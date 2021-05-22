<template>
  <div id="app">
    <div class="wrapper">
      <Hero />
      <Intro />
    </div>
    <OMnie />
    <Ksiazki />
    <Spotkania />
    <Media />
    <Terapia />
    <Kontakt />
    <Footer />
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import Intro from './components/Intro.vue'
import OMnie from './components/OMnie.vue'
import Ksiazki from './components/Ksiazki.vue'
import Spotkania from './components/Spotkania.vue'
import Media from './components/Media.vue'
import Terapia from './components/Terapia.vue'
import Kontakt from './components/Kontakt.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Hero, Intro, OMnie, Ksiazki, Spotkania, Media, Terapia, Kontakt, Footer
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;600");

* {
  box-sizing: border-box;
}
body {
  font-family: Montserrat, sans-serif;
  margin: 0;
  padding: 0;
}

.wrapper {
  width: 100%;
  position: relative;
  min-height: 100vh;
  margin: 0;
  padding: 0;
}
</style>
