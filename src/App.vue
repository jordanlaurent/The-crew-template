<template>
<div id="app">
      <videotop/>
      <banniereTheChase/>
      <informations/>
  <Motorpass/>
  <disponible/>
  <diaporama/>
  <basdepage/>
</div>
</template>

<script>
import videotop from '@/components/videotop'
import Motorpass from '@/components/Motorpass'
import basdepage from '@/components/basdepage'
import banniereTheChase from '@/components/banniereTheChase'
import informations from '@/components/informations'
import disponible from '@/components/disponible'
import diaporama from '@/components/diaporama'
export default {
  name: 'app',
  components: {
    Motorpass,
    videotop,
    basdepage,
    banniereTheChase,
    informations,
    disponible,
    diaporama
  },
   created: function (){
    document.title = 'Laurent Jordan - the crew 2'
  }
}
</script>
<style scoped>
@font-face {
    font-family: 'Just_Dance_Font_Regular';
    src: url('assets/fonts/Just_Dance_Font_Regular.woff2') format('woff2'),
        url('assets/fonts/Just_Dance_Font_Regular.woff') format('woff'),
        url('assets/fonts/Just_Dance_Font_Regular.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
}
#app{top: 0;bottom: 0; position: absolute; background-color: black;}
p, h1,h2,h3,h4,h5,a,li {font-family: 'Just_Dance_Font_Regular';}
</style>