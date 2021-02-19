<template>
  <q-layout view="lHr lpr fFf">
      <q-header style="background-color: white;">
        <q-toolbar class="text-black q-my-md" style="background-color: white;">
          <q-space />
          <q-btn-toggle style="font-size: 13px;"
            flat stretch
            :options="[
              {label: 'Gmail', value: 'gmail'},
              {label: 'Image', value: 'image'},
            ]"
          />
        </q-toolbar>
      </q-header>
      <q-footer>
        <q-toolbar class="bg-grey-3" style="color: black;">
          <q-toolbar-title style="font-size: 13px;">A propos</q-toolbar-title>
          <q-toolbar-title style="font-size: 13px;">Publicité</q-toolbar-title>
          <q-toolbar-title style="font-size: 13px;">Entreprise</q-toolbar-title>
          <q-space /><q-space /><q-space />
          <q-toolbar-title style="font-size: 13px;">Confidentialité</q-toolbar-title>
          <q-toolbar-title style="font-size: 13px;">Conditions</q-toolbar-title>
          <q-toolbar-title style="font-size: 13px;">Paramètres</q-toolbar-title>
          <q-toolbar-title style="font-size: 13px;">A propos</q-toolbar-title>
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
