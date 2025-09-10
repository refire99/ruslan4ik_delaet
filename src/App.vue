<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/header.vue';
import catalog_button from './components/catalog_button.vue';
</script>

<template>

  <HelloWorld msg="okak" />
  <Header />
  <catalog_button/>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
