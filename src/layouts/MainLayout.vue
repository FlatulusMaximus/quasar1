<template>
  <q-layout view="hHh lpr fff">
    <q-header reveal elevated class="bg-primary text-white" height-hint="98">
      <q-tabs align="left">
        <q-route-tab to="/home" label="Home" />
        <q-route-tab to="/tab" label="tab" />
        <q-route-tab to="/nix" label="Seich" />
      </q-tabs>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>

    <q-footer bordered class="bg-grey-8 text-white">
      <q-toolbar>
        <q-toolbar-title>
          <div>TA</div>
        </q-toolbar-title>
      </q-toolbar>
    </q-footer>
  </q-layout>
</template>