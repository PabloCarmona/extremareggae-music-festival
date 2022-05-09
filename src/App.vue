<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import NavBar from './components/NavBar.vue';
import Hero from './components/Hero.vue'
import Cartel from './components/Cartel.vue';
import AboutUs from './components/AboutUs.vue';
</script>

<template>
  <NavBar />
  <Hero />
  <Cartel />
  <AboutUs />
</template>

<style>
body {
  padding: 0;
  margin: 0;
}
#app {
  font-family: 'Gotham', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
