<template>
  <q-layout view="lHr lpr fFf">
      <q-header reveal class="bg-black">
        <q-toolbar>
          <q-toolbar-title>Header</q-toolbar-title>
        </q-toolbar>
      </q-header>
      <q-footer>
        <q-toolbar>
          <q-toolbar-title>Footer</q-toolbar-title>
        </q-toolbar>
      </q-footer>
      <q-page-container>
        <router-view></router-view>
      </q-page-container>
  </q-layout>
</template>

<script>
export default {
  name: 'GoogleLayout'
}
</script>
