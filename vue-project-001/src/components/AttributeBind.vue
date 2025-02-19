<!-- js -->
<script setup>
const myBlog = 'https://metacode.hashnode.dev/'
const image =
  'https://cdn.hashnode.com/res/hashnode/image/upload/v1699003722269/af0248fe-165a-4d5e-8dda-14d47fbb320c.jpeg?w=500&h=500&fit=crop&crop=faces&auto=compress,format&format=webp'
const imgHeight = '100px'
const alt = 'my_image'
</script>

<!-- html -->
<template>
  <div style="display: flex; flex-direction: column">
    <h1>Attribute binding</h1>

    <!-- bind the url to a:href using v-bind:attr short hand is : -->
    <!-- <a v-bind:href="myBlog">Meta code</a> -->
    <a :href="myBlog">Meta code</a>

    <!-- bind image -->
    <img :src="image" :alt="alt" :title="alt" :width="imgHeight" />
  </div>
</template>

<!-- css -->
<style scoped></style>
