<template>
  <div class="v-container">
    <div class="v-text">{{ num }}</div>
    <button @click="click">点击+1</button>
  </div>
</template>

<script setup>
 import { ref } from "vue";
 const num = ref(0)
 const click = () => {
   num.value ++
 }
 

</script>

<style>
.v-container {
  width: 200px;
  height: 200px;
  border: 1px solid #000;
}
</style>
