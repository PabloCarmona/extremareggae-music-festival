<script setup lang="ts">
import Button from './Button.vue';
</script>

<template>
  <section class="cartel" id="cartel">
    <p class="cartel__text">
      <span>ExtremaReggae Music Festival</span> vuelve a la <span>Terraza del Teatro L&oacute;pez de Ayala</span> de
      Badajoz, te esperamos el <span>30 de Julio</span> con el compromiso de seguir programando reggae cultural de
      calidad al gran p&uacute;blico y darles a conocer propuestas musicales &uacute;nicas.
    </p>

    <Button class="cta-tickets"
      href="https://teatrolopezdeayala.es/shows/details/938/extremareggae-music-festival">Cartel 2022</Button>
  </section>
</template>

<style scoped>
.cartel {
  padding: 64px 150px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  background-image: url(../assets/cartel-bg.png);
  background-size: cover;
  background-repeat: no-repeat;
}

.cartel__text {
  width: 100%;
  max-width: 787px;
  font-size: 32px;
  line-height: 37px;
}

.cartel__text span {
  font-weight: 900;
  line-height: 0;
}
</style>