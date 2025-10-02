<script setup>
defineProps({
  name: String,
})



</script>

<template>
  <div class="catalog_button">
   <img src="..\\assets\menu.svg"></img>
   <span class="button_text">{{name}}</span>
  </div>
</template>

<style scoped>
.catalog_button{
  min-width: calc(140px - 16px);
  width: calc(140px - 16px);
  border-radius: 4px;
  background: #70C05B;
  color: white;
  font-size: 16px;
  line-height: 150%;
  font-family: Rubik;
  padding: 8px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.button_text{
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
