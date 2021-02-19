<template>
  <div class="q-pa-md">
    <div class="column rSk4se">
      <div class="col">
        <q-img
          src="google.png"
          spinner-color="white"
          style="height: 92px; width: 272px; text-align: center;margin-top: 260px;margin-left: 40%;margin-right: 40%;"
          img-class="my-custom-image"
          class="rounded-borders"
        />
      </div>
    </div>
    <div class="column k1zIA">
      <div class="col">
        <div class="q-gutter-md" style=" background-color: green; margin-left: 25%; margin-right: 25%; min-width : 25%;width: 685px">
          <q-input rounded outlined >
            <template v-slot:prepend>
              <q-icon name="search" />
            </template>
            <template v-slot:append>
              <q-icon name="mic" />
            </template>
          </q-input>
        </div>
      </div>
      <div class="col">
        <div class="row justify-evenly" style="background-color: blue; margin-left: 25%; margin-right: 25%; width: 685px">
          <div>
            <q-btn color="white" text-color="black" label="Recherche Google"  />
            <q-btn color="white" text-color="black" label="J'ai de la chance" style="margin-left: 10px"/>
          </div>
        </div>
      </div>
    </div>
    <div class="column gyttt">
      <div class="col">
        <div>
          Google disponible en : <a href="">English</a>
        </div>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: 'GoogleLayout'
}
</script>
<style scoped>
  .rSk4se {
    height: 355px;
    display: flex;
    background-color: red;
    min-height: 92px;
    max-height: 590px;
  }
  .k1zIA {
    height: 150px;
    display: flex;
    flex-direction: column;
    background-color: yellow;
    padding: 10px;
  }
  .gyttt {
    height: 80px;
    display: flex center;
    flex-direction: column;
    background-color: green;
    text-align: center;
    padding: 10px;
  }
</style>
