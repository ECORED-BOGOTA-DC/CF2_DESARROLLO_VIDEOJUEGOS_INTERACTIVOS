<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span(style="color: #fff")
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.mb-5(data-aos="fade-right")
      .col-lg-10
        figure
          img(src='@/assets/curso/introduccion/img01.png' style="width: 750px").m-auto
    .bloque-texto-b.color-acento-contenido(data-aos="fade-left")
      .bloque-texto-b__texto        
        p.mb-0 Los principios básicos del diseño permiten bosquejar y diseñar los personajes, escenarios y <em>props</em>, que harán parte de un videojuego, para el cual se hará uso de la anatomía básica, comprendiendo la composición de los elementos de un personaje y su gestualidad. A su vez, se abordará cómo estos personajes pueden prepararse para su realización en 3D, con el diseño de un <em>blueprint</em>. Esto permitirá, integrarse en el <em>software</em> Blender versión 2.9, del cual se explicará su interfaz gráfica, además de las técnicas de modelado. Asimismo, el componente relacionará conceptos de color y texturas, materiales, texturizado y creación de uv, para elementos 3D.

</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped>
.introduccion
</style>
