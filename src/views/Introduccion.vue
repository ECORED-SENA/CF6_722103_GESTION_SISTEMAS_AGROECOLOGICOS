<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    p.mb-5(data-aos="fade-right") Le damos la bienvenida al componente formativo denominado #[span.txt-c1 “Planificación del manejo cultural en el agroecosistema”], en el siguiente video puede visualizar un breve resumen del componente:
    figure(data-aos="fade-left")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/AVV3sZxEnsA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
