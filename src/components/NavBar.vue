<script setup lang="ts"></script>

<template>
  <nav>
    <ul>
      <li>
        <a href="#cartel">Cartel</a>
      </li>
      <li>
        <a href="#about-us">Con&oacute;cenos</a>
      </li>
      <li>
        <a href="#artists">Artistas</a>
      </li>
      <li>
        <a href="#partners">Patrocinadores</a>
      </li>
      <li>
        <a href="#contact">Contacto</a>
      </li>
    </ul>
  </nav>
</template>

<style scoped>
nav {
  position: absolute;
  top: 0;
  z-index: 5;
  display: flex;
  justify-content: flex-end;
  width: 100%;
  font-size: 24px;
  line-height: 37px;
  background: linear-gradient(180deg, rgba(0, 0, 0, 0.3) 66.15%, rgba(0, 0, 0, 0) 100%);
}

ul {
  display: flex;
  align-items: center;
  flex-wrap: wrap;
  padding-inline-end: 50px;
  list-style-type: none;
}

li:not(:last-child) {
  margin-right: 30px;
}

a {
  display: inline-block;
  width: 100%;
  text-transform: uppercase;
  text-decoration: none;
  color: #fff;
}
</style>