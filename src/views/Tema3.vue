<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span(style="color: #fff") 3
      h1 Texturas y color
    .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-right")
      .t3_bloque1.bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/img01.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 En la definición de un personaje se hace necesario conocer las texturas, que son parte de los objetos diseñados por el hombre y la naturaleza, se pueden sentir a partir del tacto, debido a los altos niveles de relieve que estas contienen, algunas de ellas cuentan con características rugosas, suaves, ásperas, blandas, viscosas, duras, filosas, entre otras. Esto se debe a la cantidad de elementos repetidos que tienen y a la altura de los relieves o hendiduras que poseen, igualmente, de forma visual se puede apreciar cada uno de estos elementos, gracias a las sombras y luces que se generan en el elemento.
    p.mb-4(data-aos="fade-right") En el desarrollo de videojuegos, los colores tienen diversos significados y funcionalidades, esenciales en el diseño de escenarios idóneos que logren transmitir diferentes sensaciones y emociones en puntos concretos del juego, a esto se le conoce como psicología del color. Un mismo color puede brindar sentimientos divergentes dependiendo de la situación, por ejemplo, el rojo se usa generalmente para simbolizar el amor, pero también se puede relacionar con la agresión; o el verde muchas veces lo asociamos con la naturaleza, la tranquilidad, de igual forma, puede representar algo tóxico o venenoso, es decir, todo depende del contexto en el que se encuentre.
    p.mb-5(data-aos="fade-right") A continuación, se podrá conocer las diferentes texturas y las disposiciones que hay para los colores.  
    TabsA.color-acento-contenido.mb-5(data-aos="fade-left")
      .tarjeta.color-acento-contenido--borde.p-4.p-lg-5(titulo="Texturas artificiales")
        .row
          .col-lg-5.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema3/img03.png')
              figcaption.mt-3 Referencia de la imágen: <a href='https://www.pexels.com/es-es/foto/hoja-de-metal-con-gota-de-patron-5676470/' target='_blank'>#[span.txt-c1 https://www.pexels.com/es-es/foto/ hoja-de-metal-con-gota-de-patron-5676470/]</a>
          .col-lg-6
            p Son objetos diseñados por el hombre, como una lata metálica, una baldosa, una llanta, una tela, un tejido, entre otros.
          .col-lg-1
      .tarjeta.color-acento-contenido--borde.p-4.p-lg-5(titulo="Texturas naturales")
        .row
          .col-lg-5.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema3/img02.png')
              figcaption.mt-3 Referencias de las imágenes: Hoja: <a href='https://www.pexels.com/es-es/foto/hoja-verde-2178028/' target='_blank'>#[span.txt-c1 https://www.pexels.com/es-es/foto/ hoja-verde-2178028/]</a> Tronco: <a href='https://polyhaven.com/a/bark_brown_02' target='_blank'>#[span.txt-c1 https://polyhaven.com/a/ bark_brown_02]</a>
          .col-lg-6
            p Hacen parte de la misma naturaleza, como hojas, troncos, rocas, entre otras.
          .col-lg-1
      .tarjeta.color-acento-contenido--borde.p-4.p-lg-5(titulo="Texturas orgánicas")
        .row
          .col-lg-5.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema3/img04.png')
              figcaption.mt-3 Referencia de la imágen Tronco: <a href='https://polyhaven.com/a/bark_brown_02' target='_blank'>#[span.txt-c1 https://polyhaven.com/ a/bark_brown_02]</a>
          .col-lg-6
            p Tienen elementos que también se repiten de manera constante, pero tienen variación en sus formas. 
          .col-lg-1
      .tarjeta.color-acento-contenido--borde.p-4.p-lg-5(titulo="Texturas geométricas")
        .row
          .col-lg-5.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema3/img05.png')
              figcaption.mt-3 Referencia de la imágen: <a href='https://dl.polyhaven.com/file/ph-assets/Textures/jpg/1k/blue_floor_tiles_01/blue_floor_tiles_01_diff_1k.jpg' target='_blank'>#[span.txt-c1 https://dl.polyhaven.com/file/ ph-assets/Textures/jpg/1k/ blue_floor_tiles_01/blue_floor _tiles_01_diff_1k.jpg]</a>
          .col-lg-6
            p Las texturas tienen patrones geométricos que se repiten constantemente con formas básicas.
          .col-lg-1
      .tarjeta.color-acento-contenido--borde.p-4.p-lg-5(titulo="Texturas gráficas")
        .row
          .col-lg-5.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema3/img06.png')
              figcaption.mt-3 Referencia de la imágen: <a href='https://polyhaven.com/a/side_table_01' target='_blank'>#[span.txt-c1 https://polyhaven.com/a/ side_table_01]</a>
          .col-lg-6
            p.mb-4 Se pueden capturar a través de una cámara fotográfica, un escáner, o recrearlos en papel a través de pintura u otros elementos, que posteriormente pueden ser capturados para ser digitalizados. Otra forma es una representación virtual del mundo real, realizada a través de #[i software] 2D o 3D, en la que se simulan formas geométricas, orgánicas, naturales y artificiales, con la finalidad de aplicar estas texturas en diferentes elementos, como personajes, escenarios, props, entre otros, dotándolos de mayor credibilidad y acercamiento al mundo real. 
            p Estas texturas también facilitan los acabados de los objetos, ya que estas imágenes pueden repetirse infinitamente, por ejemplo, si se le quiere dar textura de tela (jean) a un pantalón, con un patrón repetitivo o una textura tipo madera se puede lograr el efecto, gracias a estas texturas.
          .col-lg-1
    .titulo-sexto.color-acento-contenido
          p.mb-0 #[b Tabla 1]
          p.mb-0 Simbolismo psicológico de los colores a través de emociones que se transmiten    
    .tabla-b.color-acento-contenido.mb-5(data-aos="fade-left")
      table            
        tr.tabla-b__header
          th Color
          th(colspan=3) Emociones positivas
          th(colspan=3) Emociones negativas
        tr
          td.text-center(style="color:#000000") 
            b Negro
          td.text-center(colspan=3) Sofisticación, seguridad, poder, sustancia, elegancia, autoridad.
          td.text-center(colspan=3) Opresión, amenaza, frialdad, pesadez, luto, maldad.
        tr  
          td.text-center(style="color:#9B9B9B") 
            b Gris        
          td.text-center(colspan=3) Atemporalidad, fuerza, fiabilidad, neutralidad, balance, inteligencia.
          td.text-center(colspan=3) Desconfianza, depresión, adormecimiento, mansedumbre, falta de energía.
        tr
          td.text-center(style="color:#C4C4C4") 
            b Blanco
          td.text-center(colspan=3) Pureza, sofisticación, claridad, frescura, simplicidad, limpieza.
          td.text-center(colspan=3) Esterilidad, frialdad, elitismo, hostilidad, aislamiento, vacío.
        tr
          td.text-center(style="color:#DE3737") 
            b Rojo
          td.text-center(colspan=3) Aventura, poder, pasión, acción, fuerza, intrepidez, amor.
          td.text-center(colspan=3) Ira, desafío, peligro, advertencia, agresión, dolor.
        tr
          td.text-center(style="color:#EC942F") 
            b Naranja
          td.text-center(colspan=3) Valor, confidencialidad, calidez, optimismo, entusiasmo, energía.
          td.text-center(colspan=3) Privación, frustración, inmadurez,  frivolidad, letargo, ignorancia.
        tr
          td.text-center(style="color:#F2CB0A") 
            b Amarillo
          td.text-center(colspan=3) Optimismo, felicidad, extroversión, curiosidad, creatividad, calidez.
          td.text-center(colspan=3) Irracionalidad, temor, precaución,  cobardía, ansiedad, frustración.
        tr
          td.text-center(style="color:#6CDF20") 
            b Verde 
          td.text-center(colspan=3) Naturaleza, prosperidad, esperanza, suerte, armonía, frescura, salud.
          td.text-center(colspan=3) Aburrimiento, estancación, envidia, insipidez, enfermedad, enervación.
        tr
          td.text-center(style="color:#14C9CF") 
            b Turquesa
          td.text-center(colspan=3) Comunicación, verdad, claridad, calma, salud, poder, inspiración.
          td.text-center(colspan=3) Jactancia, misterio, desconfianza,  reticencia, indiferencia.
        tr
          td.text-center(style="color:#0B5FF1") 
            b Azul
          td.text-center(colspan=3) Simpatía, armonía, amistad, lógica, seguridad, serenidad, confianza.
          td.text-center(colspan=3) Frialdad, indiferencia, antipatía, desánimo, inapetencia, descuido.
        tr
          td.text-center(style="color:#AF16E5") 
            b Violeta
          td.text-center(colspan=3) Sabiduría, riqueza, imaginación, misterio, creatividad, lujo, fantasía.
          td.text-center(colspan=3) Introversión, decadencia, mal humor, supresión, inferioridad, extravagancia.
        tr
          td.text-center(style="color:#E90DCC") 
            b Magenta
          td.text-center(colspan=3) Transformación, creatividad, pasión, imaginación, balance, innovación.
          td.text-center(colspan=3) Indignación, inconformidad, efimeridad, impulsividad, ligereza.
        tr
          td.text-center(style="color:#6D1111") 
            b Café
          td.text-center(colspan=3) Seriedad, calidez, responsabilidad, terrosidad, soporte, autenticidad.
          td.text-center(colspan=3) Falta de humor y sofisticación, suciedad, tristeza, conservadurismo.
    h2(data-aos="fade-right") Temperatura del color
    SlyderC.mb-5(:datos="datosSlyder")(data-aos="fade-down")
    p.mb-5(data-aos="fade-right") Comparando las imágenes anteriores, percibimos que cada una de ellas evoca emociones diferentes. ¿Por qué sucede esto?, la respuesta está en el uso de los colores. En la imagen de la derecha se destacan los colores azules, violetas y algunos tintes de verde que nos dan la sensación de que se trata de un mundo nocturno o frío; en contraste con la imagen de la izquierda en la que se destacan los colores amarillos, amarillos verdosos, naranjas, terrosos y ocres que nos brindan la ilusión de un mundo más cálido.
    .bloque-texto-g.color-principal.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-left")
      .t3_bloque2.bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/img08.png')})`}"
      )
      .t3_bloque2.bloque-texto-g__texto.p-4.py-5
        p.mb-0 Esto significa que brindan una percepción subjetiva de la sensación de temperatura y con base a esta se puede determinar si se trata de colores cálidos o fríos, los cuales influyen en las emociones y afectan el estado de ánimo.
    .row.mb-5(data-aos="fade-right")
      .col-lg-6.py-5.d-flex.bg-c1
        div
          figure.mb-4
            img(src='@/assets/curso/tema3/img09.svg') 
          .row.justify-content-center
            .col-lg-8
              h1.text-center Colores cálidos o activos
              p.text-center Son aquellos asociados a efectos visuales de calor como la luz solar, el fuego, los atardeceres, la arena, la playa, etc., evocando fuertes sentimientos que promueven el movimiento. Funcionan bien en espacios grandes, haciéndolos sentir seguros, acogedores y más cercanos.      
      .col-lg-6.py-5.d-flex.bg-c2
        div
          figure.mb-4
            img(src='@/assets/curso/tema3/img10.svg') 
          .row.justify-content-center
            .col-lg-8
              h1.text-center(style="color:white") Colores fríos o pasivos
              p.text-center(style="color:white")  Se relacionan con efectos visuales asociados al frío como la luz de luna, el agua, el amanecer, la nieve, naturaleza verde, etc., transmitiendo una sensación de frescura y calma. Funcionan bien en espacios pequeños, aumentando la percepción de su tamaño, haciéndolos sentir más grandes, abiertos y lejanos.
    p.mb-5(data-aos="fade-right") Realizando una mezcla adecuada de colores cálidos y fríos se logra un equilibrio con un mayor contraste y mejor definición, que mejora la estética del videojuego, haciéndolo más agradable para el espectador.
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-6
        p.BorTit Temperatura del color y sus efectos en la mente    
        ImagenInfografica.color-secundario.mb-5
          template(v-slot:imagen)                    
            figure
              img(src='@/assets/curso/tema3/img11.svg', alt='Texto que describa la imagen')
          div.tarjeta.color-acento-botones.p-3(x="12%" y="33.5%")            
            p.mb-0 Evocan sensaciones de resequedad, el ánimo, algunos estadios de la excitación, movimiento y energía.
          div.tarjeta.color-acento-botones.p-3(x="12%" y="59%")            
            p.mb-0 Se relacionan con la humedad, la calma y estadios de depresión, evocan además frescura, dinamismo y vida.
          div.tarjeta.color-acento-botones.p-3(x="12%" y="77%")            
            p.mb-0 Su percepción no genera sensación térmica y por su efecto visual posibilita utilizarse en decoraciones y vestimentas sobrias.
          div(x="57%" y="8%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #D5B64C") Dorado
            p Opulencia
          div(x="57%" y="14.3636%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #4D2311") Marrón
            p Profundidad o experiencia
          div(x="57%" y="20.7272%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #F4E703") Amarillo
            p Actitud positiva y alegría
          div(x="57%" y="27.0909%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #E42622") Rojo
            p Pasión o excitación
          div(x="57%" y="33.4545%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #EB007F") Rosa
            p Feminidad
          div(x="57%" y="39.8181%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #C5C5C5") Plata
            p Intelectualidad
          div(x="57%" y="46.1818%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #029BDD") Azul
            p Tristeza o depresión
          div(x="57%" y="52.5454%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #43B035") Verde
            p Renovación o vida
          div(x="57%" y="58.9090%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #7D2283") Violeta
            p Espiritualidad
          div(x="57%" y="65.2727%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #747476") Gris
            p Neutralidad y serenidad
          div(x="57%" y="71.6363%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #FFFFFF") Blanco
            p Pureza
          div(x="57%" y="78%")
            h4.mb-0.BorTit2(style="border-left: 5px solid #010101") Negro
            p Elegancia
    figure.mb-5(data-aos="fade-right")
      img(src='@/assets/curso/tema3/img12.png', alt='Texto que describa la imagen')
    p.mb-5(data-aos="fade-left") Adicionalmente, puede conocer sobre la teoría del color y cómo se requiere de una referencia para mezclar los colores y conseguir un efecto en concreto:
    h2(data-aos="fade-right") Teoría del color
    .row.justify-content-center(data-aos="fade-left")
      .col-lg-10
        LineaTiempoD.color-secundario
          .row(numero="1" titulo="Modelos de color")
            p.mb-5 Los modelos de color permiten catalogar los colores y que se pueda trabajar con ellos por medios digitales. A través de los modelos se accede a diferentes sistemas para visualizar y modificar una imagen:
            .row.mb-5
              .col-lg-4.ps-5
                figure.mb-4
                  img(src='@/assets/curso/tema3/img14.svg', alt='Texto que describa la imagen') 
                b Modelo RGB
                p Modelo aditivo que se basa en los colores luz. El ojo humano cuenta con 3 tipos de conos o células foto receptoras que determinan los 3 colores primarios: rojo, verde y azul (RGB por siglas en inglés). De la combinación de estos 3 se obtiene el color blanco y la ausencia de los mismos dará como resultado el negro. Este modelo de color es usado para toda clase de dispositivos como pantallas, celulares, etc.
              .col-lg-4.ps-5
                figure.mb-4
                  img(src='@/assets/curso/tema3/img15.svg', alt='Texto que describa la imagen')
                b Modelo CMYK
                p Modelo sustractivo basado en los colores pigmento o físicos. Los colores primarios en este modelo son: amarillo, cían y magenta (CMYK por sus siglas en inglés). Al contrario del modelo RGB, la combinación de los 3 primarios genera el color negro (#[i key] o #[i black]). Este modelo es usado en pintura, tintes e impresión.
              .col-lg-4.ps-5
                figure.mb-4
                  img(src='@/assets/curso/tema3/img16.svg', alt='Texto que describa la imagen')
                b Modelo HSV
                p Se basa en las propiedades del color (tono, saturación y luminosidad), las cuales se explican en mayor detalle en la siguiente lección.
          .row(numero="2" titulo="Propiedades del color")
            .col-lg-6
              figure
                img(src='@/assets/curso/tema3/img13.png', alt='Texto que describa la imagen') 
            .col-lg-6
              b a. Tono (#[i Hue])
              p Es el color en concreto y ayuda a diferenciarlos. Por ejemplo, al ver un objeto se dice que tiene un tono azul o anaranjado.
              b b. Saturación (#[i Saturation])
              p Intensidad o pureza del color. En otras palabras, la cantidad de gris que se le ha agregado a un tono; así entre más saturado es un color, más vibrante es, mientras que, entre menos saturado, dará mayor descanso al ojo.
              b c. Luminosidad o valor (#[i Value])
              p Describe el valor de claridad u oscuridad, en otras palabras, cantidad relativa de blanco o negro en un tono. Si agregamos el blanco a un color, obtendremos valores más claros del tono, llamados tintes. Por otro lado, si el que agregamos es el negro, tendremos valores más oscuros del tono, conocidos como matices. Por ejemplo, decimos que el rosa es un tinte del color rojo primario y el borgoña o rojo oscuro es un matiz (Whelan, 1994).
          .row(numero="3" titulo="Círculo cromático")
            .col-lg-5
              figure
                  img(src='@/assets/curso/tema3/img17.svg', alt='Texto que describa la imagen')
            .col-lg-7
              p Se divide en doce segmentos, incluyendo los tonos primarios, secundarios y terciarios. Los tres colores primarios: rojo, amarillo y azul, forman un triángulo equilátero dentro del círculo. Si se mezclan en igual medida dos colores primarios, se obtiene un color secundario; y si se mezcla un primario con un secundario se tiene un terciario.
          div(numero="4" titulo="Armonía del color")
            p.mb-5 Se debe saber que algunos colores se ven mejor juntos que otros, pero esto puede generar confusión si se trata de recordar cada uno. Por tanto, a continuación, se verán los 6 esquemas más efectivos de la armonía de color:
            .row.mb-4
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img18.png', alt='Texto que describa la imagen')
                b Mocromático
                p Es uno de los más fáciles de recordar, ya que es un solo color. Debido a la ausencia de otros colores, el espectador se enfoca en las diferencias de valor y saturación.
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img19.png', alt='Texto que describa la imagen')
                b Análogo
                p Se usan colores adyacentes uno del otro. Es un esquema presente en la naturaleza, por ende, crean una sensación de calma, paz y comodidad.
            .row.mb-4
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img20.png', alt='Texto que describa la imagen')
                b Complementario
                p Es el esquema más popular, donde se usan colores de lados opuestos del círculo. Naturalmente siempre van bien juntos; sin embargo, como en el esquema de triada, se debe elegir un color predominante y usar el tono complementario para crear contraste o puntos de interés.
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img21.png', alt='Texto que describa la imagen')
                b Triada
                p Quizás es una de las más difíciles de usar correctamente. Son tres colores que son equidistantes. El reto está en el equilibrio de cada uno de los tonos, dado que al usarse en la misma medida generará caos. Suele usarse para escenas con estilo cartoon, orientado al público infantil.
            .row.mb-4
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img22.png', alt='Texto que describa la imagen')
                b Complementario dividido
                p Similar al complementario, pero este esquema usa tres colores. Se debe seleccionar el tono complementario y dividirlo, es decir, tomar los dos colores adyacentes. Es útil para extender las posibilidades de la paleta de color, cuando dos tonos no son suficientes.
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img23.png', alt='Texto que describa la imagen')
                b Complementario doble
                p Justo como el esquema complementario pero doble. Dos pares de colores complementarios (sin importar su posición dentro del círculo). Se debe ser muy cuidadoso con este esquema, pues sin el equilibrio adecuado creará caos. Lo mejor es usar un par en primer plano y el otro en el fondo.
            .row.justify-content-center
              .col-lg-8
                a.anexo.mb-4.mb-lg-0(href="https://color.adobe.com/es/create/color-wheel" target="_blank")
                  .anexo__icono
                    img(src="@/assets/template/icono-link.svg")
                  .anexo__texto
                    p <b>Adobe Color.</b> Para crear paletas de color y jugar con diferentes esquemas puede consultar la herramienta creada por Adobe llamada Adobe Color, anteriormente conocida como Kuler desde internet.
          div(numero="5" titulo="Psicología del color")
            p.mb-5 Como lo menciona Bride M. Whelan, “El color es a la vez simple y complejo. Este significa cosas distintas para distintas personas en culturas diferentes. Ningún color es visto del mismo modo por dos personas. El color es personal y universal, y envía mensajes de inagotable variedad”. (Whelan, 1994).
            .row.mb-4
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img24.svg', alt='Texto que describa la imagen')
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img25.svg', alt='Texto que describa la imagen')
            .row.mb-4
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img26.svg', alt='Texto que describa la imagen')
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img27.svg', alt='Texto que describa la imagen')
            .row.mb-4
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img28.svg', alt='Texto que describa la imagen')
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img29.svg', alt='Texto que describa la imagen')
            .row.mb-4
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img30.svg', alt='Texto que describa la imagen')
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img31.svg', alt='Texto que describa la imagen')
            .row.mb-4
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img32.svg', alt='Texto que describa la imagen')
              .col-lg-6
                figure.mb-3
                  img(src='@/assets/curso/tema3/img33.svg', alt='Texto que describa la imagen')
    
</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    datosSlyder: [
      {
        titulo:
          'Escenas del videojuego <em>Ori and The Blind Forest</em> (2015)',
        imagen: require('@/assets/curso/tema3/img07.png'),
        leyendaImagen:
          'Referencia de la imágen: https://nerdmacia.cl/nerdview-ori- and-the-will-of-the-wisp/thumb-1920-928114/',
      },
      {
        titulo:
          'Escenas del videojuego <em>Ori and The Blind Forest</em> (2015)',
        imagen: require('@/assets/curso/tema3/img34.jpg'),
        leyendaImagen:
          'Referencia de la imágen: https://nerdmacia.cl/nerdview-ori- and-the-will-of-the-wisp/thumb-1920-928114/',
      },
    ],
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
