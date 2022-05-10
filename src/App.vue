<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://vuejs.org/api/sfc-script-setup.html#script-setup
import NavBar from './components/NavBar.vue';
import Hero from './components/Hero.vue'
import Cartel from './components/Cartel.vue';
import AboutUs from './components/AboutUs.vue';
import Artists from './components/Artists.vue';
import Artist from './components/Artist.vue';

const BLACK_OMOLO_RRSS = [
  { name: 'Instagram', link: 'https://www.instagram.com/blackomolo/', icon: '/src/assets/instagram.svg' },
  { name: 'Spotify', link: 'https://open.spotify.com/artist/2l3Pw2e2c6xlA2gmeXJThH?si=y784JulIQ6mgB4EYdYTtJw&nd=1', icon: '/src/assets/spotify.svg' }
]
</script>

<template>
  <NavBar />
  <Hero />
  <Cartel />
  <AboutUs />
  <Artists />
  <Artist
    backgroundImageUrl="/src/assets/black-omolo.jpg"
    name="Black Omolo<br>&amp; Militanti Band"
    country="(Kenia - Portugal)"
    :socialMediaInfo="BLACK_OMOLO_RRSS"
    fontColor="#fff" />
  <Artist
    backgroundImageUrl="/src/assets/gene-garcia.jpg"
    name="Gene Garc&iacute;a &amp; The Rockets"
    country="(Espa&ntilde;a)"
    :socialMediaInfo="BLACK_OMOLO_RRSS"
    fontColor="#212121" />
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
