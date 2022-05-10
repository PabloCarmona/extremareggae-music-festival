<script setup lang="ts">
  defineProps<{
    name: string,
    country: string,
    socialMediaInfo: { name: string, icon: string, link: string }[],
    backgroundImageUrl: string,
    fontColor: string
  }>()
</script>
<template>
  <section class="artist" :style="`background-image: url(${backgroundImageUrl})`">
    <div class="artist__info">
      <h2 v-html="name"></h2>
      <h3>{{ country }}</h3>
    </div>
    <ul class="artist__rrss">
      <li v-for="socialMedia in socialMediaInfo" class="artist__rrss__item">
        <a :href="socialMedia.link" target="_blank">
          <img :src="socialMedia.icon" :alt="socialMedia.name">
        </a>
      </li>
    </ul>
  </section>
</template>

<style scoped>
.artist {
  background-size: cover;
  background-repeat: no-repeat;
  color: v-bind(fontColor);
  text-transform: uppercase;
  padding: 100px;
}

h2 {
  width: 350px;
  font-weight: 700;
  font-size: 64px;
  line-height: 70px;
  margin: 0;
  margin-bottom: 20px;
}

h3 {
  width: 350px;
  font-weight: 400;
  font-size: 48px;
  font-style: italic;
  line-height: 55px;
  margin: 0;
}

.artist__rrss {
  display: flex;
  align-items: center;
  margin: 0;
  padding: 0;
}

.artist__rrss__item:not(:last-child) {
  margin-right: 30px;
}
</style>