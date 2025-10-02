<script setup>

defineProps({
  msg: String,
})


</script>

<template>
  <div class="search_input">
   <input type="text" placeholder="Найти товар" class="search_input_p"></input>
   <img src="..\\assets\search.svg"></img>
  </div>
</template>

<style scoped>
.search_input{
  width: calc(100% - 16px);
  height: 22px;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 8px;
  border-radius: 4px;
  border: 1px solid #70C05B;
  color: #70C05B;
}
.search_input_p{
  width: 100%;
  height: 100%;
  border: none;
  outline: none;
  font-family: Rubik;
  font-size: 16px;
  line-height: 150%;
  background: transparent;
}
</style>
