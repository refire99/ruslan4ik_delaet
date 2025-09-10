<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)

</script>

<template>
    <div class="header">
       <div class="logo">

       </div>
       <div class="catalog_button">

       </div>
       <div class="search_input">

       </div>

    </div>
</template>

<style scoped>
.header{
    color: white;
    width: 100%;
    height: 72px;
    background: black;
    justify-content: space-between;
    align-items: center;
    display: flex;
}
</style>
