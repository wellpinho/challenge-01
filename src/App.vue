<template>
  <div id="app">
    <Navbar />
    <SectionIntro />
    <Partiners />
    <SectionApp />
    <SectionMidia />
    <Footer />
  </div>
</template>

<script>
import Navbar from './components/navbar.vue'
import SectionIntro from './components/Section-intro.vue'
import Partiners from './components/Section-partiners.vue'
import SectionApp from './components/Section-app.vue'
import SectionMidia from './components/Section-midia.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    SectionIntro,
    Partiners,
    SectionApp,
    SectionMidia,
    Footer 
  }
}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  body {
    font-size: 62.5%;
    font-size: 100%;
    font-family: 'Cabin', sans-serif;
    background-color: #E9ECEF;
    overflow-x: hidden;
  }

  .btn-dark {
    background-color: rgba(0, 0, 0, 0.932);
    border: none;
  }
</style>
