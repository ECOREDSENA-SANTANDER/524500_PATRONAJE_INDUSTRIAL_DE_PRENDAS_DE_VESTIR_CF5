<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row
        .col-md-7.p-5
          p En la actualidad,  el sector confección, diseño y moda está haciendo la transición a nivel país en la preparación y capacitación de mano de obra calificada y tecnología versátil que aporte al estándar competitivo internacional, con la que busca dar una respuesta rápida y eficaz a las exigencias del mercado; en este aspecto el patronista juega un papel fundamental, pues debe estar preparado para interpretar los bocetos, sketch y diseños asignados por el diseñador, cumpliendo a cabalidad con los procesos de producción o prototipado necesarios.   
        .col-md-5.align-items-center
          img(src='@/assets/curso/temas/introduccion/imagen1.svg', alt='Modisto en un taller')
    
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
