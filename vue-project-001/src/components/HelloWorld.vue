<!-- js -->
<script setup>
// import components

import GreetingWorld from './GreetingWorld.vue'

// console.log('hello World to you')
</script>

<!-- html -->
<template>
  <h1>Hello World. Vue3</h1>
  <p>parent component for GreetingWorld</p>

  <!-- nested component -->
  <GreetingWorld />
</template>
<!-- html end -->

<!-- css -->
<style scoped>
h1 {
  color: red;
}
</style>
