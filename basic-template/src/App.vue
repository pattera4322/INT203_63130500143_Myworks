<script setup>
  const msg = 'Hello Kitty'
  const headingStyle = 'color: blue'
  const paraStyle = 'text-decoration:underline'
  const imagePath = '../public/images/eiei.jpg'
</script>
 
<template>
  <h1 v-bind:style="headingStyle">INT203 Web Client II</h1>
  <h2>{{ msg }}</h2>
  <p :style="paraStyle">lecture</p>
  <img src="./assets/logo.png" />
  <img :src="imagePath" alt="eiei" srcset="" />
</template>
 
<style>

</style>
