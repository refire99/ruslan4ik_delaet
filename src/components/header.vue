<script setup>
import { ref } from 'vue'
import search_input from './SearchInput.vue';
import catalog_button from './CatalogButton.vue';
defineProps({
  msg: String,
})

const count = ref(0)

</script>

<template>
    <div class="header">
      <div class="header_container">
          <div class="logo_search_container">
              <div class="logo_main">
                <img src="../assets/logo_main.svg"></img>
              </div>
              <div class="search_input" style="display: flex; gap: 16px; width: 100%;">
                <catalog_button name="Каталог"/>
                <search_input/>
              </div>
          </div>
      </div>
    </div>
</template>

<style scoped>
.logo_search_container{
  display: flex;
  align-items: center;
  gap: 40px;
  width: 100%;
}
.header{
    color: white;
    width: 100%;
    height: 72px;
    background: rgb(255, 0, 0);
    justify-content: center;
    align-items: center;
    display: flex;
}
.header_container{
  background: rgb(0, 255, 170);
  width: 1208px;
  height: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
</style>
