<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span(style="color: #fff") 5
      h1 Materiales y texturizado
    p.mb-5(data-aos="fade-right") Los materiales permiten dar atributos al objeto para que las superficies de estos tengan el aspecto que se busca, con ello se puede controlar el color, la cantidad de reflexión, la rugosidad de ese material, su transparencia, su refracción, además de que pueden contener texturas y, según todos estos parámetros, ver cómo la luz interactúa sobre él.
    .row.justify-content-center.mb-5(data-aos="fade-left")
      .col-lg-10
        table.mb-4(style="border:0px") 
          tr(style="border:0px")
            td.p-1(width=18 style="border:0px; background-color: #9D91EC; color: white") 1
            td(style="border:0px; background-color: #F2F0FD;") Estos materiales permiten que se creen gran variedad de estilos, como vidrio, metal, tela, plástico, humo, fuego, madera y el material estilo #[i cartoon].        
        table.mb-4(style="border:0px") 
          tr(style="border:0px")
            td.p-1(width=18 style="border:0px; background-color: #9D91EC; color: white") 2
            td(style="border:0px; background-color: #F2F0FD;")  Los materiales constan de diferentes propiedades, una de ellas es cómo absorbe la luz, si se refracta o se refleja, esto quiere decir que un material metálico puede reflejar bastante luz, en cambio un material como una tela puede absorber luz y no reflejar demasiado.
        table(style="border:0px") 
          tr(style="border:0px")
            td.p-1(width=18 style="border:0px; background-color: #9D91EC; color: white") 3
            td(style="border:0px; background-color: #F2F0FD;")  Los materiales de volumen permiten crear humo y fuego, y el material de desplazamiento puede generar volumen en la malla, esto puede ser simulado o puede ser real.
    p.mb-5(data-aos="fade-right") Finalmente, podrá conocer los materiales y diferentes tipos de texturas. 
    h3.mb-4(data-aos="fade-right") Physically Based Rendering (PBR)
    .row.justify-content-center.mb-5
      .col-lg-10
        figure(data-aos="fade-down")
          img(src='@/assets/curso/tema5/img01.png', alt='Texto que describa la imagen')
    h3(data-aos="fade-right") Texturizado
    .row.align-items-center.mb-0.mb-lg-4(data-aos="fade-left")
      .col-lg-6.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema5/img02.png', alt='Texto que describa la imagen')
      .col-lg-6
        p.mb-4 Para el texturizado se procede a sacar las uv, que diciéndolo de otra manera, son las costuras que tiene el personaje, como si de un vestido se tratase, con ello se puede hacer en 2D, lo que luego se quiere ver proyectado en 3D. Estos cortes son los que finalmente se posicionan en el apartado de la pestaña uv en el #[i software] de 3D.
        p.mb-0 En el ejemplo se puede observar un cubo 3D, con unas costuras de color rojo en sus filos, diseccionado y abierto como una caja que se va a plegar, a la derecha está dimensionado en 2D esa misma caja, pero esta vez abierta. Si se imagina  que estas piezas se doblan y se pegan, se creará el cubo. El cubo tiene 6 lados, que perfectamente se observan en la uv abierta, en 6 piezas unidas.
    p.mb-4(data-aos="fade-right") Estas uv quedan grabadas en el objeto 3D, lo que permitirá que las texturas que se vayan a aplicar hagan uso de las coordenadas del #[i uv mapping].
    p.mb-5(data-aos="fade-right") Una forma de poner a una malla de baja densidad de poligonaje detalles de alta es haciendo los dos modelos, el de alta y el de baja, para después al de baja aplicarle el modelo de alta como mapa de desplazamiento, lo que hace que no se creen más polígonos, pero simula mayor detalle al dar la sensación mediante profundidad que hay relieves y texturas, al generar relieves en los 3 ejes.
    .row.justify-content-center(data-aos="fade-left")
      .col-lg-8
        LineaTiempoD.color-secundario
          .row.justify-content-center(numero="1" titulo="Mapa <em>diffuse</em>")
            .col-8.col-lg-3.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema5/img03.jpg', alt='Texto que describa la imagen') 
            .col-lg-9.d-flex.align-items-center
              p Es la textura primaria, el color sobre los elementos 3D.
          .row.justify-content-center(numero="2" titulo="Mapa desplazamiento")
            .col-8.col-lg-3.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema5/img04.jpg', alt='Texto que describa la imagen') 
            .col-lg-9.d-flex.align-items-center
              p Brinda detalles al modelado, en este caso, desplazando y afectando los vértices del modelo.
          .row.justify-content-center(numero="3" titulo="Mapa <em>specular</em>")
            .col-8.col-lg-3.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema5/img05.jpg', alt='Texto que describa la imagen') 
            .col-lg-9.d-flex.align-items-center
              p La textura que define el brillo se utiliza en escala de grises, entre más claro más brillo, y más oscuro, menos brillo.
          .row.justify-content-center(numero="4" titulo="Mapa normal")
            .col-8.col-lg-3.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema5/img06.jpg', alt='Texto que describa la imagen') 
            .col-lg-9.d-flex.align-items-center
              p Al generar relieves en los 3 ejes brinda detalles al modelado, sin desplazar vértices.
          .row.justify-content-center(numero="5" titulo="Mapa <em>bump</em>")
            .col-8.col-lg-3.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema5/img07.jpg', alt='Texto que describa la imagen') 
            .col-lg-9.d-flex.align-items-center
              p Antecesora a la textura normal map, pero aun en uso, mediante escala de grises da la sensación de relieve, donde lo más blanco está más hacia adelante y lo más negro a profundidad.

</template>

<script>
export default {
  name: 'Tema5',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass" scoped></style>
