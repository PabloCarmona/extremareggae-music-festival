<template>
  <section class="artists" id="artists">
    <img src="../assets/artists.png" alt="Imagen de los artistas Black Omolo y Gene Garc&iacute;a" class="artists__image">
    <h1 class="artists__headline">Nuestros artistas</h1>
  </section>
</template>

<style scoped>
  .artists {
    background-image: url(../assets/bg-texture.png);
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
    z-index: 0;
    padding-bottom: 100px;
  }

  .artists__image {
    max-width: 100%;
    margin-bottom: 46px;
  }

  .artists__headline {
    text-transform: uppercase;
    font-size: 36px;
    line-height: 48px;
    font-weight: 900;
    color: #212121;
    text-shadow: 0px 2px 4px rgba(0, 0, 0, 0.5);
    margin: 0;
    text-align: center;
  }
</style>