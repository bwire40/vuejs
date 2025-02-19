<!-- js -->
<script setup>
const product = 'socks'
const stock = 100

const add = (a, b) => {
  return a + b
}

const hello = () => {
  alert('Hello there')
}
</script>

<!-- html -->
<template>
  <p>{{ product }}</p>
  <p>{{ stock }}</p>
  <p>{{ add(3, 5) }}</p>

  <button :onclick="hello">Click me</button>
</template>

<!-- css -->
<style scoped>
p {
  color: blue;
}

button {
  padding: 12px 14px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
  background-color: rgb(68, 200, 68);
  color: white;
  font-size: large;
}
</style>
