<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/4V095PQU06Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    figure.mt-5
      img(src="@/assets/curso/0.jpg", alt="Personas con dispositvos electronicos")
    p.mt-5 El programa de formación técnica en Integración de Contenidos Digitales pretende otorgar al aprendiz SENA los conocimientos necesarios para desarrollar estrategias de planeación y producción de contenidos digitales y multimedia que las Mipymes del país requieren en el contexto de la cuarta revolución industrial. A continuación, le invitamos a visualizar el video de introducción frente a este tema:
    
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
