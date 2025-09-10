<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)

</script>

<template>
  <div class="catalog_button">
   <img src="..\\assets\menu.svg"></img>
  </div>
</template>

<style scoped>
.catalog_button{
  border-radius: 4px;
  background: #70C05B;
  width: auto;
  padding: 8px;
}
</style>
