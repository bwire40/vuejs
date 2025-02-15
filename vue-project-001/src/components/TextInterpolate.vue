<!-- js -->
<script setup>
const product = 'socks'
const stock = 100

const add = (a, b) => {
  return a + b
}
</script>

<!-- html -->
<template>
  <p>{{ product }}</p>
  <p>{{ stock }}</p>
  <p>{{ add(3, 5) }}</p>
</template>

<!-- css -->
<style scoped>
p {
  color: blue;
}
</style>
