<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
      .titulo-principal__numero
        span 1
      h1 	Montaje audiovisual
    figure.mt-4
      img(src="@/assets/template/tema-1-1.png", alt="Texto que describa la imagen")
    p.mt-5 La composición gráfica se refiere a la organización o disposición de elementos dentro del espacio visual, con el objeto de construir una imagen que transmita una idea de manera sencilla y directa a un público objetivo. Esta premisa sigue teniendo la misma validez para cuando se trata de la creación y/o edición de imágenes fijas, pero tiene una definición distinta cuando se trata de imágenes en movimiento. 
    .row.mt-5
      .col-4.col-lg-5.offset-4.offset-lg-0.align-self-center
        figure
          img(src="@/assets/curso/1.svg", alt="Texto que describa la imagen")
      .col-12.col-lg-7
        p Es común hablar de edición y montaje como el mismo proceso técnico, ya que la palabra montaje, del francés #[i montage], hace referencia a montar, poner encima; pero para los teóricos del lenguaje audiovisual, el montaje tiene que ver con un proceso narrativo, mientras que la edición contempla un proceso de tipo técnico. De esta manera, lo que se refiere a la composición de mensajes o significados a través de elementos audiovisuales se conoce como montaje audiovisual, que es el paso técnico y narrativo último del producto audiovisual, aunque viene definido previamente en la elaboración del guion.
        p.mt-3 En todo caso, para desarrollar los temas necesarios en este apartado, se deben considerar las dos definiciones, porque como es sabido, en lo que respecta al tratamiento de imágenes fijas, lo común es hablar de “edición de imágenes”, mientras que montaje fotográfico o fotomontaje se refiere a un producto de la edición. 
    p.mt-4 Por consiguiente, a continuación, se hace un acercamiento frente a las definiciones: 
    Separador
    TabsB.color-primario.mb-5
      .py-4.py-md-5(titulo="Definición montaje" :icono="require('@/assets/curso/2.svg')")        
        .row
          .col-12.col-lg-8
            .h4 Definición montaje
            p Este término se define como un conjunto de relaciones espacio-temporales, creadas mediante la combinación y duración de los fragmentos, que permiten articular un mensaje audiovisual con fluidez, timo, coherencia y expresión propia, que atiende a las intenciones del emisor y las capacidades y expectativas del receptor.
          .col-4.offset-4.offset-lg-0
            figure
              img(src="@/assets/curso/4.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
      .py-4.py-md-5(titulo="Definición edición" :icono="require('@/assets/curso/3.svg')")
        .row
          .col-12.col-lg-8
            .h4 Definición edición
            p Hace referencia a la posibilidad de manipular la imagen capturada o creada y mejorarla, adaptarla o dotarla   según las necesidades requeridas.
          .col-4.offset-4.offset-lg-0
            figure
              img(src="@/assets/curso/5.svg", alt="Texto que describa la imagen").w-75.margin-0-auto
    Separador
    #t_1_1.titulo-segundo(data-aos="fade-right")
      h2 1.1  Edición de imagen

    p Cuando se habla de edición digital se involucran en el proceso una imagen, un terminal computarizado (equipo de escritorio, portátil, <i>tablet</i>, celular, dispositivo móvil) y un software especializado para tal fin.
    p Antes de entrar de lleno en el proceso de edición de la imagen, es necesario hablar de la imagen en sí misma y dejar claras sus características y los tipos de imagen digital, ya que de esta clasificación dependerá su tratamiento:      
      
    .row.justify-content-center.tarjeta.bg--row.p-4.my-5(data-aos="zoom-in-up") 
      .col-11
        TabsC.color-primario.mb-5
          .py-3.py-md-4(titulo="Inicio")
            img(src="@/assets/curso/6.jpg")
          .py-3.py-md-4(titulo="Edición de imagen")
            
              
                .row.mb-5
                  .col-lg-7
                    .tarjeta.tarjeta--azul.p-4.mb-5.mb-lg-0
                      .titulo-sexto.color-primario(data-aos="fade-right")
                        h4.mb-0
                          spam.bg--4.p-1
                            | Edición de imagen
                      p Cuando se habla de edición digital se involucran en el proceso una imagen, un terminal computarizado (equipo de escritorio, portátil, <i>tablet</i>, celular, dispositivo móvil) y un <i>software</i> especializado para tal fin.
                        br
                        br
                        |Antes de entrar de lleno en el proceso de edición de la imagen, es necesario hablar de la imagen en sí misma y dejar claras sus características y los tipos de imagen digital, ya que de esta clasificación dependerá su tratamiento: 
                  .col-lg-5: img(src="@/assets/curso/7.jpg")(data-aos="fade-right")
                .grupo-iconos.d-flex.justify-content-center
                  .contenedor_iconos.m-2  
                    img(src="@/assets/curso/8.svg" style="width: 128px").mb-3.m-auto
                    h5.text-center Imagen
                  .contenedor_iconos.m-2   
                    img(src="@/assets/curso/9.svg" style="width: 128px").mb-3.m-auto
                    h5.text-center Objetivo
                  .contenedor_iconos.m-2   
                    img(src="@/assets/curso/10.svg" style="width: 128px").mb-3.m-auto
                    h5.text-center Filtro Infrarojo
                  .contenedor_iconos.m-2   
                    img(src="@/assets/curso/11.svg" style="width: 128px").mb-3.m-auto
                    h5.text-center Filtro RGB
                  .contenedor_iconos.m-2   
                    img(src="@/assets/curso/12.svg" style="width: 128px").mb-3.m-auto
                    h5.text-center Matriz CCD
                  .contenedor_iconos.m-2   
                    img(src="@/assets/curso/13.svg" style="width: 128px").mb-3.m-auto
                    h5.text-center Conversor ADC
                  .contenedor_iconos.m-2   
                    img(src="@/assets/curso/14.svg" style="width: 128px").mb-3.m-auto
                    h5.text-center Dígitos sistema binarío
          .py-3.py-md-4(titulo="La imagen digital ")
            
                figure.mb-5
                  img(src="@/assets/curso/15.jpg" alt="Texto que describa la imagen")
                .tarjeta.tarjeta--azul.p-4.mb-5.mb-lg-0
                      .titulo-sexto.color-primario(data-aos="fade-right")
                        h4.mb-0
                          spam.bg--4.p-1
                            | La imagen digital
                      p Según la 
                        b (Real Academia Española, s. f.) 
                        |una imagen es toda forma o figura percibida por el sentido de la vista. 

                        br
                        br
                        |Se define que como una 
                        b imagen digital o gráfico digital, 
                        |la cual es representada de manera bidimensional, a partir de una imagen de una matriz numérica, frecuentemente en binario unos y ceros; esta se almacena en una memoria informática para luego ser interpretada por un sistema informático y que se transforma en una imagen visible a través de la pantalla e imprimible a través de cualquier dispositivo de salida.
          .py-3.py-md-4(titulo="Tipos de imágenes digitales")
            .titulo-sexto.color-primario(data-aos="fade-right")
              h4.mb-0
                spam.bg--4.p-1
                  | Tipos de imágenes digitales
            p Por su estructura, estas pueden ser de dos tipos:
            SlyderE(indicadores="centro")
              .row
                .col-lg-8
                  h4 Imágenes en mapa de bits
                  p Son las captadas del mundo real a través de dispositivos digitales; según Ordóñez (2005):
                    br
                    br
                    |Es una #[b estructura de datos que representa una rejilla rectangular de píxeles o puntos de color] conocida como <i>raster</i>, la cual puede visualizarse en un monitor de computadora, papel u otros dispositivos de representación. Este tipo de imágenes se obtiene de medios como el escáner o las cámaras digitales; su representación en pantalla es a través de la unidad mínima denominada píxel, que proviene del inglés <i>picture element</i>. Un píxel es la menor unidad en que se descompone una imagen digital, ya sea una fotografía, fotograma de video o gráfico. Un píxel es un concepto inmaterial que no tiene una medida concreta.
                .col-lg-4: img(src="@/assets/curso/16.jpg")
              .row
                .col-lg-8
                  h4 Imágenes vectoriales
                  p Son las creadas desde su inicio a través de un <i>software</i> que, mediante cálculos matemáticos y coordenadas sobre los ejes “X” y “Y” en la pantalla, describen posiciones de puntos trazados líneas curvas o rectas que se generan como objetos independientes, por lo que después se pueden modificar fácilmente sin que por ello los demás componentes del dibujo se vean modificados. En los mapas de bits lo que ocurre es que, al incluir un elemento en la imagen, este queda automáticamente incrustado y no puede volver a editarse de manera independiente. Las vectoriales no necesitan mucho espacio de almacenamiento y son independientes de la resolución, ya que no dependen de una retícula determinada. 
                    br
                    br
                    |Pese a que presentan características distintas, cada día es más común que ambos tipos de imágenes se vinculen a través de programas de tratamiento de imágenes.
                .col-lg-4: img(src="@/assets/curso/17.jpg")
          .py-3.py-md-4(titulo="Elementos de la imagen digital")
              .row.justify-content-center
                .col-lg-10
                  .cajon-editado
                    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
                      .bloque-texto-g__img(
                        :style="{'background-image': `url(${require('@/assets/curso/18.jpg')})`}"
                      )
                      .bloque-texto-g__texto.p-4
                        .textos.d-block 
                          h4 Elementos de la imagen digital
                          p.mb-0 Una vez definidos los tipos de imagen digital, a continuación se presentan algunos elementos propios del universo de la imagen digital, que ayudan a la comprensión de su construcción y posterior edición.
          .py-3.py-md-4(titulo="Formatos")
            SlyderE(indicadores="centro").mb-5
              div
                .tarjeta.tarjeta--azul.p-4.mb-5.mb-lg-5
                  .titulo-sexto.color-primario(data-aos="fade-right")
                    h4.mb-0
                      spam.bg--4.p-1
                        | Formatos
                  p Se refieren a la forma codificada que adquieren las imágenes al ser almacenadas en un dispositivo. En realidad se trata de cómo se almacenan digitalmente los píxeles que componen las imágenes digitales de mapa de bits o vectores. Cada formato cuenta con su propia metodología para almacenar información de la imagen digital y cada uno tiene fortalezas, pero también desventajas. El formato depende de las características, la calidad y el uso final del nuevo archivo. 
                .titulo-sexto.color-primario.mt-5(data-aos="fade-right")
                  h4.mb-0
                    spam.bg--4.p-1
                      | Formatos para mapa de bits 
                .tarjeta.bg--1.p-4
                  SlyderA
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/19.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white BMP: desarrollado para sistemas operativos Microsoft como formato de almacenamiento para mapas de bits con una profundidad de color de hasta 24 bits por píxel. Los archivos en este formato son relativamente grandes, por lo que no es adecuado para ser usado en páginas <i>web</i>.
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/20.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white TIFF: formato que se utiliza para la transmisión de datos impresos y de imágenes de alta resolución; soporta el modelo de color CMYK y permite una profundidad de color de hasta 16 bits. Es el formato estándar cuando la calidad prima sobre el tamaño de los archivos. Es empleado por las editoriales y los medios impresos.
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/21.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white JPEG: sistema de compresión con pérdida, utilizado para lograr que las imágenes digitales que se utilizan sean lo más pequeñas posible y se carguen rápidamente en el documento.
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/22.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white GIF: es el formato preferido en Internet gracias a su posibilidad de animar imágenes. Los archivos GIF utilizan mapas de bits y admiten hasta 8 bits/píxel, permitiendo 256 colores en la gama RGB. 
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/23.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white PSD: del inglés “Photoshop Document”, es un formato nativo de proyectos gráficos desarrollados con Photoshop. Guarda la información relacionada con las capas, los canales, la historia, lo que permite la posterior edición de los mismos. Las imágenes en formato PSD solo pueden abrirse y editarse con Adobe Photoshop. Las imágenes resultantes son de tipo píxel. 
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/24.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white RAW: solo se encuentra disponible en cámaras digitales sofisticadas, indicadas para fotógrafos profesionales. Este formato ofrece la máxima calidad ya que contiene los píxeles en bruto tal y como se han adquirido, generando un archivo que contiene la totalidad de los datos de la imagen, por lo que comúnmente se lo conoce como negativo digital. Los datos del archivo RAW generan un tipo de compresión sin pérdida de información, por lo que comúnmente suele decirse que no comprimen. 
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/25.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white PDF: del inglés Portable Document Format. Es un tipo de archivo universal, que funciona independientemente del <i>software</i>, del sistema operativo, de la resolución, de la versión, entre otros; usados para la creación del archivo original. Este formato permite el almacenamiento de archivos bitmap, vector, texto, adicionalmente soporta archivos que pueden tener diversas páginas.
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/26.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white PNG: este formato se destaca porque permite comprimir imágenes sin pérdidas de calidad.  Además, ofrece la posibilidad de almacenar y publicar imágenes y gráficos respetando las transparencias. 
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/27.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white EPS: del inglés Encapsulated PostScript, es un formato estandarizado que permite importar y exportar archivos de texto e imágenes, es compatible con todos los sistemas operativos. Se usa básicamente en el ámbito editorial.
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/28.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white AI: es la extensión nativa de los archivos generados desde Adobe Illustrator, que se clasifican como archivos de imágenes vectoriales. Las imágenes vectoriales son las más indicadas para usar en páginas <i>web</i> por el peso final de ellas. Una ventaja de la imagen vectorial es que se pueden escalar sin que pierdan calidad, al tiempo que requiere menos espacio de almacenamiento.
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/29.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white SVG: del inglés Scalable Vector Graphics. Al igual que el formato Ai, el SVG es una extensión de gráficos vectoriales bidimensionales, tanto estáticos como animados. Es un formato poco conocido pero muy útil para ser utilizarlo en entornos digitales. Su ventaja radica en que es un formato abierto y estándar.
                    .row.p-4.align-items-center.justify-content-center
                      .col-md-2
                        figure
                          img(src="@/assets/curso/30.svg")           
                      .col-md-8.mb-4.mb-md-0
                        p.text-white CDR: es la extensión nativa de los archivos generados desde Corel Draw. Al igual que los archivos Ai, las imágenes resultantes de Corel se clasifican como archivos de imágenes vectoriales. Se puede decir que Corel Draw es la competencia directa de Illustrator.
              div
                .tarjeta.color-primario.p-3.mb-5
                  .row.justify-content-around.align-items-center
                    .col-3.col-sm-2.col-lg-2
                      img(src="@/assets/curso/31.svg")
                    .col
                      .row.justify-content-between.align-items-center
                        .col.mb-3.mb-sm-0
                          h3.mb-1 Formatos de imagen digital
                          p.text-small Estimado aprendiz, para profundizar sobre el tema puede dar clic para ir al siguiente documento "Formato de imagen digital"
                        .col-sm-auto
                          a.boton.color-acento-botones(:href="obtenerLink('/downloads/formatos_imagen_digital.pdf')" target="_blank")
                            span Descargar
                            i.fas.fa-file-download
                      .row.justify-content-between.align-items-center
                        .col.mb-3.mb-sm-0
                          h3.mb-1 Mapa de Bits e Imágenes Vectoriales
                          p.text-small Estimado aprendiz, para profundizar sobre el tema puede consultar la siguiente video:  
                        .col-sm-auto
                          a.boton.color-acento-botones(:href="('https://www.youtube.com/watch?v=9i_0cLdJE-s&ab_channel=HeyJaime')" target="_blank")
                            span Enlace web
                            i.fas.fa-link


          .py-3.py-md-4(titulo="Resolución de la imagen")
            SlyderE(indicadores="centro").mb-5
              div
                .tarjeta.tarjeta--azul.p-4.mb-5.mb-lg-5
                      .titulo-sexto.color-primario(data-aos="fade-right")
                        h4.mb-0
                          spam.bg--4.p-1
                            | Resolución de la imagen
                      p Desde una visión general, según Fernández (2015):
                        br
                        br
                        |La resolución se refiere a la capacidad de una tecnología o un mecanismo para reflejar los detalles de una imagen. A mayor resolución, mejor calidad de imagen, pero también más tamaño y peso. 
                        br
                        |Si se divide una imagen en pocos píxeles, se podrá codificar con poca información, pero seguramente perderá mucho detalle, por lo que se dice que tiene poca resolución. Si se divide en muchas más partes, estas llegarán a ser tan pequeñas que no se podrán  distinguir. La visión de la imagen será mucho mejor y más detallada, pero también mucho más costosa en bits al ser más grande y más pesada. 
                .row.p-4.align-items-center.justify-content-center
                  .col-lg-10
                    figure
                      img(src="@/assets/curso/32.jpg")
              div
                .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-3.mb-5
                  .bloque-texto-g__img(
                    :style="{'background-image': `url(${require('@/assets/curso/33.jpg')})`}"
                  )
                  .bloque-texto-g__texto.p-4.w-90.text-small
                    h4.d-block Resolución de la imagen
                    p.mb-0 El tamaño y la frecuencia de los píxeles siempre son elección del diseñador, quien deberá tener en cuenta que el concepto de resolución hace referencia a tres tipos de tamaño:  en píxeles, el informático (pantalla) y el superficial. El tamaño en píxeles habla, como ya se ha dicho, de en cuántas filas y columnas se divide la imagen, o de cuál es el número total de píxeles. 
                      br
                      br
                      |El tamaño informático se cuenta en unidades de información como <i>bytes</i>, <i>kilobytes</i> o <i>megabytes</i>, y depende del número de píxeles y de la cantidad de <i>bytes</i> que gastamos para definir cada píxel. Tamaño de salida es lo que ocupará la foto si se imprime; como los píxeles son información numérica, es el editor quien decide, cuántos píxeles quiere imprimir en cada centímetro o pulgada de papel.
                      br
                      br
                      |En conclusión, tal y como lo expresa Fernández (2005):
                .row.align-items-center
                  .col-5.col-lg-2.col-md-3.col-sm-4: img(src="@/assets/curso/34.svg")
                  .col-7.col-lg-10.col-md-9.col-sm-8
                    .bloque-texto-b.color-secundario.p-4
                      .bloque-texto-b__texto
                        i.fas.fa-quote-left
                        h5.mb-0 La resolución de una imagen digital se expresa multiplicando su anchura por la altura en píxeles. Por ejemplo la imagen de 1200 x 1200 píxeles = 1.440.000 píxeles, expresado en Mp (megapíxel) es igual a 1,4 Mp. Conviene tener en cuenta que 1 Megapíxeles = 1024 píxeles.
                        i.fas.fa-quote-right                       
          .py-3.py-md-4(titulo="Modos de color")
            SlyderE(indicadores="centro").mb-5
              div
                p.mb-5 Además del formato y la resolución, otro elemento imprescindible en la imagen es el color.
                .row.justify-content-center
                  .col-lg-10
                    .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-3.mb-5
                      .bloque-texto-g__img(
                        :style="{'background-image': `url(${require('@/assets/curso/35.jpg')})`}"
                      )
                      .bloque-texto-g__texto.p-4.w-90.text-small
                        h4.d-block Modos de color
                        p.mb-0 El color puede entenderse en términos técnicos como la profundidad de color en la imagen, es decir, la cantidad de bits de información necesarios para representar el color de un píxel en una imagen digital.  En términos generales se alude al concepto de modelo de color en la imagen, que describe los colores que pueden verse en las imágenes digitales e impresas. Se pueden diferenciar tres modelos de color para trabajar en multimedia: modelo RGB, modelo CMYK y modelo HSB.
              div 
                .row.mt-3
                  .col-4
                    figure
                      img(src="@/assets/template/tema-1-32.png", alt="Texto que describa la imagen")
                    p.mt-4 #[strong Color CMYK:] se refiere a los colores Cian, Magenta, Yellow y Black, que son los colores que se usan en impresión.
                  .col-4
                    figure
                      img(src="@/assets/template/tema-1-33.png", alt="Texto que describa la imagen")
                    p.mt-4 #[strong Color RGB:]  Red, Green, Blue. Este es el espacio de color que usan los monitores para presentar este tipo de imagen tricromática.
                  .col-4
                    figure
                      img(src="@/assets/template/tema-1-34.png", alt="Texto que describa la imagen")
                    p.mt-4 #[strong Escala de grises:] este modo de color presenta una imagen monocromática que maneja un espacio de colores limitado a 256 porcentajes de negro.
                .row.mt-3
                  .col-4
                    figure
                      img(src="@/assets/template/tema-1-35.png", alt="Texto que describa la imagen")
                    p.mt-4 #[strong Color Lab:] consiste en tres canales: un canal de luminosidad (L) y dos canales cromáticos, A (que oscila entre verde y rojo) y B (que oscila entre azul y amarillo). #[strong (M, 2014).]
                  .col-4
                    figure
                      img(src="@/assets/template/tema-1-36.png", alt="Texto que describa la imagen")
                    p.mt-4 #[strong Mapa de bits:] el modo Mapa de bits utiliza uno de los dos valores de color (blanco o negro) para representar los píxeles de una imagen. Las imágenes en modo Mapa de bits se denominan imágenes monocromáticas.
                  .col-4
                    figure
                      img(src="@/assets/template/tema-1-37.png", alt="Texto que describa la imagen")
                    p.mt-4 #[strong Color indexado:] en este modo el número de colores máximo es de 256. #[strong (M, 2014).]
    p.mb-5 Ya vistos los temas que conciernen a la imagen digital, es momento de pasar a la edición de la misma. Para iniciar, una breve definición:
    Separador
    .titulo-sexto.color-primario(data-aos="fade-right")
      h4.mb-0
        spam.bg--4.p-1
          | Definición de edición de la imagen
    .contenedor-jux.d-flex.justify-content-center
      <iframe frameborder="0" class="juxtapose" width="80%" height="722" src="https://cdn.knightlab.com/libs/juxtapose/latest/embed/index.html?uid=dfb199c6-11d7-11ec-abb7-b9a7ff2ee17c"></iframe>
    p.mb-5 “Es la manipulación, a través de programas de edición gráfica, de imágenes capturadas o previamente diseñadas, con la intención de reforzar conceptos o mensajes mediante la modificación del color, formas, composición, contrastes, estilo, etcétera. La edición para hacer <i>collages</i> o mejorar la calidad de la imagen, es también un recurso de gran valor en publicidad; gracias a ello, se pueden exagerar o disminuir rasgos o elementos de todo tipo” (Viveros, 2005) El programa donde se hace el tratamiento es un editor de imágenes que ofrece opciones de edición, herramientas, efectos y modificación en el formato al guardar el archivo.
    Separador
    .titulo-sexto.color-primario(data-aos="fade-right")
      h4.mb-0
        spam.bg--4.p-1
          | Aspectos de la edición de imágenes
    p.mb-5 El tratamiento o edición de la imagen digital comprende aspectos creativos y herramientas técnicas, explicados a continuación:
    AcordeonB.mb-5(tipo="b" clase-tarjeta="tarjeta")(data-aos="zoom-in-up") 
      .row(titulo="Aspectos Creativos")
        .col-md-4
          figure
            img(src='@/assets/curso/36.jpg', alt='Texto que describa la imagen')
        .col-md-8.mb-4.mb-md-0
          p El proceso de edición se refiere también a los aspectos conceptuales y creativos de los que se sirve quien realiza la edición. Lo conceptual determina las características semióticas de los productos, como el sentido-significación que se desea transmitir, la función que se espera realice, si acompaña a otros medios o tiene un rol principal, si es ilustrativa o descriptiva, etcétera. Asimismo, es deseable determinar el estilo que se desea manejar y se relaciona con el realismo o la figuración, entre otros aspectos (Viveros, 2005).
            br
            br
            |Estos aspectos fueron tratados ampliamente en el Componente Formativo “Diseño para contenidos digitales”, en el apartado de Diseño y se aplican de la misma manera para la creación, captura o edición de imágenes digitales. De esta manera, es necesario especificar la composición adaptada a entornos digitales y el retoque como aspecto propio de este mundo.
      
      .row(titulo="Composición Digital")
        .col-md-4
          figure
            img(src='@/assets/curso/37.jpg', alt='Texto que describa la imagen')
        .col-md-8.mb-4.mb-md-0
          p También denominada composición de efectos visuales, tiene que ver con la creación de imágenes digitales a partir de manipular y combinar elementos de diferentes fuentes o herramientas digitales, con el fin de generar piezas homogéneas que transmitan la sensación de unidad en la imagen resultante, independiente de que sean reales o no. 
      
      .row(titulo="Retoque Digital")
        .col-md-4
          figure
            img(src='@/assets/curso/38.jpg', alt='Texto que describa la imagen')
        .col-md-8.mb-4.mb-md-0
          p Pese a ser un proceso técnico que involucra el conocimiento de las herramientas del <i>software</i> que se use, es también un proceso creativo, puesto que el retoque puede llevar implícito significados que se quieren compartir con el receptor.  El retoque da la opción de manipular imágenes o fotografías  y  permite alterar el escenario, la luz, el color y la percepción de forma variada e ingeniosa para construir  una nueva imagen.
    Separador
    AcordeonC.mb-5(tipo="a" clase-tarjeta="tarjeta")(data-aos="zoom-in-up") 
      .row(titulo="Herramientas para la edición")
        p.mb-5 Tienen que ver con los <i>software</i> de tratamiento de imagen. El mercado ofrece múltiples opciones y se clasifican entre los editores para computador, celulares y editores online. 
        .row.justify-content-center.align-items-end
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/39.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Canva
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/40.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Crello
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/41.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Piktochart
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/42.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Adobe Spark
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/43.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Befunky
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/44.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Freepik
      .row(titulo="Para computador")
        p.mb-5 Suelen tener mayores funcionalidades, lo que se traduce en mejor desempeño, pero también ocupan espacio en el disco duro ya que son mucho más completos. Normalmente requieren conocimientos de la herramienta, incluso de diseño, así que se necesita conocimiento y experiencia en su manejo. Algunos editores de fotos para computadora son Adobe Photoshop, Corel Draw, Paint.net, GIMP.
        .row.mb-5.justify-content-center.align-items-end
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/45.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Adobe Ilustrator
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/46.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Gravit Designer
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/47.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center VSCO
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/48.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Adobe Indesign
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/49.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Afterlight
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/50.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Adobe Photoshop
        .row.mb-5.justify-content-center.align-items-end
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/51.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center SVG-Edit
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/52.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Snapseed 
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/53.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Vectr
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/54.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Inkscape
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/55.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Gimp
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/56.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Canva
        .row.mb-5.justify-content-center.align-items-end
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/57.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center PaintShop Pro 2019
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/58.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Lightroom
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/59.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Pixlr Editor
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/60.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Corel Draw
      .row(titulo="Para celulares")
        p.mb-5 Se crearon para sistemas operativos como Android e iOS; aunque también necesitan descargarse, sus funciones no necesitan mucho espacio de memoria. Esto los hace más limitados que un software de gran tamaño, pero con las ventajas de modificar una imagen en cualquier momento. Algunos de este tipo son: Photoshop Express, VSCO, Canva, entre otros.
        .row.mb-5.justify-content-center.align-items-end
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/39.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Canva
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/61.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center Adobe Photoshop
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/62.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center VSCO
      .row(titulo="Editores online")
        p.mb-5 No necesitan descargarse en dispositivos y muchos de ellos tienen versiones gratuitas, con funciones limitadas y un poco de publicidad en sus interfaces. Algunos son Canva o Photoshop Express en esta clasificación, además de Photo Fancy y PicMonkey.
        .row.mb-5.justify-content-center.align-items-end
          .col-lg-2
            .iconos-hover.h-100
              .contenedor_icono.p-4
                img(src='@/assets/curso/63.svg', alt='Texto que describa la imagen')
              hr.mt-0
              h5.text-center PicMonkey
    .bloque-texto-a.color-primario.p-4.p-md-5.mb-5(data-aos="zoom-in-up") 
      .row.m-0.align-items-center.justify-content-between
        .col-lg-4.mb-4.mb-lg-0: img(src='@/assets/curso/64.svg', alt='Texto que describa la imagen' style='width: 250px').m-auto
        .col-lg-8
          .bloque-texto-a__texto.p-4
            p A continuación se específica las herramientas gratuitas y con pago: 
            br
            h5 Gratuitos: 
            p VSCO PicsArtPhoto Lab, Lensa, Photoscape X, Paint.Net, GIMP, Adobe Photoshop Express, Krita, Canva, Pixlr, iPiccy, Fotor, Lensa.
            br
            h5 Pago: 
            p InPixio Photo Editor, Adobe Photoshop, PaintShop, píxelmator Pro, PhotoPlus, Lightroom, PhotoDirector, PicMonkey, Ribbet, Mextures, Touch Retouch y SKRWT
    Separador
    #t_1_2.titulo-segundo(data-aos="fade-right")
      h2 1.2  Edición de audio
    .row.mb-5
      .col-lg-6
        p Hace referencia a la posibilidad de manipular diferentes elementos sonoros, involucrando en el proceso un terminal computarizado y <i>software</i> específico, con el fin de integrar o generar sonidos nuevos o que se adapten a una necesidad específica.
          br
          br
          |Un sonido digital suele tener asociados una serie de condiciones y parámetros característicos entre los que se puede destacar: la tendencia a ser dinámicos, su capacidad de interactividad, su condición ubicua y su naturaleza versátil.
      .col-lg-6: img(src="@/assets/curso/65.jpg")
    .titulo-sexto.color-primario(data-aos="fade-right")
      h4.mb-0
        spam.bg--4.p-1
          | Formatos para la edición de audio 
    p.mb-5 Ahora es pertinente revisar los formatos de audio y conocer algunos <i>softwares</i> comúnmente utilizados para la edición de este tipo de recursos:
      br
      br
      | Según el uso y la utilidad, los formatos de audio se dividen en dos categorías. Una, los que se usan para almacenar archivos de audio en DD, memorias USB o dispositivos que permiten escuchar este tipo de archivos (MP3, WAV, AIFF) y otra los que se usan en servicios de transmisión online (OGG, FLAC, ALAC).
    .row.justify-content-center.mb-5
      .col-lg-10
        .tarjeta.bg--2-claro.flechas-slyder.p-4(data-aos="zoom-in-up") 
          SlyderA
            .row.p-4.align-items-center.justify-content-center
              .col-md-2
                figure
                  img(src="@/assets/curso/66.svg")           
              .col-md-8.mb-4.mb-md-0
                p MP3: formato de audio comprimido con pérdida más conocido. Al mismo tiempo es el más compatible con múltiples reproductores multimedia. Se caracteriza por la compresión de la secuencia del sonido, dando como resultado un archivo realmente pequeño, que normalmente ocupa la mitad del archivo original. Para conseguirlo, es necesaria la pérdida de determinados sonidos, que supuestamente no pueden ser escuchados por el oído humano.
            .row.p-4.align-items-center.justify-content-center
              .col-md-2
                figure
                  img(src="@/assets/curso/67.svg")           
              .col-md-8.mb-4.mb-md-0
                p WAV: formato sin compresión de datos creado por Microsoft e IBM. Es compatible con todos los programas reproductores de audio. Los archivos de formato WAV no son tan populares como los MP3 porque son de mayor tamaño, aunque de mejor calidad.
            .row.p-4.align-items-center.justify-content-center
              .col-md-2
                figure
                  img(src="@/assets/curso/68.svg")           
              .col-md-8.mb-4.mb-md-0
                p AIFF: Audio Interchange File Format, formato estándar de audio, desarrollado por Apple para almacenar datos de sonido en computadores Apple. Hoy en día los archivos WAV y AIFF son compatibles.
            .row.p-4.align-items-center.justify-content-center
              .col-md-2
                figure
                  img(src="@/assets/curso/69.svg")           
              .col-md-8.mb-4.mb-md-0
                p WMA: del inglés Windows Media Audio, es un formato de archivos musicales creados por Microsoft. Una de sus principales características está en que aquellos archivos que han sido comprimidos en formato WMA ocupan menos espacio que los MP3, lo que implica también la reducción de su calidad. Por tanto, se trata de un formato de compresión de audio con pérdida.
            .row.p-4.align-items-center.justify-content-center
              .col-md-2
                figure
                  img(src="@/assets/curso/70.svg")           
              .col-md-8.mb-4.mb-md-0
                p FLAC: del inglés Free Lossless Audio Codec, es un formato de archivos de audio, libre y abierto, cuyo objetivo es reducir el tamaño original sin perder calidad. FLAC se ha convertido en la competencia directa del formato WAV.
            .row.p-4.align-items-center.justify-content-center
              .col-md-2
                figure
                  img(src="@/assets/curso/71.svg")           
              .col-md-8.mb-4.mb-md-0
                p AAC: del inglés Advanced Audio Coding, es un formato de compresión con pérdida que está usando Apple como formato principal para los iPods y para su <i>software</i> iTunes. Es la versión de Apple del formato MP3. (Truesdell, 2007, p 516).
            .row.p-4.align-items-center.justify-content-center
              .col-md-2
                figure
                  img(src="@/assets/curso/72.svg")           
              .col-md-8.mb-4.mb-md-0
                p OGG: archivos de audio comprimidos, que por su tamaño pueden ser transmitidos vía WIFI. Adicionalmente puede contener video. No es compatible con dispositivos Apple o con sistema operativo iOS.
            .row.p-4.align-items-center.justify-content-center
              .col-md-2
                figure
                  img(src="@/assets/curso/73.svg")           
              .col-md-8.mb-4.mb-md-0
                p ALAC: del inglés Apple Lossless Audio Codec, es básicamente la alternativa de Apple al formato FLAC. Es el formato utilizado por iTunes para las transmisiones de Apple Music.
    p.mb-5 Algunos programas para edición de audio offline:
    //- .icons.d-flex
    //-   i.fab.fa-windows.m-1
    //-   i.fab.fa-android.m-1
    //-   i.fab.fa-apple.m-1
    //-   h5 
    .row.justify-content-center.mb-3(data-aos="zoom-in-up") 
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-3
            img(src="@/assets/curso/74.png" style='width: 324px').mb-2
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            h5 Windows
          p
            b Audacity: 
            | es un programa gratuito de código abierto para grabar y editar sonido.
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-3
            img(src="@/assets/curso/75.png" style='width: 324px')
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            h5 Windows
          p
            b Power Sound Editor: 
            | permite llevar a cabo avanzadas y poderosas tareas a partir de cualquier archivo en audio. Puede usarlo para grabar o editar sus archivos y mezclarlos con otras piezas de sonido.
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-3
            img(src="@/assets/curso/76.png" style='width: 324px').mb-2
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            h5 Windows
          p
            b Mp3DirectCut:  
            | programa que permite editar de forma rápida archivos comprimidos en mp3. Permitir realizar la edición de los archivos sin descomprimirlos.
    .row.justify-content-center.mb-3(data-aos="zoom-in-up") 
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-3
            img(src="@/assets/curso/77.png" style='width: 326px').mb-2
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            h5 Windows
          p
            b Music Editor Free:  
            | <i>software</i> de edición de música, ayuda a registrar y editar música y sonidos, permitiéndole crear o editar sus propias pistas musicales o archivos de audio. Al igual que la mayoría de las herramientas de este tipo permite cortar, copiar y pegar partes de la grabación y, de ser necesario, añadir efectos.
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-3
            img(src="@/assets/curso/78.png" style='width: 326px').mb-2
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            h5 Windows 98, XP y Vista
          p
            b Wavosaur: 
            | al tiempo que permite grabar audio, este programa permite editar archivos en formato wav o mp3. Cuenta con funciones como copiar, cortar, pegar. 
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-3
            img(src="@/assets/curso/79.png" style='width: 326px').mb-2
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            i.fab.fa-apple.m-1
            i.fab.fa-android.m-1
            h5 Windows, Mac OS X, iPhone, iPad y Android
          p
            b WavePad:  
            |  permite grabar y editar música, voz y archivos de audio. Puede realizar la mayoría de tareas básicas en lo que se refiere a edición de audios.
    .row.justify-content-center.mb-3(data-aos="zoom-in-up") 
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-3
            img(src="@/assets/curso/80.png" style='width: 326px').mb-2
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            h5 Windows
          p
            b Expstudio:  
            |  este programa cuenta con múltiples funciones para editar archivos de audio o música. La versión gratuita una vez finalizada la edición solo permite guardar los audios resultantes en formato wav o mp2.
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-3
            img(src="@/assets/curso/81.png" style='width: 326px').mb-2
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            h5 Windows
          p
            b DJ Audio Editor: 
            | herramienta de fácil uso, que le permite editar canciones y sonidos en una forma única y atractiva. Permite añadir cientos de efectos de sonido a los archivos de audio, incluso brinda la posibilidad de grabar desde varias fuentes de audio y exportar los archivos a los principales formatos de audio.
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-3
            img(src="@/assets/curso/82.png" style='width: 236px').m-auto
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            i.fab.fa-apple.m-1
            h5 Windows y Mac OS X
          p
            b Let 's make music: 
            | programa pensado principalmente para producir música con el computador. Incluye la creación de melodías y ritmos, sintetizar y mezclar sonidos y guardar de forma ordenada cada una de las melodías que se van creando. 
    .row.justify-content-center.mb-5(data-aos="zoom-in-up") 
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-3
            img(src="@/assets/curso/83.png" style='width: 326px').mb-2
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            i.fab.fa-apple.m-1
            h5 Windows y Mac OS X
          p
            b WaveSurfer: 
            | <i>software</i> de código abierto diseñado pensando en los usuarios: tanto en aquellos que tienen un conocimiento avanzado del tema, como aquellos que apenas están empezando. 
      .col-lg-4
        .tarjeta.bg--4-claro.p-4.h-100
          figure.mb-3.ajuste-img.p-1
            img(src="@/assets/curso/84.png" style="width: 96px").m-auto
          .icons.d-flex.mb-2.justify-content-center
            i.fab.fa-windows.m-1
            i.fab.fa-apple.m-1
            h5 Windows y Mac OS X
          p
            b Adobe Audition:
            | Aplicación en forma de estudio de sonido destinado a la edición de audio digital de Adobe Systems Incorporated que permite un entorno de edición mezclado de ondas multipista.

    Separador 
    #t_1_3.titulo-segundo(data-aos="fade-right")
      h2 1.3  Edición de video 
    .contenedor-fondo.p-5.mb-5
      h4 La edición de video requiere de la manipulación de varios elementos, en donde la unión de varias imágenes y la adición de efectos digitales, como música, efectos y textos, posibilitan tener un resultado de un producto listo, pero que requiere de una serie de conocimientos que se amplían en el video relacionado a continuación:
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/_RTfWHoFcZE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)       
    .titulo-sexto.color-primario(data-aos="fade-right")
      h4.mb-0
        spam.bg--4.p-1
          | La imagen en movimiento
    .row.mt-5 
      .col-12.col-lg-9
        p Son aquellas que pueden verse a través de medios audiovisuales y representan secuencias: cine, animación, vídeo, gif, etc. 
        p.mt-3 El movimiento de una imagen se produce cuando una sucesión de imágenes estáticas, llamadas fotogramas, son proyectadas a gran velocidad. Para que una imagen fija se perciba en movimiento se tienen que proyectar un mínimo de 16 imágenes por segundo, aunque para percibirlo como real, se graba y se proyecta a 24 fotogramas por segundo en el cine y a 25 en la televisión y el video.
    Separador
      .col-4.col-lg-3.offset-4.offset-lg-0
        figure  
          img(src="@/assets/curso/86.svg", alt="Texto que describa la imagen")
    .titulo-sexto.color-primario(data-aos="fade-right")
          h4.mb-0
            spam.bg--4.p-1
              | Aspectos de la edición de video
    h5 Narrativa audiovisual
    figure.mt-5
      img(src="@/assets/curso/89.jpg", alt="Texto que describa la imagen")
    p.mt-5 Las imágenes en movimiento, al igual que las imágenes fijas, asumen el espacio en dos dimensiones y componen la realidad mediante encuadres o planos fijos y puntos de vista o ángulos de visión. Las imágenes en movimiento tienen además la propiedad de trabajar con la dimensión del tiempo.
    p.mt-4 Los elementos narrativos de un producto audiovisual son:
    .row.mt-5
      .col-10.col-lg-8.offset-1.offset-lg-2
        .cajon.color-primario.bg-acento-botones-60.p-4.mb-4
          .h4 El fotograma
          p.mt-4 Unidad mínima en la que se divide una captura de imagen en movimiento. Es una imagen fija que, al sucederse con otras, produce una imagen en movimiento. Es equivalente a una fotografía.
    .row.mt-4
      .col-10.col-lg-8.offset-1.offset-lg-2
        .cajon.color-primario.bg-acento-botones-40.p-4.mb-4
          .h4 La secuencia
          p.mt-4 Es la manera como se narra de forma completa, una acción concreta. Aunque la acción sucede en diferentes lugares y momentos, se mantiene una línea argumental. Su duración depende de la importancia que tenga dentro del guion. La secuencia se compone de escenas y estas a su vez de planos. Existe un tipo de plano adaptado a la secuencia: el plano secuencia es un plano fijo o en movimiento que no tiene cortes y dura lo mismo que la secuencia que está capturando.
    .row.mt-4
      .col-10.col-lg-8.offset-1.offset-lg-2
        .cajon.color-primario.bg-acento-botones-20.p-4.mb-4
          .h4 La escena 
          p.mt-4 Se encarga de mostrar una acción que transcurre en un mismo tiempo y lugar. El paso de una escena a otra se da a través de cortes que pueden ser secos, si se pasa de una imagen a otra diferente; fundidos a negro cuando se oscurece la imagen hasta el negro o, fundido encadenado cuando se superpone paulatinamente a la siguiente escena. La escena se compone de tomas.
    .row.mt-4
      .col-10.col-lg-8.offset-1.offset-lg-2
        .cajon.color-primario.bg-acento-botones-10.p-4.mb-4
          .h4 La toma
          p.mt-4 Es la grabación obtenida de una acción o escena. Es habitual hacer varias tomas de una misma escena utilizando diferentes ángulos de visión o puntos de vista.
    Separador
    .titulo-sexto.color-primario(data-aos="fade-right")
          h4.mb-0
            spam.bg--4.p-1
              | Los planos en movimiento 
    
    
    
    p.mt-5 Surgen cuando la cámara hace un seguimiento del espacio y del movimiento de los personajes. Estos planos son, entre otros:
    .row.mt-5.justify-content-center
      .col-4.py-5.w-31.bg--4-claro.rounded-20-top
        figure
          img(src="@/assets/template/tema-1-92.svg", alt="Texto que describa la imagen").w-50.margin-0-auto
      .col-4.position-relative.w-31.mx-3.bg--4-claro.rounded-20-top
        figure(style="position:absolute; top:20%; left:2%;")
          img(src="@/assets/template/tema-1-93.svg", alt="Texto que describa la imagen").w-50.margin-0-auto
      .col-4.mx-0.position-relative.w-31.bg--4-claro.rounded-20-top
        figure(style="position:absolute; top:20%; left:2%;")
          img(src="@/assets/template/tema-1-94.svg", alt="Texto que describa la imagen").w-50.margin-0-auto    
    .row.mt-0.text-center.justify-content-center
      .col-4.borde-no-top.w-31.bg--4-claro.px-4.rounded-20-bot
        .h4 Travelin:
        p.mt-4.text-small Plano que describe la cámara al acompañar al personaje o elemento durante su desplazamiento de un lugar a otro. 
      .col-4.borde-no-top.w-31.mx-3.bg--4-claro.px-4.rounded-20-bot
        .h4 Panorámica o paneo:
        p.mt-4.text-small.mb-5 Plano que se obtiene al realizar un movimiento de cámara de derecha a izquierda para dar una visión general del espacio. 
      .col-4.mx-0.borde-no-top.w-31.bg--4-claro.px-4.rounded-20-bot
        .h4 Plano grúa:
        p.mt-4.text-small Plano que se capta al colocar la cámara sobre una grúa elevada para tomar la imagen cenital, desde lo alto y en todas las direcciones.
    p.mt-5 Racionero (2008) afirma que “los planos cinematográficos se clasifican según su tamaño y dependiendo de este tienen diferentes funciones y reciben distintos nombres”. Según las características de movimiento e imagen los planos se pueden clasificar en:
    .row.mt-5
      .col-10.offset-1
        SlyderC(:datos="datosSlyder1")
    Separador
    .titulo-sexto.color-primario(data-aos="fade-right")
          h4.mb-0
            spam.bg--4.p-1
              | Proceso de edición del video
    .row.mt-5
      .col-12.col-lg-6
        p Es el proceso mediante el cual se crea un producto audiovisual a partir de la selección y unión de fragmentos de vídeo y audio obtenidos previamente a través de un soporte digital (cámaras) Anteriormente se hablaba de dos formas de edición: analógica y digital, pero actualmente, la analógica está casi descontinuada y es la edición digital bajo la que se trabaja en todos los entornos en los que son necesarios los productos audiovisuales.
          br
          br
          |La parte final de la edición es la posproducción de imagen y audio. En ella se elaboran los efectos especiales, sobreimpresión de textos o animaciones, y en el audio, locuciones, efectos o bandas sonoras.

          br
          br
          |La edición es un proceso dispendioso que habitualmente había venido requiriendo de dos profesionales: el que define el concepto y el que utiliza el programa. Los cambios en el mercado y las competencias profesionales hoy en día han simplificado los procesos, con el apoyo también de la tecnología, y un mismo profesional debe estar en capacidad de elaborar un producto audiovisual de principio a fin.
      .col-6.offset-3.offset-lg-0.align-self-center
        figure
          img(src="@/assets/curso/87.jpg", alt="Texto que describa la imagen")
    .row.mt-5
      .col-10.col-lg-8.offset-1.offset-lg-2
        .bloque-texto-a.color-primario-invertido.azul--1.p-4.p-md-3.mt-4(data-aos="zoom-in-up") 
          .row.m-0.align-items-center.justify-content-between
            .col-lg-7
              .bloque-texto-a__texto.p-4
                .h4.mb-0 Herramientas técnicas para la edición de video
                p.mb-0 Al momento de iniciar la edición, es necesario contar con dos herramientas básicas para procesar el material “en bruto”, o sea, todo el material grabado por el dispositivo. Se trata del guion de montaje y el programa de edición.    
            .col-lg-5
              img(src="@/assets/curso/88.svg", alt="Texto que describa la imagen").w-50.margin-0-auto
    .row.mt-5
      .col-10.offset-1
        .bloque-texto-g.color-primario.azul--2.p-3.p-sm-4.p-md-4.mt-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/template/tema-1-104.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            .h4.d-block.mb-0 Guion técnico
            p.mb-0 Es el mismo documento que se utilizó en la etapa de grabación, pero que en la edición se constituye como un documento clave que consigna el orden en que se insertarán todos los elementos de la narrativa audiovisual; define cómo se une una escena con otra, los tipos de plano que contiene cada escena, las transiciones entre las escenas y las secuencias definidas. Además de las imágenes, consigna también los sonidos de cada escena y otro tipo de elementos gráficos como títulos o imágenes insertadas que contribuyan a dar sentido.
    Separador
    .titulo-sexto.color-primario(data-aos="fade-right")
          h4.mb-0
            spam.bg--4.p-1
              | Programas de edición
    p.mt-5 Al igual que para las imágenes estáticas, existe una amplia variedad de <i>software</i> con los cuales llevar a cabo el montaje de las imágenes de video. Los <i>software</i> más populares actualmente son los siguientes:
    .row.mt-5
      .col-10.offset-1
        SlyderD(:datos="datosSlyder2")

</template>

<script>
import AcordeonB from '@/components/AcordeonB.vue'
import AcordeonC from '@/components/AcordeonC.vue'
export default {
  name: 'Tema1',
  components: {
    AcordeonB,
    AcordeonC,
  },
  data: () => ({
    overFlag: '',
    datosSlyder1: [
      {
        titulo: 'Plano general',
        texto:
          'Ubica al espectador en el espacio donde sucede la acción y su objetivo es describir el entorno.',
        imagen: require('@/assets/template/tema-1-95.png'),
      },
      {
        titulo: 'Plano de detalle',
        texto:
          'Se usa para destacar elementos específicos que se consideren fundamentales para la acción que quiere presentarse.',
        imagen: require('@/assets/template/tema-1-96.png'),
      },
      {
        titulo: 'Plano entero',
        texto:
          'Está estrechamente relacionado con el plano general, la diferencia radica en que el centro de acción lo producen los personajes no el decorado.',
        imagen: require('@/assets/template/tema-1-97.png'),
      },
      {
        titulo: 'Plano americano',
        texto:
          '“Nació a partir de la necesidad del western, que en el plano medio tenía que incluir la pistola del <i>cowboy</i>. Este plano comprende, entonces, desde la pistola colgada debajo de la cintura hasta la cabeza entera del personaje”. ',
        imagen: require('@/assets/template/tema-1-98.png'),
      },
      {
        titulo: 'Plano medio',
        texto:
          'Este plano presenta desde la cintura hasta la cabeza del personaje.',
        imagen: require('@/assets/template/tema-1-99.png'),
      },
      {
        titulo: 'Primer plano',
        texto:
          '“Es el más expresivo, del cual se ha dicho es el reflejo del alma”. (Lourdes, 2000, p.56)',
        imagen: require('@/assets/template/tema-1-100.png'),
      },
      {
        titulo: 'Primerísimo primer plano',
        texto:
          'Este plano supone un acercamiento muy acentuado al rostro del personaje, va de debajo de los labios hasta las cejas.',
        imagen: require('@/assets/template/tema-1-101.png'),
      },
    ],
    datosSlyder2: [
      {
        titulo: 'Final Cut Pro (Mac): ',
        texto:
          'Programa de Apple que se ha convertido en uno de los referentes para la edición de vídeo de forma profesional.',
        imagen: require('@/assets/template/tema-1-105.png'),
      },
      {
        titulo: 'Adobe Premiere Pro (Windows y Mac):',
        texto:
          'Es una de las mejores alternativas profesionales para sacar el máximo rendimiento a la edición de vídeo. Pertenece a la familia de productos de Adobe Creative Suite. ',
        imagen: require('@/assets/template/tema-1-106.png'),
      },
      {
        titulo: 'Adobe After Effects (Windows y Mac):',
        texto:
          'Es un complemento para Adobe Premiere Pro que aunque requiere de un nivel algo avanzado, permite crear animaciones, gráficos 3D con movimiento y efectos para incluir en los vídeos dando un toque muy profesional.',
        imagen: require('@/assets/template/tema-1-107.png'),
      },
      {
        titulo: 'Avid Media Composer (Windows y Mac):',
        texto:
          'A pesar de no ser tan popular en los estudios de posproducción profesional de cine y televisión es muy usado por su dinámico flujo de trabajo. ',
        imagen: require('@/assets/template/tema-1-108.png'),
      },
      {
        titulo: 'Pinnacle Studio (Windows): ',
        texto: 'Es un <i>software</i> muy intuitivo y fácil de manejar.',
        imagen: require('@/assets/template/tema-1-109.png'),
      },
      {
        titulo: 'Sony Vegas Pro (Windows):',
        texto:
          'Potente <i>software</i> con una estética que sigue la línea de Sony. También tiene una versión llamada Movie Studio para usuarios no tan avanzados.',
        imagen: require('@/assets/template/tema-1-110.png'),
      },
      {
        titulo: 'Corel VideoStudio (Windows):',
        texto:
          'Una opción más a tener en cuenta entre los programas avanzados. Recientemente ha añadido la opción de capturar en vídeo la pantalla del ordenador, ideal para tutoriales.',
        imagen: require('@/assets/template/tema-1-111.png'),
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
  methods: {
    chBg(id) {
      this.overFlag = id
    },
    chBgTransparent() {
      this.overFlag = ''
    },
  },
}
</script>

<style lang="sass" scoped></style>
