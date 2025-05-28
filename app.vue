<script setup lang="ts">
  const runtimeConfig = useRuntimeConfig();
  const appConfig = useAppConfig();
  const count = ref(1);
</script>

<template>
  <div id="app">
    <AppHeader />
    <NuxtPage />
    <AppFooter />
    <!-- <NuxtRouteAnnouncer />
    <NuxtWelcome /> -->
  </div>
</template>

<style>
  #app {
    background-color: #020420;
    color: #00DC82;
  }
</style>