<script setup lang="ts">
import Button from './Button.vue';
</script>

<template>
  <header>
    <Button class="cta-tickets"
      href="https://teatrolopezdeayala.es/shows/details/938/extremareggae-music-festival">Compra ya tus
      entradas</Button>
  </header>
</template>

<style scoped>
header {
  background-image: url(../assets/hero.jpg);
  background-position: center center;
  background-repeat: no-repeat;
  background-size: cover;
  width: 100vw;
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  align-items: center;
}

.cta-tickets {
  margin-block-end: 50px;
}
</style>