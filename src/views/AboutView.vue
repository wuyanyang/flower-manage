<template>
  <div class="about">
    <div class="container"><input type="text" class="myinput" :value= "inputValue"></div>
  </div>
</template>
<script lang="ts" setup>
import {ref} from 'vue'
  const inputValue = ref<string>("heihei")
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }

  .container {
    background-color: bisque;
    border:1px solid #0f0;
    display: flex;
    align-items: center;
    justify-content: center;
    height: 500px;
    width: 300px;
  }
}
</style>
