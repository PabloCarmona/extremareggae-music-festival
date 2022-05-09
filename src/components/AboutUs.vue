<template>
  <section class="about-us" id="about-us">
    <div class="about-us__overlay"></div>
    <p class="about-us__text about-us__text--first">
      En esta segunda edici&oacute;n volveremos a mostrar un festival para disfrutar en familia, con los amigos o en pareja, donde vamos a gozar de una velada &uacute;nica y para el recuerdo.
    </p>
    <p class="about-us__text about-us__text--second">
      Queremos seguir produciendo al p&uacute;blico hispanoluso alegr&iacute;a, emoci&oacute;n, m&uacute;sica sanadora y una nueva alternativa tan profunda y rica como es la m&uacute;sica y cultura reggae.
    </p>
    <p class="about-us__text about-us__text--third">
      La terraza del Teatro L&oacute;pez de Ayala de Badajoz, albergar&aacute; por segundo a&ntilde;o consecutivo nuestro evento.
    </p>
  </section>
</template>

<style scoped>
  .about-us {
    background-image: url(../assets/about-us-bg.png);
    background-size: cover;
    background-repeat: no-repeat;
    width: 100vw;
    min-height: 1800px;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(3, 1fr);
    position: relative;
    z-index: 0;
  }

  .about-us__overlay {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    z-index: 3;
    background-color: rgba(0, 0, 0, 0.45);
  }

  .about-us__text {
    width: 100%;
    max-width: 548px;
    z-index: 5;
  }

  .about-us__text--first {
    text-align: right;
    grid-column: 2 / 3;
    grid-row: 1 / 2;
    justify-self: end;
    padding-inline-end: 100px;
    padding-block-start: 80px;
  }

  .about-us__text--second {
    grid-row: 2 / 3;
    align-self: center;
    padding-inline-start: 100px;
  }

  .about-us__text--third {
    max-width: 700px;
    text-align: right;
    grid-column: 2 / 3;
    grid-row: 3 / 4;
    justify-self: end;
    align-self: end;
    padding-inline-end: 100px;
    padding-block-end: 80px;
  }

  .about-us p {
    font-size: 40px;
    line-height: 48px;
    font-weight: 900;
    color: #FFCB40;
    text-shadow: 0px 4px 4px rgba(255, 203, 64, 0.45);
  }
</style>