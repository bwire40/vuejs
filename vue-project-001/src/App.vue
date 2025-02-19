<script setup>
// import components
import HelloWorld from './components/HelloWorld.vue'
import TextInterpolate from './components/TextInterpolate.vue'
import AttributeBind from './components/AttributeBind.vue'
</script>

<template>
  <p>App is the main parent component of the other components</p>
  <HelloWorld />

  <!-- text interpolate -->
  <p>Text interpolate, dynamic rendering</p>
  <TextInterpolate />
  <AttributeBind />
</template>

<style scoped></style>
