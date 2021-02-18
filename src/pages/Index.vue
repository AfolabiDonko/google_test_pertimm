<template>
  <q-page class="flex flex-center">
    <div class="q-pa-md">
      <div class="row">
          <q-img
            src="google.png"
            spinner-color="white"
            style="height: 100%; max-width: 100%"
            img-class="my-custom-image"
            class="rounded-borders"
          >
          </q-img>
      </div>

      <div class="row">
        <div class="q-gutter-md" style="max-width: 300px">
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
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'GoogleLayout'
}
</script>
<style scoped>
  .rSk4se {
      max-height: 92px;
  }
  .k1zIA {
      height: 100%;
      margin-top: auto;
  }
  div {
      display: block;
  }
</style>
