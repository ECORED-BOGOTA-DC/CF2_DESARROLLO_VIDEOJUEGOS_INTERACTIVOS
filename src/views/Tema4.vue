<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span(style="color: #fff") 4
      h1 Conceptos de 3D y modelado
    p.mb-5(data-aos="fade-right") El modelado 3D consiste en representar cualquier elemento de manera tridimensional en un #[i software] de computador, basándose en la interrelación de 3 ejes, los cuales se denominan eje X, eje Y, eje Z.
    figure.mb-5(data-aos="fade-right")
      img(src='@/assets/curso/tema4/img01.png', alt='Texto que describa la imagen') 
    .row.mb-5(data-aos="fade-left")
      .col-lg-3
      .col-lg-6
        .cajon.color-secundario.p-5
          p.mb-0 El #[i software] que utilizaremos de ahora en adelante será Blender, ver video de instalación del #[i software].
      .col-lg-3
    .row.justify-content-center.mb-5(data-aos="fade-left")
      .col-lg-10
        figure
          .video          
            iframe(width="1280" height="722" src="https://www.youtube.com/embed/gzBXxQToqEg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)         
    p.mb-5(data-aos="fade-right") Para el modelado 3D en cada #[i software], lo primero que se tiene que entender es la escena, la cual es el espacio en que se va a contener y a ordenar todos los elementos tridimensionales. Para ello, el sistema de coordenadas se hace indispensable para poder navegar en la escena, los cuales como se menciona antes, van a proporcionar información de la dirección en que se navegará teniendo en cuenta lo siguiente:
    .row.justify-content-center.mb-4(data-aos="fade-left")
      .col-10.col-md-8.col-lg.m-2
        .row
          .col-12.p-4(style="background-color:#F2F0FD")
            figure.mb-5
              img(src='@/assets/curso/tema4/img02.svg', alt='Texto que describa la imagen') 
            h4 Eje X
            p.mb-0 Brindará información necesaria sobre el ancho o diciéndolo de otra manera, de la vista de usuario de lado a lado.
      .col-10.col-md-8.col-lg.m-2
        .row.h-100
          .col-12.p-4(style="background-color:#F2F0FD")
            figure.mb-5
              img(src='@/assets/curso/tema4/img03.svg', alt='Texto que describa la imagen') 
            h4 Eje Y
            p.mb-0 Brindará información de la altura, es decir, de abajo a arriba. 
      .col-10.col-md-8.col-lg.m-2
        .row.h-100
          .col-12.p-4(style="background-color:#F2F0FD")
            figure.mb-5
              img(src='@/assets/curso/tema4/img04.svg', alt='Texto que describa la imagen') 
            h4 Eje Z
            p.mb-0 Brindará información de profundidad, es decir, la distancia entre el usuario y los objetos a lo lejos.
    p.mb-5(data-aos="fade-right") A continuación, se podrá conocer sobre los conceptos de 3D y modelado a partir ejemplos del sistema de coordenadas en los ejes.
    .row.justify-content-center.mb-4(data-aos="fade-left")
      .col-lg-10
        .row.justify-content-center.mb-5.py-5(style="background-color:#F9F9F9") 
          .col-lg-10
            p.mb-4 Para hacer representaciones se debe tener en cuenta varios aspectos como lo son los vértices (#[i vertex]), arista o bordes (#[i edges]), y caras (#[i faces]).
            h4 Vértices
            p.mb-4 Es el punto en el cual se puede definir el comienzo y el final de un segmento, es el punto primario de un modelo 3D. Al conectar 2 vértices se crea una línea, y al conectar más puntos se crean los polígonos. Estos puntos son los que finalmente acogen la información de texturas uv como a su vez, la información de peso influido por el sistema de huesos.
            h4 Arista o bordes
            p.mb-4 Son las líneas que conectan los puntos del polígono, por ende, las aristas, son las que afectan visualmente la definición de los bordes del polígono, dándoles dureza o suavidad.
            h4 Cara
            p.mb-4Son las superficies resultantes de la unión de como mínimo 3 vértices y aristas, se podrían denominar en los que se componen de 3 puntos, que son polígonos de forma triangular, que se usan en videojuegos, para hacer referencia a los polígonos de 4 puntos, usados en animación 3D, y los de 5 o más puntos llamados #[i n-gon].
    figure.mb-3(data-aos="fade-right")
      img(src='@/assets/curso/tema4/img34.svg', alt='Texto que describa la imagen')
    .row.justify-content-center.mb-5(data-aos="fade-right")
      .col-lg-10 
        p.ps-0 Representación de elementos de modelado 3D.
    TabsA.color-acento-contenido(data-aos="fade-left")
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Personajes")     
        .row.justify-content-center
          .col-8.col-lg-5
            ImagenInfografica.color-secundario.mb-5
              template(v-slot:imagen)                    
                figure
                  img(src='@/assets/curso/tema4/img06.svg', alt='Texto que describa la imagen')
              div(x="27%" y="27%").bg-c3
                p.text-center.mb-0 #[b Seleccionar/]
                p.text-center.mb-0 #[b Deseleccionar]
              div(x="55%" y="27%").bg-c4
                p.text-center.mb-0 #[b Menú contextual ]
                p.text-center.mb-0.txt-c1 Posiciona cursor 3D
              div(x="68%" y="80%").bg-c5
                p.text-center.mb-0 #[b Zoom cámara ]
                p.text-center.mb-0.txt-c1 Paneo cámara
                p.text-center.mb-0.txt-c2 Cambiar vistas #[i (superior/lateral/frontal)]
          .col-lg-5.d-flex.align-items-center
            p Para el modelado se emplean varias técnicas, en este caso se mencionarán las que pueden utilizarse en el #[i software] Blender. Para ello, se debe tener en cuenta la navegación en el #[i software] y el conocer ciertas acciones que se harán con el mouse en combinación con las teclas.
      .tarjeta.color-acento-contenido--borde.p-4(titulo="<em>Box modeling</em>")
        p.mb-4 Es la técnica más utilizada, se parte de una primitiva o malla preestablecida, como podría ser una esfera, un plano, un cubo, un cono, etc.  Las cuales vienen integradas en Blender, para lo cual una vez teniéndolas en el escenario se le agregaran polígonos, extruyendo, biselando, escalando caras, vértices y bordes.
        figure
            img(src='@/assets/curso/tema4/img05.png', alt='Texto que describa la imagen') 
      .tarjeta.color-acento-contenido--borde.p-4(titulo="<em>Sculpting</em>")
        p.mb-5 En este tipo de modelado se parte de un elemento del propio #[i software], y en este caso el modelado se desarrolla como un esculpido en la vida real con masilla, es decir, aplicando presión, puliendo, cortando, suavizando. Con él se pueden conseguir resultados visuales muy detallados, los cuales funcionan para mostrar un tipo de estilo, pero no para animar, puesto que la cantidad de polígonos es demasiada para que cualquier hardware la soporte. 
        figure
          img(src='@/assets/curso/tema4/img06.png', alt='Texto que describa la imagen')
      .tarjeta.color-acento-contenido--borde.p-4(titulo="<em>Nurbs</em>")
        p.mb-5 Partiendo de líneas se pueden generar superficies que den un aspecto muy orgánico, como por ejemplo, terrenos irregulares de la naturaleza. Luego, esa curva se puede convertir en malla.
        .row.justify-content-center
          .col-lg-8
            figure.mb-4
              img(src='@/assets/curso/tema4/img07.png', alt='Texto que describa la imagen')
            figure.mb-4
              img(src='@/assets/curso/tema4/img08.png', alt='Texto que describa la imagen')
            figure
              img(src='@/assets/curso/tema4/img09.png', alt='Texto que describa la imagen')
    Separador 
    #t_4_1.titulo-segundo.color-acento-contenido
      h2 4.1 Personajes
    p.mb-5(data-aos="fade-right") Para la creación de personajes se utilizarán las herramientas de modificación con las que Blender dispone para elaborar en el modo de edición, entre ellas se tienen tres principales modos, vértice (#[i vertex]), borde (#[i edge]) y cara (#[i face]) con las cuales se puede modificar la malla, moviéndola, escalándola y rotándola, pero además de ello modificar la malla, precisamente el siguiente recurso permitirá conocer estas disposiciones. 
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")(data-aos="fade-down")
      div(titulo="Extruir")  
        .row.justify-content-center.mb-4
          .col-lg-11
            p <b>Extruir (tecla e):</b> la extrusión, genera polígonos a partir de los vértices, bordes o caras, desplazándolos en cualquiera de los ejes, es el modo que se usa con más frecuencia.
            figure.mb-4
              img(src='@/assets/curso/tema4/img11.png', alt='Texto que describa la imagen')
            p Ejemplo de modelado herramienta Extruir
          div(titulo="Insertar caras")  
        .row.justify-content-center
          .col-lg-11
            p <b>Insertar caras (tecla Shift + barra espaciadora + i):</b> como su nombre lo indica, este modificador inserta una cara dentro de otra, generando así una subdivisión.
            figure.mb-4
              img(src='@/assets/curso/tema4/img12.png', alt='Texto que describa la imagen')
            p Ejemplo de modelado herramienta Insertar caras
      div(titulo="Biselado")  
        .row.justify-content-center
          .col-lg-11
            p <b>Biselado (tecla ctrl + B):</b> la herramienta permite insertar bordes, cortados oblicuamente, se puede agregar en la ventana de sus modificadores opciones como el número de segmentos por agregar. 
            figure.mb-4
              img(src='@/assets/curso/tema4/img13.png', alt='Texto que describa la imagen')
            p Ejemplo de modelado herramienta Biselado
      div(titulo="Loop Cut") 
        .row.justify-content-center
          .col-lg-11           
            p <b>Loop Cut (tecla ctrl + r):</b> corta la malla alrededor, siguiendo un trayecto hasta cerrarse. 
            figure.mb-4
              img(src='@/assets/curso/tema4/img10.png', alt='Texto que describa la imagen')
            p Ejemplo de modelado herramienta Loop Cut
      div(titulo="Knife")  
        .row.justify-content-center
          .col-lg-11
            p <b>Knife (tecla shift + barra espaciadora + K):</b> corta generando una nueva topología.
            figure.mb-4
              img(src='@/assets/curso/tema4/img14.png', alt='Texto que describa la imagen')
            p Ejemplo de modelado herramienta Knife
      div(titulo="Spin")  
        .row.justify-content-center
          .col-lg-11
            p <b>Spin (tecla shift + barra espaciadora + 0):</b> genera extrusión, en circunferencia según el #[i viewport].
            figure.mb-4
              img(src='@/assets/curso/tema4/img15.png', alt='Texto que describa la imagen')
            p Ejemplo de modelado herramienta Spin
      div(titulo="Rip Region")  
        .row.justify-content-center
          .col-lg-11
            p <b>Rip Region (tecla shift + barra espaciadora + v):</b> despega vértices o bordes de la malla.
            figure.mb-4
              img(src='@/assets/curso/tema4/img16.png', alt='Texto que describa la imagen')
            p Ejemplo de modelado Rip Region
      div(titulo="Fill")  
        .row.justify-content-center
          .col-lg-11
            p <b>Fill (tecla F):</b> para rellenar espacios vacíos, se selecciona 3 vértices o bordes y se presiona la tecla F, con lo cual generará un polígono conectando dichos puntos.
            figure.mb-4
              img(src='@/assets/curso/tema4/img17.png', alt='Texto que describa la imagen')
            p Ejemplo de modelado Fill
    p.mb-5(data-aos="fade-right") Combinando estos modificadores se puede realizar el modelado del personaje.
    .row.mb-5(data-aos="fade-left")
      .col-lg-4
        figure.mb-4
          img(src='@/assets/curso/tema4/img18.png', alt='Texto que describa la imagen')
      .col-lg-4
        figure.mb-4
          img(src='@/assets/curso/tema4/img19.png', alt='Texto que describa la imagen')
      .col-lg-4
        figure.mb-4
          img(src='@/assets/curso/tema4/img20.png', alt='Texto que describa la imagen')
    .row.justify-content-center.mb-5(data-aos="fade-right")
      .col-lg-6
        .cajon.color-acento-contenido.p-4
          p.mb-0 Para empezar a modelar, partimos de sacar las vistas 2D y llevarlas al programa 3D, veamos el video de cómo hacerlo. A continuación veremos cómo se crea el personaje Flynn en los siguientes videos.
    .row.justify-content-center(data-aos="fade-left")
      .col-lg-10
        figure
          .video          
            iframe(width="1280" height="722" src="https://www.youtube.com/embed/966QR6R6jQk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    Separador
    #t_4_2.titulo-segundo.color-acento-contenido
      h2 4.2 Escenarios y props
    p.mb-5(data-aos="fade-right") Las técnicas para crear escenarios son las mismas, salvo que en algunas ocasiones se utilizará un par de herramientas para crear más rápido terrenos o duplicar elementos en cantidad. Se utilizarán los modificadores anteriormente mencionados para generar geometrías y así crear un puente, en el cual se empleará un nuevo modificador que servirá básicamente para agilizar trabajo a la hora de crear elementos arquitectónicos o elementos modulares, es decir, que se repiten cíclicamente. Para ello, se debe crear un cubo y se aplicará biselado en sus bordes para darle suavizado, agregando dos segmentos en las características de biselado, tal como se puede observar en el siguiente recurso. 
    .row.justify-content-center.mb-3(data-aos="fade-down")
      .col-lg-10
        SlyderC(:datos="datosSlyder")
    .row.justify-content-center.mb-5(data-aos="fade-right")
      .col-lg-10
        p.mb-4 Con estas herramientas y estos pasos además del puente se puede crear infinidad de elementos en Blender, por ejemplo, árboles estilo #[i lowpoly], en este caso se usan 3 conos y un cilindro bajando sus segmentos a 8 y, para que queden unidos se debe seleccionar Control + J para unirlos y luego se agrega array para crear un bosque rápido, en este caso se duplica el árbol un par de veces para posicionarse aleatoriamente.
        figure
          img(src='@/assets/curso/tema4/img27.png', alt='Texto que describa la imagen')
    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10
        SlyderC(:datos="datosSlyder2")
    .row.justify-content-center.mb-5(data-aos="fade-right")
      .col-lg-6
        .cajon.color-secundario.p-4
          p.mb-0 Ver el video de la creación del puente en el #[i software] Blender.
    .row.justify-content-center(data-aos="fade-left")
      .col-lg-10
        figure
          .video               
            iframe(width="1280" height="722" src="https://www.youtube.com/embed/BEiWXK1DxRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    datosSlyder: [
      {
        titulo: 'Ejemplo de modelado de puente',
        texto:
          'Se duplica con shift + D 4 veces para generar la base del puente.',
        imagen: require('@/assets/curso/tema4/img21.png'),
      },
      {
        titulo: 'Ejemplo de modelado de puente',
        texto:
          'Se duplica con shift + D 4 veces para generar la base del puente.',
        imagen: require('@/assets/curso/tema4/img22.png'),
      },
      {
        titulo: 'Ejemplo de modelado de puente',
        texto:
          'Como siguiente paso se crearán los tablones del puente, para ello se crea agregando un cubo a la escena, modificando solo el borde frontal para darle un efecto  rústico con biselado, ahora se aplicará el modificador <em>array</em>, que permitirá crear copias simultáneas una seguida de otra, para ello, lo primero que se debe realizar es la separación del tablón de las demás geometrías, por tanto, se selecciona el tablón completo y se presiona la tecla P, con ello saldrá una pestaña que dará la opción de separar, así, el objeto quedará separado de los demás y se podrá agregar el modificador <em>array</em>.',
        imagen: require('@/assets/curso/tema4/img23.png'),
      },
      {
        titulo: 'Ejemplo de modelado de puente',
        texto:
          'Aplicado el modificador se observa cómo se duplica el elemento, para asignarle el número de veces que se requiere duplicar el eje.',
        imagen: require('@/assets/curso/tema4/img24.png'),
      },
      {
        titulo: 'Ejemplo de modelado de puente',
        texto:
          'Se selecciona las escalerillas y se reflejan con la combinación de teclas cntrl + m, Blender posteriormente preguntará en qué eje, y se oprime X para ver reflejado en el otro eje el elemento.',
        imagen: require('@/assets/curso/tema4/img25.png'),
      },
      {
        titulo: 'Ejemplo de modelado de puente',
        texto:
          'Se selecciona las escalerillas y se reflejan con la combinación de teclas cntrl + m, Blender posteriormente preguntará en qué eje, y se oprime X para ver reflejado en el otro eje el elemento.',
        imagen: require('@/assets/curso/tema4/img26.png'),
      },
    ],
    datosSlyder2: [
      {
        titulo: 'Edificaciones',
        texto:
          'Como también se puede jugar con <em>Loop Cut</em> para crear edificios rápidos, y luego agregarles <em>Array</em> para generar una manzana de edificaciones.',
        imagen: require('@/assets/curso/tema4/img28.png'),
      },
      {
        titulo: 'Edificaciones',
        texto:
          'Como también se puede jugar con <em>loop cut</em> para crear edificios rápidos, y luego agregarles array para generar una manzana de edificaciones.',
        imagen: require('@/assets/curso/tema4/img29.png'),
      },
      {
        titulo: 'Edificaciones',
        texto:
          'Se realiza los cortes y luego se bisela para generar las ventanas.',
        imagen: require('@/assets/curso/tema4/img30.png'),
      },
      {
        titulo: 'Edificaciones',
        texto:
          'Se selecciona las caras de la ventana y se mueven hacia adentro con la tecla G, adicionalmente para dar un poco de suavizado se seleccionan todos los bordes externos y se le aplica biselado.',
        imagen: require('@/assets/curso/tema4/img31.png'),
      },
      {
        titulo: 'Edificaciones',
        texto: 'Se duplica el edificio para hacer unas ligeras modificaciones.',
        imagen: require('@/assets/curso/tema4/img32.png'),
      },
      {
        titulo: 'Edificaciones',
        texto:
          'Se selecciona las teclas control + J para unirlos y agregar el modificador array, con esto se genera una sucesión de dichos edificios.',
        imagen: require('@/assets/curso/tema4/img33.png'),
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
