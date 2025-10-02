<script setup>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/header.vue';
import catalog_button from './components/CatalogButton.vue';
import search_input from './components/SearchInput.vue';
</script>

<template>


  <Header />
  <catalog_button name="Каталог"/>
  <search_input/>
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
