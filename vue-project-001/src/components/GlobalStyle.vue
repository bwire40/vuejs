<script setup>
import LocalStyle from './LocalStyle.vue'
// import LocalStyle from './LocalStyle.vue'
</script>

<template>
  <h1 class="text-red">Global component</h1>

  <LocalStyle />

  <!-- localstyle component -->
</template>

<!-- <style>
/* global style */
.text-red {
  color: red;
}
</style> -->

<style scoped>
/* local styling */

.text-red {
  color: green;
}
</style>
