<template>
  <div id="app">
    <Navbar />
  </div>
</template>

<script>
import Navbar from './components/navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar
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
  }
</style>
