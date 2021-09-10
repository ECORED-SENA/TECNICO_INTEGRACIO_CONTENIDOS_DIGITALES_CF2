<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal
      .titulo-principal__numero
        span 2
      h1 Creación <i>web</i>

    figure.mb-5(data-aos="fade")
      img(src="@/assets/curso/tema2-banner.png", alt="Creación web") 

    p La creación o desarrollo de sitios <i>web</i> trascienden el concepto de diseño <i>web</i> y sitúa la labor en aspectos más de tipo técnico, que de manera transversal, se fusionan para generar un producto único que cumpla con unas características definidas, entre ellas, ser agradable a la vista (buen diseño) y ser lo más funcional posible (navegabilidad). También se incluyen aspectos implícitos funcionales como los que define la arquitectura <i>web</i>.   

    .row
      .col-md-7.mb-4
        p Pero conseguir un diseño óptimo no solo incluye la integración de contenido visual o conceptos de UX, sino que tiene que ver también con los objetivos planteados por el cliente previamente y la alineación con la estrategia global de la empresa. Igualmente, el uso de herramientas como Google analytics guiarán la toma de decisiones sobre un sitio <i>web</i> para conseguir los resultados esperados.
        p Finalmente, la construcción de páginas <i>web</i> incluye la producción de contenido que cada día toma más relevancia, al ser esta la herramienta más eficaz para fidelizar nuevos usuarios.
      .col-md-5.mb-4
        img(src="@/assets/curso/tema2-img1.jpg", alt="Imagen decorativa") 

    Separador


    // 2.1
    #t_2_1.titulo-segundo(data-aos="fade-right")
      .h2 2.1  Diseño <i>web</i>

    .row.justify-content-center
      .col-md-10
        .bloque-texto-a.color-azul.p-4.p-md-5.mb-5 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-8.mb-4.mb-lg-0
              .bloque-texto-a__texto.p-4
                p.mb-4 Desde el punto de vista técnico el diseño <i>web</i> se refiere al uso de los códigos HTML y XML. Según la W3C (World Wide <i>web</i> Consortium) y desde el punto de vista estructural, el diseñador <i>web</i> crea las páginas utilizando lenguajes de marcado como HTML o XML. En la parte visual de los sitios, el CSS es utilizado para estilizar los elementos escritos en HTML y configurar el layout.
                p Para desarrollar páginas <i>web</i> es necesario seguir un proceso que tiene diferentes etapas, que, si se desarrollan adecuadamente, garantizan el éxito del resultado final. Este proceso está compuesto por las siguientes fases:
            .col-lg-4
              img(src="@/assets/curso/tema2-1-img1.svg", alt="Diseño web")

    .row.align-items-center.mb-4
      .col-md-7.mb-4
        LineaTiempoD.color-acento-botones.color-amarillo 
          p.text-small(numero="1" titulo="Contacto inicial") Incluye la reunión inicial, la definición de objetivos, realización del <i>briefing</i>, definición del alcance y <i>benchmarking</i>.
          p.text-small(numero="2" titulo="Planificación") Construcción del mapa de navegación, elaboración del <i>wireframe</i> y definición de UX.
          p.text-small(numero="3" titulo="Concepto") Elaboración del esquema de contenidos.
          p.text-small(numero="4" titulo="Diseño") Inclusión de elementos visuales y realización de <i>mockups</i>.
          p.text-small(numero="5" titulo="Desarrollo") Definición del CMS, lenguajes de programación, maquetación de <i>wireframes</i>, velocidad, compatibilidad con dispositivos móviles, pruebas, Google Analytics y searc console.
          p.text-small(numero="6" titulo="Lanzamiento") Refinamiento e indexación en los motores de búsqueda.
      .col-md-4.mb-4
        img.p-md-5(src="@/assets/curso/tema2-1-img2.svg", alt="Imagen decorativa")

    p.mb-4 En la siguiente figura se puede observar en detalle cual es el proceso global, las etapas y las áreas a las que pertenecen.

    .row.justify-content-center(data-aos="fade-down")
      .col-lg-10    
        .tarjeta.color-azul-fuerte.p-3.px-lg-5
          .row.justify-content-around.align-items-center
            .col-4.col-sm-3.col-lg-2.px-lg-4
              img(src="@/assets/curso/tema2-1-cta.svg")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h4 “Diseño <i>web</i>: fases y etapas para su desarrollo”
                  p.text-small.mb-1 Estimado aprendiz, para profundizar sobre el tema puede consultar la siguiente página:
                .col-sm-auto
                  a.boton.color-acento-botones(:href="('https://www.google.com/url?q=https://www.marketerosagencia.com/diseno-web/fases-etapas-diseno-web/&sa=D&source=editors&ust=1631226360938000&usg=AOvVaw2q0ud8VFMil7qcaVVSm0mv')" target="_blank")
                    span Enlace web
                    i.fas.fa-link    

    Separador


    // 2.2
    #t_2_2.titulo-segundo(data-aos="fade-right")
      .h2 2.2  Arquitectura y diagramación <i>web</i>

    .row.mb-5.alto-igual
      .col-md-4.m-0.p-0
        img(src="@/assets/curso/tema2-2-img1.jpg", alt="Imagen decorativa")
      .col-md-8.borde.m-0.py-5
        p El diseño y la arquitectura de información de las páginas web son “el resultado de la actividad de clasificar, describir, estructurar y etiquetar los contenidos del sitio”. 
          strong (Leyva, Alarcón, Barrera & Ortegón, 2017)
        p Es así como la arquitectura <i>web</i> incluye pensar en sí el resultado final será un sitio que pueda resolver las necesidades de negocios y servir mejor a las necesidades de los clientes. El arquitecto <i>web</i> diseña y coordina el desarrollo de sitios <i>web</i>, ya que estos son una compleja integración de distintos sistemas (bases de datos, servidores, redes, componentes de <i>backup</i> y seguridad, etc.)
          br
          br 
          | Las piezas esenciales de la arquitectura <i>web</i> son principalmente: servidores, bases de datos, redes, HTML, componentes de <i>backup</i> y seguridad, inteligencia de contenidos <i>web</i>, organización de componentes y organización de las llamadas a las páginas o <i>interlinking</i>.  

    p.mb-4 Por su parte la diagramación es la representación de la arquitectura de los contenidos que tendrá un producto digital y las relaciones entre dichos contenidos. La representación se ha usado desde los comienzos del diseño de <i>software</i>, en forma de organigramas, diagramas de flujo de datos, árboles de decisión, etc. 

    img.mb-5(src="@/assets/curso/tema2-2-img2.jpg", alt="Imagen decorativa")

    .row.align-items-center.mb-5
      .col-md-4.mb-4.position-relative
        img.px-lg-5.imagen_flotante_1.d-none.d-lg-block.d-md-block(src="@/assets/curso/tema2-2-img3.svg", alt="Imagen decorativa") 
      .col-md-8
        p Al evolucionar las interfaces gráficas de usuario, las labores de representación se ampliaron con los llamados guiones de navegación y guiones de interacción, los cuales consistían en diagramas que representan el funcionamiento de los productos electrónicos que se generaban en ese momento. 
        p Hay que señalar que durante el proceso de arquitectura de Información se usan otras formas de representación, con diferentes objetivos. Por ejemplo, en la aplicación de la técnica de <i>Card Sorting</i> se pueden generar dendrogramas y gráficos de escalamiento multidimensional; otro ejemplo serían las representaciones de las estructuras mentales de los usuarios tras una tormenta de ideas (<i>brainstorming</i>); o los organigramas de la empresa por la cual se crea el producto digital. En la siguiente figura se puede ver representado el proceso:

    .row.justify-content-center
      .col-lg-10.mb-5    
        h5 Figura 1
        p Esquema de la Arquitectura de la información <i>web</i>
        img(src="@/assets/curso/tema2-2-infografia.svg", alt="Esquema de la Arquitectura de la información web") 

    p Los autores angloparlantes, pioneros en los temas del diseño y representación del <i>software</i>, dividen estos diagramas en 2 tipos: Blueprints y <i>wireframes</i>. (Morville & Rosenfeld, 1998) Como sustituto del término Blueprint a veces se usa el de Architecture Map, que significa Mapa de Arquitectura.

    p.mb-4 Ahora profundizaremos sobre las diferentes formas de representar la arquitectura de información y su respectiva diagramación:

    .row.justify-content-center.mb-5
      .col-md-10.borde2
        .row.p-4
          .col
            h4 Blueprints
            p Es un tipo de diagrama que representa las principales áreas de organización y rotulado (Rosenfeld & Morville, 1998), están enfocados a los aspectos estructurales y de funcionamiento del producto. Generalmente se representan con textos, cajas y flechas. Estos planos o blueprints parten de lo general a lo particular, de lo abstracto a lo concreto. Su función es explicitar iterativamente las decisiones de diseño, con el objetivo de comunicar dichas decisiones al resto de miembros del equipo de desarrollo, o al cliente final.
            p Christina Wodtke conceptualiza los #[i Blueprint] como: #[i un plano de diseño es justamente una buena idea llevada a la realidad a través de la escritura] (Wodtke, 2002)    

    .bloque-texto-g.azul2.p-3.p-sm-4.p-md-5.mb-5
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2-2-img4.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4
        h4.mb-4 Maquetas
          br
          br
        p Es un tipo de diagrama que representa las principales áreas de organización y rotulado (Rosenfeld & Morville, 1998), están enfocados a los aspectos estructurales y de funcionamiento del producto. Generalmente se representan con textos, cajas y flechas. Estos planos o blueprints parten de lo general a lo particular, de lo abstracto a lo concreto. Su función es explicitar iterativamente las decisiones de diseño, con el objetivo de comunicar dichas decisiones al resto de miembros del equipo de desarrollo, o al cliente final.
          br
          br
        p Christina Wodtke conceptualiza los Blueprint como: un plano de diseño es justamente una buena idea llevada a la realidad a través de la escritura (Wodtke, 2002)


    p.mb-4 Los niveles de prototipos son:

    AcordeonB(tipo="b" clase-tarjeta="tarjeta--blanco border-bottom acordeon-tema2-2")
      .row.px-lg-5(titulo="Prototipos de baja fidelidad o estáticos")
        .row
          .col-md-4    
            img(src="@/assets/curso/tema2-2acordeon1.jpg", alt="Prototipos de baja fidelidad o estáticos")
          .col-md-8
            h4.mb-0 El <i>wireframe</i> 
            p De un sitio <i>web</i> es un boceto rápido que puede elaborarse con lápiz y papel y que representa, por medio de recuadros, líneas, trazos, el esquema del contenido, de la interfaz, sistema de navegación y funcionamiento de la página <i>web</i> que se va a diseñar.
            h4.mb-0 Mockup 
            p en el proceso del diseño <i>web</i> el paso posterior al <i>wireframe</i> es el mockup, que permite tener una idea más clara de cómo se verá el sitio <i>web</i>. Este paso es más visual y se tienen en cuenta las dimensiones, la organización de los elementos, el texto, las imágenes, iconos, logos, etc.  
      .row.px-lg-5(titulo="Prototipos de fidelidad intermedia")
        .row
          .col-md-4    
            img(src="@/assets/curso/tema2-2acordeon2.jpg", alt="Prototipos de fidelidad intermedia")
          .col-md-8
            p Se trataría de todo el diseño gráfico, visual y llamativo que se incorporará en la <i>web</i>.
      .row.px-lg-5(titulo="Prototipos de alta fidelidad o dinámicos ")
        .row
          .col-md-4    
            img(src="@/assets/curso/tema2-2acordeon3.jpg", alt="Prototipos de alta fidelidad o dinámicos ")
          .col-md-8
            ul.lista-ul
              li 
                i.fas.fa-angle-right
                | Es la página <i>web</i> en sí misma en formato HTML.
              li 
                i.fas.fa-angle-right
                | En la siguiente figura se presentan ejemplos de maquetas.  

    Separador


    .row.justify-content-center.mb-5
      .col-md-10.borde2
        .row.p-4
          .col-md-4    
            img(src="@/assets/curso/tema2-2-img5.jpg", alt="Frameworks")
          .col-md-8
            h4 Frameworks
            p Un framework es una estructura base utilizada como punto de partida para elaborar un proyecto con objetivos específicos. El framework es una especie de plantilla, un esquema conceptual, que simplifica la elaboración de una tarea, ya que solo es necesario complementarlo de acuerdo a lo que se quiere realizar.

    .row.justify-content-center.mb-4
      .col-md-10.borde2
        .row.p-4
          .col-md-4    
            img(src="@/assets/curso/tema2-2-img6.jpg", alt="Frontend")
          .col-md-8
            h4 Frontend
            p Este concepto se usa para hacer referencia a la presentación de las aplicaciones que se encarga de definir cómo se verán las cosas y cómo se comportará la interacción con el usuario. Frontend es la parte de una aplicación que interactúa con los usuarios, es conocida como el lado del cliente. Básicamente es todo lo que se ve en la pantalla al  acceder a un sitio <i>web</i> o aplicación: tipos de letra, colores, adaptación para distintas pantallas (RWD), los efectos del ratón, teclado, movimientos, desplazamientos, efectos visuales y otros elementos que permiten navegar dentro de una página <i>web</i>. Este conjunto crea la experiencia del usuario. Un desarrollador frontend debe conocer, al menos, los siguientes lenguajes de programación: HTML5, CSS3, JavaScript, Jquery, Ajax.z

    Separador


    .titulo-sexto.color-amarillo-fuerte-tercer.mb-4(data-aos="fade-right") 
      h3.mb-0 <i>software</i> para hacer diagramas

    p El diseño de diagramas también se puede realizar a través de plataformas o herramientas digitales. Para una mejor comprensión de los mismos se han clasificado en dos grupos: los que originalmente fueron ideados para hacer diagramas y los que no fueron pensados para diagramación, pero que también pueden usarse con este objetivo ya que son poderosas herramientas de diseño gráfico. 

    p.mb-5 Algunas aplicaciones <i>software</i> que fueron ideadas para hacer diagramas son:

    .row.justify-content-center
      .col-md-10
        SlyderD.mb-4(:datos="datosSlyder")

    p.mb-4 En cambio las aplicaciones <i>software</i> que no fueron ideadas específicamente para hacer diagramas pueden ser:

    .row.mb-5
      .col-md-4.mb-4
        .row.justify-content-center.img-tarjeta.mb-3
          .col-4
            img(src="@/assets/curso/tema2-2-a-hover1.png", alt="Corel Draw")
        h5.text-center Corel Draw
          br
          a.color-link(href="www.corel.com" target="_blank") www.corel.com
      .col-md-4.mb-4
        .row.justify-content-center.img-tarjeta.mb-3
          .col-4
            img(src="@/assets/curso/tema2-2-a-hover2.png", alt="Corel Draw")
        h5.text-center Adobe [antes Macromedia] FreeHand
          br
          a.color-link(href="https://www.adobe.com" target="_blank") www.adobe.com
      .col-md-4
        .row.justify-content-center.img-tarjeta.mb-3
          .col-4
            img(src="@/assets/curso/tema2-2-a-hover3.png", alt="Corel Draw")
        h5.text-center Adobe Illustrator
          br
          a.color-link(href="www.adobe.com" target="_blank") www.adobe.com


    .row.justify-content-center
      .col-md-10
        .bloque-texto-a.color-azul2.p-4.p-md-5.mb-4
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4
              img(src="@/assets/curso/tema2-2-a-img1.svg", alt="Imagen decorativa")
            .col-lg-8.mb-4.mb-lg-0
              .bloque-texto-a__texto.p-4
                p Otra opción para hacer la diagramación de sitios <i>web</i> es la propuesta por Jesse James Garret 
                  a.color-link(href="http://www.jjg.net" target="_blank") (http://www.jjg.net) 
                  | que consiste, según el propio autor, en un “vocabulario visual para describir arquitectura de información y diseño de interacción” 
                  strong (Garret, 2002). 
                  | El sistema de diagramación está compuesto de símbolos geométricos, flechas y líneas. El vocabulario visual de Garret es muy útil para representar tanto el diseño de interacción, como la estructura conceptual y organizativa del contenido. 
                  strong (Garret, 2002). 
                  | Esta notación gráfica está concebida para realizar un diseño de lo general a lo concreto, ya que sigue el principio de la simplificación de representación a partir de cajas (boxes) y flechas (arrows). Este principio es el que le facilita a cualquier diseñador comunicar arquitecturas de información de forma fácilmente comprensible.

    Separador


    // 2.3
    #t_2_3.titulo-segundo(data-aos="fade-right")
      .h2 2.3  Maquetación <i>web</i>

    .cajon.color-acento-botones.row.p-4.mb-5
      .col-md-3
        img(src="@/assets/curso/tema2-3-img1.jpg", alt="Imagen decorativa")
      .col-md-9
        p Este proceso inicia a partir de la construcción del mapa de navegación donde se planea el contenido y la organización de cada página y subpágina de un sitio <i>web</i>. 
        p La maquetación <i>web</i> consiste en definir, organizar y posicionar el contenido de la página, atendiendo a una estructura que se adecue a la lectura y a una presentación atractiva de la información y un buen diseño de la experiencia de usuario. Esta maquetación implica el conocimiento y manejo de algunos lenguajes de programación.
        p.mb-0 Para el proceso de maquetación se debe planificar lo siguiente: 

    PasosA.color-acento-contenido.azul-3.mb-5(tipo="n")
      .row
        .col-md-2.mb-4.mb-md-0
          figure
            img.px-md-3(src='@/assets/curso/tema2-3-paso1.svg', alt='Imagen decorativa')
        .col-md-9
          p Entendemos el desempeño Fijar unas zonas de trabajo que soportan la estructura de contenidos del sitio <i>web</i> y generar los recursos necesarios que faciliten la futura carga, siempre pensando en las necesidades reales de la estructura de contenido. 
      .row
        .col-md-9
          p Separar la presentación del contenido para facilitar el mantenimiento del sitio y las funcionalidades de la <i>web</i> de los archivos que definen las propiedades gráficas (.css). Además, este proceso optimiza la velocidad de carga de la <i>web</i> y permite la personalización del sitio según necesidades de los usuarios.
        .col-md-2.mb-4.mb-md-0
          figure
            img.px-md-3(src='@/assets/curso/tema2-3-paso2.svg', alt='Imagen decorativa')  
      .row
        .col-md-2.mb-4.mb-md-0
          figure
            img.px-md-3(src='@/assets/curso/tema2-3-paso3.svg', alt='Imagen decorativa')
        .col-md-9
          p Separar la Utiliza estándares en desarrollo de la maqueta, se recomienda el uso de los estándares <i>web</i> (conjunto de recomendaciones lideradas por la W3C) que permite mostrar la información de forma universal, robusta y poder acceder al mayor número de usuarios independientemente del dispositivo o la tecnología que usen.    

    p Así mismo, en la maquetación <i>web</i> se deben tener en cuenta la interfaz gráfica de usuario o GUI (Graphic User Interface) porque esta constituye el entorno visual de imágenes y objetos mediante el cual una máquina y un usuario interactúan. Es el contenido gráfico mediante el cual se visualiza información del equipo en una pantalla. Casi todos los programas tienen alguna clase de interfaz visual, que sirve al mismo tiempo para mostrar información al usuario.

    Separador


    .titulo-sexto.color-amarillo-fuerte-tercer.mb-4(data-aos="fade-right") 
      h3.mb-0 Lenguajes de programación para Fronted

    p.mb-4 Para introducir los lenguajes de programación más usados para el diseño <i>web</i>, es necesario definir primero el Frontend como parte fundamental del desarrollo <i>web</i>, lo cual se indica a continuación:  
    
    TabsC.color-primario.mb-5
      .py-3.py-md-4(titulo="Frontend")
        .row
          .col-md-5.mb-4.mb-md-0
            figure
              img.px-md-5(src='@/assets/curso/tema2-3-a-tab1.svg', alt='Frontend')
          .col-md-7
            h4 Frontend
            p Este concepto se usa para hacer referencia a la presentación de las aplicaciones, ya que se encarga de definir cómo se verán las cosas y cómo se comportará la interacción con el usuario. 
            p Frontend es la parte de una aplicación que interactúa con los usuarios; básicamente, es todo lo que se ve en la pantalla al acceder a un sitio <i>web</i> o aplicación: tipos de letra, colores, botones, adaptación para distintas pantallas (RWD), los efectos del ratón, teclado, movimientos, desplazamientos, menús efectos visuales y otros elementos que permiten navegar dentro de una página <i>web</i>. Este conjunto crea la experiencia del usuario. Esta área no trata directamente con bases de datos, servidores y todas las aplicaciones de back-end complejas, pero aborda la usabilidad, los efectos visuales y la velocidad de carga, entre otros detalles.
            p Un desarrollador frontend debe conocer, al menos, los siguientes lenguajes de programación: HTML5, CSS3, JavaScript, Jquery, Ajax. Entre los estándares más utilizados en maquetación <i>web</i> están los siguientes:
      .py-3.py-md-4(titulo="HTML")
        .row
          .col-md-5.mb-4.mb-md-0
            figure
              img.px-md-5(src='@/assets/curso/tema2-3-a-tab2.svg', alt='HTML')
          .col-md-7
            h4 HTML
            p Se trata de una sigla que corresponde a Hyper Text Markup Language, es decir, Lenguaje de Marcas de Hipertexto, que podría ser traducido como Lenguaje de Formato de Documentos para Hipertexto. Es el principal  lenguaje de marcación que se utiliza para el desarrollo de páginas <i>web</i>.
            p Una definición bastante descriptiva es la que se encuentra en la <i>web</i> Next U que habla de que el HTML es un lenguaje abstracto que usan las aplicaciones para representar documentos (se les llama documentos a instancias completas, como lo son las páginas <i>web</i>) y que puede ser transmitido fácilmente por algún medio, como Internet. Los navegadores de Internet procesan e interpretan documentos descritos en HTML usando un analizador de HTML.
            p El lenguaje HTML está definido por lo que se llama etiquetas, cuyo nombre se delimita usando los símbolos &#60; y &#62;, de la siguiente forma: &#60;etiqueta&#62;. Dichas etiquetas se utilizan para describir algo que se quiere representar en una página <i>web</i>. Por ejemplo: &#60;title&#62;Internet básico, email, descargas y compras en línea&#60;/title&#62; En este ejemplo, la etiqueta &#60;title&#62; se usa para indicar que lo que se pondrá a continuación es el título de la página <i>web</i>. 
              a.color-link(href="(https://www.nextu.com/blog/que-es-html/9)" target="_blank") (https://www.nextu.com/blog/que-es-html/9)
            p HTML5 también es un término de marketing para agrupar las nuevas tecnologías de desarrollo de aplicaciones <i>web</i>: HTML5, CSS3 y nuevas capacidades de JavaScript. HTML4 y HTML5 que son 100% compatibles entre sí. 
            p Las principales etiquetas HTML5 son:
            .row.align-items-bottom
              .col-md-4.mb-4
                ul.lista-ul
                  li 
                    i.fas.fa-angle-right
                    | Elemento raíz.
                  li 
                    i.fas.fa-angle-right
                    | Metadatos del documento.
                  li 
                    i.fas.fa-angle-right
                    | Secciones.
                  li 
                    i.fas.fa-angle-right
                    | Agrupación de contenido.
                  li.mb-0
                    i.fas.fa-angle-right
                    | Semántica a nivel de texto.      
              .col-md-8.mb-5
                .row
                  .col
                    img.px-md-1(src='@/assets/curso/tema2-3-a-tab2-1.svg', alt='CSS3')
                  .col
                    img.px-md-1(src='@/assets/curso/tema2-3-a-tab2-2.svg', alt='HTML5')  
                  .col
                    img.px-md-1(src='@/assets/curso/tema2-3-a-tab2-3.svg', alt='JS')
                  .col
                    img.px-md-1(src='@/assets/curso/tema2-3-a-tab2-4.svg', alt='JQuery')    
            .tarjeta.color-azul-fuerte.p-3.px-lg-5
              .row.justify-content-around.align-items-center
                .col-4.col-sm-3.col-lg-2.px-md-2
                  img(src="@/assets/curso/tema2-3-cta.svg")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0.text-white
                      h4 “Estructura del código HTML5”
                      p.text-small.mb-1 Estimado aprendiz, para profundizar sobre el tema y visualizar un ejemplo puede consultar la siguiente página:
                    .col-sm-auto
                      a.boton.color-acento-botones(:href="('https://vinkula.com/estructura-del-codigo-html5-anatomia-de-una-pagina-web/')" target="_blank")
                        span Enlace web
                        i.fas.fa-link       
      .py-3.py-md-4(titulo="CSS")
        .row
          .col-md-5.mb-4.mb-md-0
            figure
              img.px-md-5(src='@/assets/curso/tema2-3-a-tab3.svg', alt='CSS')
          .col-md-7
            h4 CSS
            p Las hojas de estilo en cascada, en inglés Cascading Style Sheets, controlan la apariencia visual del sitio web y permiten darle un aspecto único. Esto se consigue con hojas de estilo que se sobreponen sobre otras reglas de estilo y se lanzan basándose en el tipo de entrada, como el tamaño y la resolución de la pantalla del dispositivo.
            p Tras la aparición de la primera versión en 1993, el lenguaje HTML ha ido evolucionando hasta convertirse en un estándar, o en lo que se conoce hoy en día como HTML5, el cual tiene características mucho más robustas, como el audio, video, gráficos SVG y la adaptación a distintos dispositivos. Estos avances han sido posible gracias a las hojas de estilo en cascada.
            p El código CSS es utilizado para organizar la presentación y el aspecto de cualquier página <i>web</i>; es decir, el CSS definirá cómo van a lucir los elementos de un documento HTML. 


    .titulo-sexto.color-amarillo-fuerte-tercer.mb-4(data-aos="fade-right") 
      h3.mb-0 Estructuración técnica de un sitio <i>web</i>

    figure.mb-4
      img(src='@/assets/curso/tema2-3-b-img1.jpg', alt='Estructuración técnica de un sitio web')

    p.mb-4 Para estructurar un sitio <i>web</i> es importante tener en cuenta algunos pasos consecutivos que son claves para hacerlo de la mejor manera, pensando no solo como fijar la estructura casi a la perfección desde el punto de vista conceptual, sino también en la temática que se presentará en la página <i>web</i> y cómo va a ser expuesta porque sin ello es imposible crear una buena estructura después. Estos son:
          
    .row.mt-5
      .col-10.col-lg-8.offset-1.offset-lg-2.py-5.px-4.rounded-20.borde-1-azul
        .row
          .col-4.borde-3-der-azul
            figure
              img(src="@/assets/curso/tema2-3-b-img2.svg", alt="Imagen decorativa").w-75.margin-0-auto
          .col-12.col-lg-8.align-self-center.px-4
            p.mb-0 Es la población o conjunto de elementos totales que se pueden contar o medir, por ejemplo, la población de una ciudad.
    .row.mt-4
      .col-10.col-lg-8.offset-1.offset-lg-2.py-5.px-4.rounded-20.borde-1-azul
        .row
          .col-4.borde-3-der-azul
            figure
              img(src="@/assets/curso/tema2-3-b-img3.svg", alt="Imagen decorativa").w-75.margin-0-auto
          .col-12.col-lg-8.align-self-center.px-4
            p.mb-0 Hacer estructura de un sitio <i>web</i> con URLS amigables para SEO. Al crear las páginas de la <i>web</i>, lo que se está creando son diferentes URLS o “direcciones” dentro de la misma, partiendo de un dominio común. Detrás de la barra, sin embargo, se necesita poner palabras indicativas. Lo primero que ve Google al rastrear la estructura de un sitio <i>web</i> es la URL. 
    .row.mt-4.mb-5
      .col-10.col-lg-8.offset-1.offset-lg-2.py-5.px-4.rounded-20.borde-1-azul
        .row.align-items-center
          .col-4.borde-3-der-azul
            figure
              img(src="@/assets/curso/tema2-3-b-img4.svg", alt="Imagen decorativa").margin-0-auto
          .col-12.col-lg-8.align-self-center.px-4
            p.mb-0 Se trata de conectar todas las páginas entre sí de forma que mejore la navegabilidad y la experiencia del usuario, o sea, la usabilidad. Por eso no debemos ampararnos únicamente en el menú superior de navegación, sino añadir enlaces internos entre páginas. Enlaces internos que tienen dos funciones: orientar al usuario dependiendo del caso, poniéndole algunos enlaces o llamadas a la acción para que Google sea capaz de rastrear todas y cada una de las páginas de la <i>web</i> de forma más rápida. De esta forma Google calificará mejor porque le facilita el trabajo de navegación al usuario y el trabajo de desindexación a Google mismo. La usabilidad y la estructura están íntimamente relacionadas dentro del diseño <i>web</i>. 

    .row.justify-content-center(data-aos="fade-down")
      .col-lg-10    
        .tarjeta.color-azul-fuerte.p-3.px-lg-5
          .row.justify-content-around.align-items-center
            .col-4.col-sm-3.col-lg-2.px-lg-3
              img(src="@/assets/curso/tema2-3-b-cta.svg")
            .col
              .row.justify-content-between.align-items-center.mb-4
                .col.mb-3.mb-sm-0.text-white
                  h4 “¿Qué es la maquetación <i>web</i>?”
                  p.text-small.mb-1 Estimado aprendiz, para profundizar sobre el tema puede consultar la siguiente página:
                .col-sm-auto
                  a.boton.color-acento-botones(:href="('https://www.crehana.com/co/blog/desarrollo-web/que-es-maquetacion-web/')" target="_blank")
                    span Enlace web
                    i.fas.fa-link  
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h4 “Maquetación de una página <i>web</i> con HTML y CSS”
                  p.text-small.mb-1 Estimado aprendiz, para profundizar sobre el tema puede consultar el siguiente video:
                .col-sm-auto
                  a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?v=VnZwBIwT4Rw')" target="_blank")
                    span Enlace web
                    i.fas.fa-link         

    Separador


    // 2.4
    #t_2_4.titulo-segundo(data-aos="fade-right")
      .h2 2.4  Tipos de medios y plataformas digitales

    .row
      .col-md-7.mb-4
        p El desarrollo tecnológico que viene experimentando la sociedad, ha llevado en pocos años a ampliar los conceptos, herramientas y por supuesto los medios referidos a la internet. Al inicio, los sitios o páginas <i>web</i> estaban disponibles sólo a través de los computadores de escritorio; posteriormente surgen los computadores portátiles, para finalmente dar paso a los dispositivos móviles como <i>Smartphone</i> (teléfonos inteligentes) y <i>Tablet</i>. 

        p En este proceso de transformación y especialización surge el concepto de diseño <i>web</i> <i>responsive</i> o adaptativo que consiste en la aplicación de una técnica de diseño <i>web</i> que busca la correcta visualización de una misma página en distintos dispositivos, como ordenadores de escritorio y móviles pasando por <i>Tablet</i>.

        p En la siguiente figura se puede observar que este diseño no consiste en conseguir que se vea lo mismo en todos los dispositivos:
      .col-md-5.mb-4
        img(src="@/assets/curso/tema2-4-img1.svg", alt="Imagen decorativa") 

    .row.justify-content-center
      .col-lg-10.mb-5    
        h5 Figura 3
        p Diseño <i>responsive</i>
        img(src="@/assets/curso/tema2-4-figura.jpg", alt="Diseño responsive")

    p De lo que se trata es de redimensionar y colocar los elementos que tendrá la <i>web</i>, de forma que se adapten al ancho de cada dispositivo permitiendo una correcta visualización y una mejor experiencia de usuario. Se caracteriza porque los layouts (contenidos) e imágenes son fluidos y se usa código media-queries de CSS3.

    Separador


    .titulo-sexto.color-amarillo-fuerte-tercer.mb-4(data-aos="fade-right") 
      h3.mb-0 La <i>web</i> <i>responsive</i>

    img.mb-4(src="@/assets/curso/tema2-4-a-img1.jpg", alt="La web responsive")

    p Además de la correcta visualización y navegación, las páginas <i>web</i> deben adaptarse a determinaciones externas que afectan su funcionamiento en los servidores, buscadores, navegadores, etc. Tal es el caso y resulta importante mencionar, que Google, el mayor buscador de Internet, ha actualizado el sistema de calificación de sitios <i>web</i> para proporcionar mejores resultados de búsqueda a los usuarios que usan móviles. Dicho de otra manera, si una página <i>web</i> no es <i>responsive</i>, podría ser excluida de los resultados de búsqueda móvil de Google o clasificarse más bajo en SERP.

    p.mb-5 Con la llegada del teléfono inteligente el mundo cambió, y las páginas <i>web</i> también; algunas cosas se volvieron más prácticas, así como también, las páginas <i>web</i>. Las personas tienen conexión y acceden a la red hoy día en cualquier momento y en cualquier lugar. Por tanto, tener un sitio <i>web</i> optimizado para dispositivos móviles expande todas las posibilidades y abre la puerta a una audiencia más grande. De acuerdo a 
      strong Shum (2021): 
      | “En la actualidad el 70% del tráfico de internet proviene de teléfonos móviles”. 


    .titulo-sexto.color-amarillo-fuerte-tercer.mb-4(data-aos="fade-right") 
      h3.mb-0 Ventajas de tener un sitio <i>web</i> <i>responsive</i> 

    .row.justify-content-center
      .col-md-10
        .bloque-texto-a.color-azul2.p-4.p-md-5.mb-4
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4
              img.px-md-4(src="@/assets/curso/tema2-4-b-img1.svg", alt="Ventajas de tener un sitio web responsive")
            .col-lg-8.mb-4.mb-lg-0
              .bloque-texto-a__texto.p-4
                p Según el sitio <i>web</i> Hostinger Tutoriales las ventajas de incorporar el diseño <i>responsive</i> se materializan en las estrategias del marketing digital y los resultados de estas.

    .row.mt-4
      .col-10.col-lg-8.offset-1.offset-lg-2
        .cajon.color-acento-contenido.bg-azul1.p-4.mb-4
          .h4 Mejor SEO
          p.mt-4 El diseño del sitio <i>responsive</i> utiliza la misma URL y HTML, independientemente del dispositivo utilizado para acceder a la página. Esta configuración permite a Google explorar, indexar y administrar el contenido del sitio de manera más fácil y eficiente. Como resultado, el sitio <i>web</i> tendrá una mejor calidad de SEO (posicionamiento en buscadores u optimización de motores de búsqueda que arroja resultados orgánicos de los diferentes buscadores).
    .row.mt-4
      .col-10.col-lg-8.offset-1.offset-lg-2
        .cajon.color-acento-contenido.bg-azul2.p-4.mb-4
          .h4 No es necesario crear un nuevo diseño
          p.mt-4 Los sitios <i>web</i> <i>responsive</i> no necesitan una nueva apariencia o diseño para dispositivos móviles. En otras palabras, la visualización del sitio <i>web</i> seguirá siendo la misma, aunque se acceda desde varios tipos diferentes de dispositivos. Al no tener que crear dos diseños de sitios <i>web</i>, se puede ahorrar mucho tiempo y energía.
    .row.mt-4
      .col-10.col-lg-8.offset-1.offset-lg-2
        .cajon.color-acento-contenido.bg-azul3.p-4.mb-4
          .h4 Más fácil de administrar y rentable
          p.mt-4 Un sitio <i>web</i> <i>responsive</i> es fácil de administrar y desarrollar. Todas las actualizaciones que realices aparecerán en cada dispositivo que acceda al sitio <i>web</i>, no hay diferencia en el contenido que aparece tanto en la PC, computadora portátil o teléfonos inteligentes. Además, los costos operativos de un sitio <i>web</i> receptivo son más bajos, ya que no es necesario desarrollar sitios <i>web</i> para PC y para dispositivos móviles por separado.

</template>

<script>
import AcordeonB from '../components/AcordeonB'
export default {
  name: 'Tema2',
  components: {
    AcordeonB,
  },
  data: () => ({
    datosSlyder: [
      {
        titulo: 'SmartDraw',
        texto: 'http://www.smartdraw.com',
        imagen: require('@/assets/curso/tema2-2-a-slider1.jpg'),
      },
      {
        titulo: 'Microsoft Visio',
        texto: 'http://www.microsoft.com',
        imagen: require('@/assets/curso/tema2-2-a-slider2.jpg'),
      },
      {
        titulo: 'iGrafx Flowcharter',
        texto: 'http://www.igrafx.de',
        imagen: require('@/assets/curso/tema2-2-a-slider3.jpg'),
      },
      {
        titulo: 'Mindmanager',
        texto: 'http://www.mindjet.com',
        imagen: require('@/assets/curso/tema2-2-a-slider4.jpg'),
      },
      {
        titulo: 'Freemind',
        texto: 'http://freemind.sourceforge.net/wiki/index.php/Main_Page',
        imagen: require('@/assets/curso/tema2-2-a-slider5.jpg'),
      },
      {
        titulo: 'OmniGraffle (OSX)',
        texto: 'http://www.omnigroup.com',
        imagen: require('@/assets/curso/tema2-2-a-slider6.jpg'),
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

<style lang="sass" scoped>
italic
  font-style: oblique
italic-strong
  font-style: oblique
  font-weight: bold

.azul2
  background-color: #116DD9
.color-amarillo-fuerte
  background-color: #FFC935

.bloque-texto-a.color-azul
  background-color: #2F94FF
.bloque-texto-a.color-azul:before
  background-color: #e4f6ff

.bloque-texto-a.color-azul2
  background-color: #e4f6ff
.bloque-texto-a.color-azul2:before
  background-color: #2F94FF

.linea-tiempo-d.color-acento-botones.color-amarillo .linea-tiempo-d__item--selected .linea-tiempo-d__item__number
  background-color: #fff1cc !important
.linea-tiempo-d__item--selected .linea-tiempo-d__item__content
  background-color: #fff1cc !important

.color-azul-fuerte
  background-color: #084A93

.alto-igual
  display: -webkit-flex
  display: flex
.borde
  background-color: #F0FCFF
  border-top: 4px solid #116DD9
  border-bottom: 4px solid #116DD9
  border-right: 4px solid #116DD9
  border-top-right-radius: 20px
  border-bottom-right-radius: 20px

.borde2
  border: 4px solid #2F94FF
  border-radius: 20px

.imagen_flotante_1
  animation: float 6s ease-in-out infinite
  top: -127px
  left: 0
@keyframes float
	0%
		transform: translatey(0px)
	50%
		transform: translatey(-20px)
	100%
		transform: translatey(0px)

li .fa-angle-right::before
  color: #004046

.acordeon-tema2-2
  margin-bottom: 0rem !important

.titulo-sexto.color-amarillo-fuerte-tercer h3
  background-color: #FFC935
  padding: 5px 10px 5px 2px
  width: fit-content

.slyder-d__content
  width: 100% !important
.slyder-d__content__card
  background-color: #F0FCFF !important

.img-tarjeta
  height: 200px
  display: flex
  align-content: center
  transition-duration: 0.2s
  transition-delay: 0.3s
.img-tarjeta:hover
  background-color: #F0FCFF
  transition-duration: 0.2s
  transition-delay: 0.3s
.img-tarjeta:after
  content: " "
  width: 68%
  right: 0
  bottom: 0
  height: 20px
  z-index: 999
  -moz-box-shadow: 0px 4px 6px -6px #b3b1b1
  -webkit-box-shadow: 0px 4px 6px -6px #b3b1b1
  box-shadow: 0px 4px 6px -6px #b3b1b1
.img-tarjeta:hover:after
  content: " "
  right: 0
  bottom: 0
  height: 0px
  z-index: 0

.tabs-c__tab--active span
  font-weight: bold !important

.align-items-bottom
  display: flex
  align-items: flex-end

.borde-1-azul
  border: 4px solid #2F94FF
.borde-3-der-azul
  border-right: 3px solid #2F94FF

.bg-azul1
  background-color: #c9e3ff
.bg-azul2
  background-color: #D9EBFD
.bg-azul3
  background-color: #eff7ff
</style>
