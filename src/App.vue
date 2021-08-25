<template>
  <div id="app">
    <Navbar />
    <SectionIntro />
  </div>
</template>

<script>
import Navbar from './components/navbar.vue'
import SectionIntro from './components/Section-intro.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    SectionIntro
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
  }
</style>
