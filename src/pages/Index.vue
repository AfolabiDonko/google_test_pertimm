<template>
  <div class="q-pa-md">
    <div class="column layout_image">
      <div class="col">
        <q-img
          src="google.png"
          spinner-color="white"
          img-class="my-custom-image"
          class="rounded-borders img"
        />
      </div>
    </div>
    <div class="column layout_input">
      <div class="col">
        <div class="q-gutter-md input_div">
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
        <div class="row justify-evenly button_div">
          <div>
            <q-btn class="btn_search" label="Recherche Google" />
            <q-btn class="btn_lucky" label="J'ai de la chance" />
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
  .layout_image {
    height: 260px;
    display: flex;
    min-height: 92px;
    max-height: 590px;
  }
  .layout_input {
    height: 150px;
    display: flex;
    flex-direction: column;
    padding: 10px;
  }
  .img {
    height: 92px;
    width: 272px;
    text-align: center;
    margin-top: 160px;
    margin-left: 42%;
    margin-right: 42%;
  }
  .btn_search {
    background: #f8f9fa;
    color: black;
    font-size:12px;
  }
  .btn_lucky {
    background: #f8f9fa;
    color: black;
    font-size:12px;
    margin-left: 10px
  }
  .input_div {
    margin-left: 32%;
    margin-right: 32%;
    width: 685px;
  }
  .button_div {
    margin-left: 32%;
    margin-top: 1%;
    margin-right: 32%;
    width: 685px;
  }
  .gyttt {
    height: 80px;
    display: flex center;
    flex-direction: column;
    text-align: center;
    padding: 10px;
  }
</style>
