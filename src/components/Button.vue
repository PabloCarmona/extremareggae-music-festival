<script setup lang="ts">
  defineProps<{
    href: string
  }>()
</script>

<template>
  <a target="_blank" :href="href">
    <slot></slot>
  </a>
</template>

<style scoped>
  a {
    text-decoration: none;
    text-transform: uppercase;
    background-color: #FFCB40;
    color: #fff;
    border: 0;
    border-radius: 6px;
    /* font-family: 'Gotham Black', sans-serif; */
    font-family: 'Oswald', sans-serif;
    font-size: 24px;
    line-height: 37px;
    padding: 24px 80px;
    transition: all ease-in 200ms;
  }

  a:hover {
    box-shadow: 0px 4px 4px rgba(255, 203, 64, 0.45);
    transform: scale(1.05);
  }
</style>