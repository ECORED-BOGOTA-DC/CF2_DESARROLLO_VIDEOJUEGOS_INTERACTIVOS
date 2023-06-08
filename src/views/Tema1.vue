<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span(style="color: #fff") 1
      h1 Formas primarias y composición dinámica
    .bloque-texto-a.color-acento-botones.p-4.mb-2(data-aos="fade-right")
      .bloque-texto-b__texto
        p.mb-0 En el diseño de videojuegos la estética juega un papel muy importante y se puede abordar desde las formas primarias principales: #[b círculo, cuadrado y triángulo], las cuales son el punto de partida de lo que se va a diseñar, que en un principio puede ser simple, pero al adicionarles detalles mejoran considerablemente.
    figure.mb-5(data-aos="fade-down")
      img(src='@/assets/curso/tema1/img01.png') 
    p.mb-5(data-aos="fade-left") Estas tres formas vistas bidimensionalmente se representan por líneas curvas, rectas y ángulos. De los círculos, los cuadrados y los triángulos nacen otras formas como los elementos en tres dimensiones: esferas, cubos y pirámides. A continuación, se podrá conocer cómo se utilizan las formas primarias en su composición dinámica.
    TabsA.color-acento-contenido.mb-5(data-aos="fade-right")
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Formas básicas")
        .row.align-items-center.justify-content-center.py-4
          .col-lg-4.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema1/img03.svg' style="width: 250px").m-auto
          .col-lg-6
            p.mb-0 Gracias a estas formas primarias y combinándolas entre sí, se pueden crear elementos con mayor complejidad.
          .col-lg-1
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Formas modificadas")
        .row.align-items-center.justify-content-center.py-4
          .col-lg-4.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema1/img04.svg' style="width: 250px").m-auto
          .col-lg-6
            p.mb-0 Estas formas se pueden deformar y ajustar su apariencia según el objetivo que se pretenda o lo que se quiera transmitir a través de su diseño.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Objetos")
        .row.align-items-center.justify-content-center.py-4
          .col-lg-4.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema1/img05.svg' style="width: 250px").m-auto
          .col-lg-6
            p.mb-0 Se puede observar cómo con objetos básicos se pueden diseñar elementos figurativos que representan objetos cotidianos, como una casa, un árbol, un oso. Estos apenas son unos ejemplos básicos, pero  a partir de elementos tan sencillos se pueden realizar incluso obras de arte, como las realizadas por Picasso.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Carros")
        .row.align-items-center.justify-content-center.py-4
          .col-lg-4.mb-4.mb-lg-0
            figure
              img(src='@/assets/curso/tema1/img06.svg' style="width: 250px").m-auto
          .col-lg-6
            p.mb-0 Se puede observar que con cuadrados, triángulos y círculos se puede armar un carro como si fuera un rompecabezas, posterior a ello se eliminan las líneas internas, integrando las formas básicas, lo que genera una figura de un carro, o también  un árbol complejo puede comenzar como una combinación de esferas y cilindros simples.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Cabeza")
        .row.align-items-center.justify-content-center.py-4
          .col-lg-4.d-flex.align-items-center
            figure
              img(src='@/assets/curso/tema1/img02.svg' style="width: 250px").m-auto
          .col-lg-6
            p Una cabeza humana a menudo se conceptualiza como una combinación de formas de esfera y cubo.
    .row(data-aos="fade-left")
      .col-lg-6.mb-4.mb-lg-0
        figure
          img(src='@/assets/curso/tema1/img07.png') 
      .col-lg-6.d-flex
        .cajon.color-acento-contenido.p-5
          p.mb-4 Las formas básicas permiten ser usadas como base para el modelado y escultura 3D de elementos básicos y complejos, los cuales se pueden combinar entre sí. La importancia de las formas primarias es que son la base para las figuras del diseño en 3D. 
          p Estas son usadas para el modelado y esculpido de los elementos 3D básicos y complejos, tales como: animales, plantas, figuras humanas, entornos, #[i props], entre otros, empezando por elegir las formas primarias que más se aproximan a la forma final a la cual se quiere llegar.
    Separador
    #t_1_1.titulo-segundo.color-acento-contenido
      h2 1.1  Formas primarias y temas emocionales
    p(data-aos="fade-right") Las figuras evocan emociones que se asocian de forma intrínseca con las vivencias de las personas, por ejemplo, un elemento redondo como un oso, va a evidenciar ternura; a diferencia de un demonio, que va a tener elementos afilados y puede transmitir terror. Es así, que de forma general a las figuras se les asocia emociones, pero estas también pueden variar de acuerdo con las formas que se empleen. 
    p.mb-5(data-aos="fade-right") De la siguiente manera se asocia las formas básicas a las emociones:                  
    figure.mb-5(data-aos="fade-down")
      img(src='@/assets/curso/tema1/img08.png', alt='Texto que describa la imagen')
    p(data-aos="fade-left") Estos temas emocionales se pueden multiplicar al generar combinaciones de los elementos básicos, lo que permite al equipo completo de videojuegos tomar decisiones durante la conceptualización de las ideas. En sí, se pueden observar elementos creados con figuras básicas, como el círculo, el cuadrado y el triángulo, dándole a cada personaje una identidad particular y reflejando una emoción de manera particular. 
    p.mb-5(data-aos="fade-left") En el siguiente ejemplo se dará a conocer qué emociones reflejan las figuras al dar clic sobre cada una de ellas:
    .row.justify-content-center(data-aos="fade-right")
      .col-12.col-lg-5.d-flex.flip-card.indicador__containe.mb-4.mb-lg-0
        div.indicador--click
        div.flip-card-inner
          div.p-3.p-md-4.p-lg-5.d-flex.flex-column.flip-card-front(style="background-color:#D8F3F9")
            .row
              .col-lg-2(style="border-bottom: 5px solid #8979F3")
            br              
            p Hay elementos creados con figuras básicas, como el círculo, el cuadrado y el triángulo, dándole a cada personaje  una identidad particular, los que reflejan una emoción particular. En este sentido, las emociones que despiertan estos 3 elementos permiten que se transmitan mensajes puntuales a partir de sus formas.
          div.flip-card-back
            figure
              img(src='@/assets/curso/tema1/img37.png' style="width: 350px")
      .col-12.col-lg-5.d-flex.flip-card.indicador__containe
        div.flip-card-inner
          div.p-3.p-md-4.p-lg-5.d-flex.flex-column.flip-card-front(style="background-color:#E1DDFC")
            .row
              .col-lg-2(style="border-bottom: 5px solid #05DBF3")
            br   
            p El uso principal del cuadrado se encuentra deformado y adaptado a cada una de las partes que conforman la estructura general del cuerpo. Este personaje Flynn,  demuestra una sensación de seriedad y fortaleza mental.
          div.flip-card-back
            figure
              img(src='@/assets/curso/tema1/img38.png' style="width: 350px")
    Separador
    #t_1_2.titulo-segundo.color-acento-contenido
      h2 1.2 Identidad en los personajes
    p.mb-4(data-aos="fade-right") La personalidad, características o estados emocionales de una persona suelen estar intrínsecamente relacionados con sus gestos y la posición de su cuerpo, por ejemplo, una persona corriendo en una maratón denotará cansancio en contraste con una que se encuentre sentada en un sillón viendo una película, implicando que se encuentra relajado; o un leñador indicará rudeza, mientras que un jugador de ajedrez se asocia con la inteligencia.
    p.mb-5(data-aos="fade-right") Lo mismo sucede en el mundo de los videojuegos, la caracterización y personalidad de un personaje depende en gran medida de la postura y gestos que se le asocian, a continuación, se podrá conocer las emociones, tamaño, equilibrio visual, diseño de grupo, formas del entorno, armonía y disonancia. 
    AcordionA(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")(data-aos="fade-left")
      .row(titulo="Emociones")   
        .col-lg-1
        .col-lg-10.px-4
          .row
            .col-lg-6.d-flex.py-5
              div.px-4(style="background-color:#DDDCE9")
                figure(style="position:relative; top:-30px")
                  img(src='@/assets/curso/tema1/img10.png')  
                p Kirby se puede asociar con una personalidad tierna, inocente, activa y positiva, es decir, con características relacionadas con los temas emocionales del círculo.
                p Referencia de la imágen: https://kirby.fandom.com /es/wiki/
            .col-lg-6.d-flex.py-5
              div.px-4(style="background-color:#DDDCE9")
                figure(style="position:relative; top:-30px")
                  img(src='@/assets/curso/tema1/img11.png')  
                p Dark Mind está claramente relacionado con temas emocionales del triángulo como la agresividad, fuerza, tensión e inestabilidad.
                p Referencia de la imágen: https://kirby.fandom.com /es/wiki/
          p Con el diseño de Kirby y Dark Mind se observa que las emociones relacionadas a cada espectro de forma son de gran utilidad a la hora de diseñar y perfilar las características de un personaje, ya sean positivas, negativas o incluso neutras, brindándole una identidad única que lo diferencia de los demás, marcando el concepto visual de un objeto que puede aplicarse a todos los elementos del videojuego para conservar un mismo estilo.       
        .col-lg-1
      .row(titulo="Tamaño")
        .col-lg-1
        .col-lg-10
          .row
            .col-lg-4.mb-4.mb-lg-0           
              figure
                img(src='@/assets/curso/tema1/img12.svg')                  
            .col-lg-8.px-4
              p El tamaño de los objetos es un elemento fundamental durante el proceso de diseño, tanto de personajes como del escenario. <br>Se puede observar cómo en la parte superior los personajes y los objetos son de tamaños similares, lo que no permite una jerarquización de los objetos compuestos. 
              p.mb-0 En la parte inferior se observa que con los mismos objetos diseñados se pueden organizar de mejor forma los objetos, generando una composición agradable visualmente.         
        .col-lg-1  
      .row(titulo="Equilibrio visual")
        .col-lg-1
        .col-lg-10.ps-0
          .row
            .col-lg-4.mb-4.mb-lg-0
              figure
                img(src='@/assets/curso/tema1/img13.svg')                  
            .col-lg-8.px-4
              p Las imágenes que se trabajan en conjunto, su unión fortalece una idea, una historia, en la que se encuentran narrativas visuales, por ello es importante mantener un equilibrio visual.
              p Los elementos en la imagen superior están sobrecargados hacia la derecha, por ello, la mirada es más atraída hacia ese punto. 
              p.mb-0 En la imagen inferior, los objetos están mejor distribuidos, como en una balanza, lo que hace que visualmente sean más agradables. 
        .col-lg-1  
      .row(titulo="Diseño de grupo")
        .col-lg-1
        .col-lg-5.mb-4.mb-lg-0
          figure
            img(src='@/assets/curso/tema1/img09.png') 
        .col-lg-5.px-4
          p Al igual que los personajes individuales, los grandes grupos suelen diseñarse de manera similar, compartiendo cualidades estéticas para conservar el mismo estilo. Esto se hace especialmente en los juegos de estrategia como por ejemplo, en el juego #[i Lords Mobile], donde se le permite al jugador adaptar su ejército consistente con personajes homogéneos, es decir, de la misma clase o tipo, en formaciones circulares enfocadas principalmente a la defensa desde todos los flancos; cuadrada que se presenta como una formación densa y rígida; y formaciones tipo flecha o cuña más agresivas, orientadas a romper las líneas del frente enemigo.
          p Referencia de la imágene: https://www.9apps.com/es/ android-games/Lords-Mobile/#gallery-1
        .col-lg-1
      .row(titulo="Conceptos de siluetas sencillas para personajes intrincados")
        .col-lg-1
        .col-lg-10
          p Los conceptos de forma también son particularmente esenciales en la creación de bocetos, que junto a los elementos de tamaño, forma y vestuario bien diseñados pueden formar una silueta bien definida que transmita a simple vista la esencia o personalidad que va a tener un personaje.
        .col-lg-1  
      .row(titulo="Formas del entorno")
        .col-lg-1
        .col-lg-10.px-4
          p Otro aspecto fundamental para la composición visual de un videojuego es el entorno, puesto que ocupa gran parte de la escena en donde se ejecutarán las acciones del personaje principal, mostrando también personajes secundarios que pueden ser hostiles, amistosos o neutrales; objetos ya sea que obstaculicen o contribuyan con el avance del jugador, y diferentes decoraciones como árboles, rocas, casas, nubes, animales, entre otros, que sirven para hacer más o menos llamativo el escenario, de acuerdo con el contexto en el que se desarrolle.
        .col-lg-1  
      .row(titulo="Armonía y disonancia")
        .col-lg-1
        .col-lg-10.px-4
          figure.pe-5.mb-4
            img(src='@/assets/curso/tema1/img14.png') 
          p Dada la intrínseca relación existente entre los personajes y el entorno donde se desenvuelven es necesario analizar dos elementos claves y determinantes en la composición visual de un videojuego: la armonía y la disonancia.
          p Dos tipos de personajes en entornos diferentes, un personaje y un entorno ligados a la misma forma, ya sea circular, cuadrada o triangular crearán una sensación de <b>armonía</b> para el jugador. Esto es debido a que en ambos entornos se mantiene el mismo estilo, por ejemplo, un personaje redondo en un sitio lleno de nubes y paisajes redondos estaría en un espacio armonioso. Por otra parte, si los personajes están ligados a una forma diferente de la de su entorno se produce una sensación de <b>disonancia</b>, debido a los diferentes temas emocionales de cada forma, es decir, un personaje de tipo triangular ligado a la agresión o poder,  no encajaría muy bien en un mundo con elementos suaves, alegres, optimistas o viceversa, un personaje de tipo circular ligado a temas positivos no se “sentiría cómodo” en un ambiente o entorno hostil y amenazante ligado al triángulo. 
        .col-lg-1
    Separador
    #t_1_3.titulo-segundo.color-acento-contenido
      h2 1.3 Anatomía básica
    p.mb-4(data-aos="fade-right") Conocer el sistema del cuerpo anatómico permite estructurar de una forma eficaz los personajes, por lo que es importante entender estos conceptos básicos para su realización.
    p.mb-5(data-aos="fade-right")  El cuerpo humano se divide en varias regiones que son la cabeza, el cuello, el tórax, miembros superiores, abdomen, pelvis y miembros inferiores. Estas son las regiones a tener en cuenta, pero para el dibujo básico se puede tener principalmente, la cabeza, el tórax y la cadera. A partir de ellos nacen los demás elementos que forman parte del cuerpo, a continuación, se podrá conocer la información referente a este proceso.
    SlyderB(:datos="datosSlyder")(data-aos="fade-left")
    Separador
    #t_1_4.titulo-segundo.color-acento-contenido
      h2 1.4 Diseño de personajes
    p(data-aos="fade-right") Se debe ayudar el trabajo del modelador, recreando poses de sus movimientos principales, para que a la hora de modelar y animar sea lo más cercano posible a como se tiene planeado. Puesto que es el personaje quien ayuda a desentrañar toda la historia y se debe dotar de las características coherentes para que se pueda desenvolver en todos los escenarios. Por ello, se hace necesario resaltar ciertas líneas de acción del personaje, líneas imaginarias que indican el movimiento del cuerpo de este, lo cual ayudará a transmitir las sensaciones y sentimientos del personaje en varias situaciones, tal como se muestra en la siguiente figura.
    .row.mb-5(data-aos="fade-down")
      .col-lg-1
      .col-lg-10.p-5(style="background-color:#D6F3F9")
        .titulo-sexto.color-acento-contenido
          p.mb-0 <b>Figura 1</b>
          p.mb-0 Personajes de acción
        figure
          img(src='@/assets/curso/tema1/img19.png')
          figcaption Tomado de: https://www.notodoanimacion.es/principios-del-diseno-de-personajes/
      .col-lg-1
    p.mb-5(data-aos="fade-right") Para trabajar el diseño de personajes, a continuación, se conocerá la línea de acción en un personaje llamado Flynn.
    .row.justify-content-center.mb-5(data-aos="fade-right")
      .col-lg-10.p-0
        figure
          .video          
            iframe(width="1280" height="722" src="https://www.youtube.com/embed/k80cALwOEYA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)         
    .row.justify-content-center.mb-5(data-aos="fade-left")
      .col-lg-6
        .cajon.color-acento-contenido.p-4
          p Conozca sobre los diseños de personajes, su referencia y documentación para que un personaje funcione correctamente en el contexto de una historia.
    h2(data-aos="fade-left") Diseño de personajes
    p.mb-4(data-aos="fade-right") Así como en las producciones en #[i live action] se acostumbra a realizar castings para seleccionar a los actores que mejor se adapten a los atributos físicos y psicológicos, desarrollados al momento de crear los personajes durante las etapas correspondientes al desarrollo de guion; en animación y videojuegos se lleva a cabo un proceso análogo denominado diseño de personajes, donde un equipo de artistas conceptuales se encargan de interpretar los personajes creados por los escritores para generar un casting que permita diseñar los atributos visuales que mejor se adapten a las características de cada uno.
    p(data-aos="fade-right") Para realizar este proceso con éxito existe una serie de conocimientos indispensables y aspectos a tener en cuenta, los cuales serán descritos a continuación:
    TabsC.color-acento-contenido.mb-5(data-aos="fade-down")
      .py-3.py-md-4(titulo="Referencias y documentación")
        p.mb-5 Para que un personaje funcione correctamente es indispensable tener en cuenta el contexto, la historia dentro de la cual se desarrolla y su propia historia individual que como ya se sabe, ha sido desarrollada desde la etapa del guion por parte de los escritores. Así como hacer un barrido sobre los orígenes del personaje, sus actitudes, aptitudes y motivaciones no solo los desarrollados en la etapa de escritura, sino los que puedan relacionarse con una época o un lugar específico. Por ejemplo, no es lo mismo diseñar un personaje que haya nacido en la década de 1950 en el continente latinoamericano, a uno que lo haya hecho en el siglo XXV en una colonia en Marte. Aunque en esta comparación en apariencia sea más fácil encontrar información sobre el primer caso, no quiere decir que para el segundo no sea relevante hacer una investigación sobre las condiciones conocidas del planeta y la misma historia y proyección de la raza humana, ya que esto permite obtener datos que brindan credibilidad al personaje.
        figure.mb-5
          img(src='@/assets/curso/tema1/img21.png') 
        p.mb-4  Por otro lado, la recolección de referencias visuales es una práctica indispensable al momento de diseñar, puesto que por mucha experiencia que se tenga, absolutamente nadie tiene almacenados en su cerebro todos los referentes que necesita. Por lo tanto, no está de más construir un banco visual que ayude a alimentar la creatividad y analizar el trabajo que realizaron otros artistas para tratar de entender de qué manera afrontan los retos presentados en sus respectivas producciones.
        p.mb-5 Una buena manera de gestionar las referencias es mediante PureRef, una aplicación gratuita que permite crear tableros y superponerlos a otras aplicaciones para tenerlos siempre a la vista y que puede ser descargada en el siguiente enlace:
        .row.mb-5
          .col-lg-3
          .col-lg-3
            a.anexo.mb-4.mb-lg-0(href="https://www.pureref.com/" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p <b>Enlace web.</b> PureRef 
          .col-lg-3
            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=Be_r_c1zt8w" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p <b>Enlace web.</b> PureRef - Introducción
          .col-lg-3
        .row.mb-5
          .col-lg-2
          .col-lg-8
            .tabla-b.color-acento-botones.mb-5                     
              table            
                tr.tabla-b__header
                  th Referente
                  th(colspan=2) Sitio web
                tr
                  td.text-center Carter Goodrich
                  td.text-center(colspan=2 nowrap) 
                    a(href="http://www.cartergoodrich.com" target="_blank") <u>www.cartergoodrich.com</u>
                tr
                  td.text-center Brett Bean
                  td.text-center(colspan=2 nowrap)
                    a(href="http://www.brettbean.com" target="_blank") <u>www.brettbean.com</u>
                tr
                  td.text-center Anette Marnat
                  td.text-center(colspan=2 nowrap) 
                    a(href="https://annettemarnat.ultra-book.com/portfolio" target="_blank") <u>www.annettemarnat.ultra-book.com/portfolio</u>
                tr
                  td.text-center Frank Frazetta
                  td.text-center(colspan=2 nowrap) 
                    a(href="http://www.frazettamuseum.com" target="_blank") <u>www.frazettamuseum.com</u>
                tr
                  td.text-center Creature Box
                  td.text-center(colspan=2 nowrap)
                    a(href="http://www.creaturebox.com" target="_blank") <u>www.creaturebox.com</u>
                tr
                  td.text-center Syd Mead
                  td.text-center(colspan=2 nowrap) 
                    a(href="http://www.sydmead.com" target="_blank") <u>www.sydmead.com</u>
                tr
                  td.text-center Phil Saunders
                  td.text-center(colspan=2 nowrap) 
                    a(href="http://www.artstation.com/philsaunders" target="_blank") <u>www.artstation.com/philsaunders</u>
                tr
                  td.text-center Shane Glines
                  td.text-center(colspan=2 nowrap) 
                    a(href="http://www.instagram.com/shaneglines" target="_blank") <u>www.instagram.com/shaneglines</u>            
          .col-lg-2
      .py-3.py-md-4(titulo="Anatomía básica")
        .row
          .col-lg-6            
            figure
              img(src='@/assets/curso/tema1/img20.png') 
          .col-lg-5
            p.mb-5 Según la RAE la anatomía es la ciencia que estudia la estructura y forma de los seres vivos y las relaciones entre las diversas partes que los constituyen. Aunque se trata de una ciencia derivada de la biología es muy útil en las artes plásticas y visuales pues uno de los conocimientos clave a la hora de diseñar personajes es la anatomía, independientemente de si se trata de un personaje de estilo realista o cartoon. Tener bases fuertes de anatomía ayuda a que la construcción física de los personajes sea creíble y por tanto, funcionen adecuadamente en el universo al que pertenecen.
            p Una buena forma de estudiar el funcionamiento del cuerpo es mediante los atlas médicos de anatomía, ya que presentan un desglose detallado que va desde la estructura ósea que soporta el cuerpo y muestra su relación con los músculos. No es necesario en principio memorizar el nombre de cada uno de los huesos y músculos que conforman el cuerpo, pero sí es sumamente importante saber dónde están ubicados, de dónde parten y a dónde llegan; debido que esto permite comprender su función en el movimiento y así mismo su importancia en la definición de siluetas y volúmenes del cuerpo.
          .col-lg-1
      .py-3.py-md-4(titulo="Proporciones del cuerpo humano")
        .row.mb-5
          .col-lg-6            
            figure
              img(src='@/assets/curso/tema1/img22.png') 
          .col-lg-5
            p.mb-4 Cada cuerpo posee características únicas que lo diferencian de los demás, sin embargo, desde la antigüedad han sido desarrollados diferentes sistemas de proporción para representar la figura humana de una manera armónica buscando unas proporciones ideales, los egipcios por ejemplo usaban la medida del puño como base para determinar las demás proporciones del cuerpo, determinando que la altura de este correspondía a 18 veces el tamaño del puño usando 2 para el rostro, diez en la distancia que va de los hombros a las rodillas y otros 6 para la distancia comprendida entre las rodillas y los pies.
            p El sistema más común es el que usa la dimensión de la cabeza como medida de referencia, con el cual muchos artistas han usado en sus obras proporciones basadas en sistemas de 7, 7 ½, 8, 8 1⁄2 y hasta 9 cabezas para determinar la estatura de la figura humana.
        p.mb-4  Estos sistemas de medida y proporción llevan por nombre canon (del griego Χανων, que significa regla). Uno de los cánones más conocidos es el del Hombre de Vitruvio, famoso dibujo de Leonardo da Vinci realizado alrededor de 1490 en el cual se representa una figura masculina inscrita al interior de un cuadrado y una circunferencia con 2 pares de brazos y piernas sobrepuestas, este estudio anatómico fue hecho a partir de textos arquitectónicos de Marco Vitruvio (de donde saca su nombre) y se rige bajo un sistema de proporciones de 8 cabezas.
        p Cabe resaltar que aunque se acepte el uso de un canon anatómico para la representación de las proporciones perfectas, esta es una idealización y las proporciones reales de cada persona varían en función de diversos factores como su origen étnico, genética heredada, condiciones de vida, etc. sin embargo, los cánones son útiles para construir estructuras anatómicas sólidas y su conocimiento nos permite tomar ciertas licencias para poder deformar las proporciones y así generar personajes con estilos más realistas o cartoon.
    h2(data-aos="fade-right") Personajes no jugadores NPC
    p.mb-4(data-aos="fade-right") En el diseño de personajes se encuentran los personajes no jugadores NPC, estos hacen referencia a los que habitan los escenarios del juego, pero el usuario no puede controlarlos, los cuales se pueden clasificar en: 
    .row.justify-content-center.mb-5(data-aos="fade-left")
      .col-10.col-lg-4.p-4
        div.px-4
          div.mb-4(style="background-color:#F2F0FD")
            figure(style="position:relative; top:-30px; width: 350px").m-auto
              img(src='@/assets/curso/tema1/img23.png')  
          h3 Aliados
          p Estos personajes tienen la función de ayudar al jugador o son a quienes hay que ayudar en el juego.
      .col-10.col-lg-4.p-4
        div.px-4
          div.mb-4(style="background-color:#F2F0FD")
            figure(style="position:relative; top:-30px; width: 350px").m-auto
              img(src='@/assets/curso/tema1/img24.png')  
          h3 Enemigos
          p Son los personajes que estarán interfiriendo en el avance del personaje, por lo que se encuentran dispersos en los escenarios. De estos se encuentran tres clases principales: enemigos comunes, enemigos de jerarquía media y enemigos jefes.
      .col-10.col-lg-4.p-4
        div.px-4
          div.mb-4(style="background-color:#F2F0FD")
            figure(style="position:relative; top:-30px; width: 350px").m-auto
              img(src='@/assets/curso/tema1/img25.png')  
          h3 Neutro
          p Son los personajes que pululan el mundo sin afectar al personaje de manera buena o mala.
    h2(data-aos="fade-right") Limitantes
    p.mb-5(data-aos="fade-down") En los videojuegos a diferencia de la animación 3D el renderizado es en tiempo real, por ende, se debe manejar una limitante en cuanto a polígonos y texturas para que todo fluya con movimientos mínimos de 24 cuadros por segundo. Todo esto depende de la plataforma en la cual se está pensado lanzar el juego, debido a las limitantes de cada hardware, pues consumirán recursos de la memoria del dispositivo, un ejemplo de ello son los celulares, que al ser de menor potencia, deben utilizar menor número de elementos en el juego. Dicho lo anterior, lo que se debe tener en cuenta a la hora de elegir la plataforma en la que se lanzará el juego es:
    .row.justify-content-center.mb-4(data-aos="fade-up")
      .col-10.col-md-4.col-lg-2.px-0(style="background-color:#F8F7FE")
        figure
          img(src='@/assets/curso/tema1/img26.svg' style="width: 350px").m-auto  
      .col-10.col-md-8.col-lg-8.d-flex.align-items-center.px-4.py-3(style="background-color:#F8F7FE")
        div
          h4 La cantidad de polígonos
          p Para dispositivos móviles la cantidad de polígonos debe oscilar entre 300 y 1.500 como máximo por malla, para consolas de antigua generación lo ideal es que oscilen entre 2.400 a 5.000 triángulos por malla, y para consolas de nueva generación y pcs #[i gamer] las mallas de personajes deberían tener 22.000 a 50.000 triángulos.
    .row.justify-content-center.mb-4(data-aos="fade-left")
      .col-10.col-md-4.col-lg-2.px-0(style="background-color:#F8F7FE")
        figure
          img(src='@/assets/curso/tema1/img27.svg' style="width: 350px").m-auto  
      .col-10.col-md-8.col-lg-8.d-flex.align-items-center.px-4.py-3(style="background-color:#F8F7FE")
        div
          h4 La cantidad de texturas y el tamaño de ellas 
          p Suelen usarse entre: 512, 1024, 2048, 4096 pixeles según sea el dispositivo al que van destinadas. No usar más de 3 materiales en una malla.
    .row.justify-content-center.mb-4(data-aos="fade-right")
      .col-10.col-md-4.col-lg-2.px-0(style="background-color:#F8F7FE")
        figure
          img(src='@/assets/curso/tema1/img28.svg' style="width: 350px").m-auto  
      .col-10.col-md-8.col-lg-8.d-flex.align-items-center.px-4.py-3(style="background-color:#F8F7FE")
        div
          h4 La cantidad de huesos en el modelo 
          p Debe ser la mínima posible en la malla, pues esto que ayudará al rendimiento del motor de videojuegos, el conteo sería entre 15 y 60 huesos para un rendimiento óptimo.
    .row.justify-content-center(data-aos="fade-left")
      .col-10.col-md-4.col-lg-2.px-0(style="background-color:#F8F7FE")
        figure
          img(src='@/assets/curso/tema1/img29.svg' style="width: 350px").m-auto  
      .col-10.col-md-8.col-lg-8.d-flex.align-items-center.px-4.py-3(style="background-color:#F8F7FE")
        div
          h4 La cantidad de animaciones
          p Para movimientos lo ideal es usar loops de animaciones, es decir, ciclos de repeticiones, por ejemplo, crear la animación de correr, caminar, entre otras, en ellas el primer cuadro de animación será el mismo que el último para poder así crear ese ciclo. También son necesarias las animaciones que conectan unas con otras, las cuales sirven para mostrar estados diferentes del personaje, como el saltar, el voltearse, el impulsarse, etc. 
    Separador
    #t_1_5.titulo-segundo.color-acento-contenido
      h2 1.5 Escenarios y <i>props</i>
    p(data-aos="fade-right") Los #[i props] son aquellos objetos y enseres que aparecen en un escenario a modo de #[i atrezzo]. A continuación, se hará una descripción sobre estos para ampliar cada uno de los conceptos.
    h2(data-aos="fade-right") <i>Props</i> en los videojuegos
    .row.mb-5(data-aos="fade-down")
      .col-lg-6
        p Todos los objetos utilizados por los personajes o NPC en un videojuego, exceptuando la vestimenta, son llamados #[i props], estos elementos son necesarios para el desarrollo de la historia. #[i Prop] (proveniente de la palabra propiedad, hace referencia a un objeto que se le asigna a alguien), los #[i props] hacen resaltar características de cada personaje, un ejemplo de ello sería la trampilla de los #[i Cazafantasmas], el neuralizador de #[i Hombres de Negro], la varita de #[i Harry Potter], el #[i hover board] de Marty McFly en #[i Volver al Futuro], entre otros.
        p El artista conceptual toma referencias para la creación del tipo de objeto que busca, dotándolo de características que lo relacionen con su propietario y el contexto en que se desarrolla la historia, así lo detalla desde todos los puntos de vista posible, para que el modelador tenga certeza y claridad de lo que va a modelar. A continuación, se relacionan algunos escenarios #[i props] para videojuegos. 
      .col-lg-6
        figure
          img(src='@/assets/curso/tema1/img30.png')
    .tarjeta.tarjeta--gris.p-2.p-lg-4.mb-5(data-aos="fade-left")
      LineaTiempoC.color-acento-contenido
        .row.justify-content-center(titulo="<em>Props</em> para juego medieval")
          .col-10
            figure
              img(src='@/assets/curso/tema1/img32.png')
              figcaption Referencia de la imágen: https://co.pinterest.com/ pin/331155378840196274/
        .row.justify-content-center(titulo="<em>Props The legend of Zelda</em>")
          .col-10
            figure.mb-3
              img(src='@/assets/curso/tema1/img31.png')
              figcaption Referencia de la imágen: https://co.pinterest.com/ pin/411375747217571766/
            p <b><i>Props</i> videojuego</b> <i>The legend of Zelda: breath of the wild.</i> 
        .row.justify-content-center(titulo="Flynn y la espada")
          .col-10
            figure.mb-3
              img(src='@/assets/curso/tema1/img33.png')     
            p Flynn se construyó a partir de geometrías básicas, 2 elementos #[i props] como ejemplo, en este caso son 2 de las armas del personaje Flynn, las cuales usará en la travesía para poder avanzar en su aventura.
    h2(data-aos="fade-right") Escenarios en los videojuegos
    .row(data-aos="fade-left")
      .col-lg-7.mb-4.mb-lg-0
        .cajon.color-secundario.p-4
          p Los escenarios en los videojuegos son los protagonistas en la ambientación de estos, dotándolos de un espacio y un tiempo particular, delimitando la interacción de los personajes, pudiendo así ser una parte que influya directamente en la jugabilidad, como ejemplo de ello es ver juegos como #[i Dragon Quest Builders] o el famoso #[i Minecraft] o simplemente ser un decorado donde los personajes desarrollan sus acciones y mecánicas.
      .col-lg-5
        p Los escenarios son los que generan los niveles del videojuego, por ende, tienen un proceso creativo en el que se realizan los bocetos, que luego pasan a perfeccionarse y a crearse visuales detalladas, que a su vez una vez listas pasan a modelarse y posteriormente a integrarse en el motor de videojuegos nivel a nivel. Es un trabajo denso, puesto que los escenarios se componen de muchos elementos, entre ellos se debe tener en cuenta el tipo de iluminación y perspectiva.
    p.mb-5(data-aos="fade-right") Los escenarios, por ende, abarcan todos los elementos visuales que contiene un nivel, a continuación, se podrá conocer algunos de estos escenarios.
    SlyderB(:datos="datosSlyder2")

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    datosSlyder2: [
      {
        titulo: 'Escenario <em>Super Mario 3D World</em>',
        imagen: require('@/assets/curso/tema1/img34.png'),
        leyendaImagen:
          'Referencia de la imágen: http://www.gamedynamo.es/article/ cheats/7091/3447/es/nintendo_wii _u/super_mario_3d_world',
      },
      {
        titulo: 'Puente de primer escenario',
        texto:
          'El puente se construyó a partir de geometrías básicas y llevará a Flynn al inicio de su aventura. Cabe resaltar que la figura se trabaja a partir de cubos rectangulares, pero que a su vez se deforma para dar un estilo visual artesanal.',
        imagen: require('@/assets/curso/tema1/img35.png'),
      },
      {
        titulo: 'Arte conceptual escenario <em>The last of us</em>',
        imagen: require('@/assets/curso/tema1/img36.png'),
        leyendaImagen:
          'Referencia de la imágen: https://www.borntoplay.es/en/ arte-conceptual-de-the-last-of-us/',
      },
    ],
    datosSlyder: [
      {
        titulo: 'Estructura del cuerpo humano',
        texto:
          'La estructura del cuerpo humano se puede diseñar con 8 o 8.5 cabezas, que se usan principalmente en los dibujos o cuerpos de personajes, principalmente de superhéroes, que permiten tener una altura imponente. De igual manera, están las cabezas de 7 o  7.5, estas generalmente se usan en cuerpo de estatura promedio y las 4 cabezas se usan en los <i>cartoon</i> animados, son cuerpos más bajos, pero si se desea se puede usar las que se necesiten para el personaje.',
        imagen: require('@/assets/curso/tema1/img16.png'),
        leyendaImagen: 'Ahriman 8 cabezas',
      },
      {
        titulo: 'Estructura alámbrica',
        texto:
          'La estructura alámbrica permite organizar de una forma simple el gesto del personaje que se quiere construir, por ello es dinámico.<br>En la figura se puede observar una estructura básica, elaborada en 4 cabezas de medida, en una posición frontal y de descanso, la estructura metálica maneja cabeza, tórax y cadera, de donde desprenden los demás elementos, a su derecha se observa cómo esa estructura metálica es recubierta con la forma del cuerpo, pero siempre siguiendo la forma base.',
        imagen: require('@/assets/curso/tema1/img17.png'),
      },
      {
        titulo: 'Niño figura alámbrica',
        texto:
          'La figura tiene el uso de la estructura alámbrica en una vista de ¾, luego esta es cubierta por los detalles y finalmente, se elimina para dejar como boceto el personaje, que posteriormente se debe pulir.',
        imagen: require('@/assets/curso/tema1/img15.png'),
      },
      {
        titulo: 'Dibujo gestual',
        texto:
          'Una estructura alámbrica dinámica permite crear una gestualidad en los personajes, hay un ritmo y un movimiento en ellos, dejando de lado las figuras estáticas.',
        imagen: require('@/assets/curso/tema1/img18.png'),
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
