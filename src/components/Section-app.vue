<template>
  <div class="section-app">
    <div class="container">
      <div class="row">
        <div class="col-2"></div>
        <span class="jumbotron">
          <div class="col-4">
            <h2>{{ heading }}</h2>
            <p>{{ subheading }}</p>
            <a href="#">{{ link }} <i class="fas fa-long-arrow-alt-right"></i></a>
          </div>
          <div class="col-4">
            <img class="img-fluid" src="./../assets/large-phone.png" alt="">
          </div>
        </span>
        <div class="col-2"></div>
      </div>
    </div>
  </div>  
</template>

<script>
export default {
  data() {
    return {
      heading: 'Secure your money with Escrow.',
      subheading: 'Spense uses Escrow to secure all payments. We believe Escrow offers the highest level of security for your payments, so you never need to worry about scams.',
      link: 'Learn more about Escrow'
    }
  },
}
</script>

<style scoped>
  .section-app {
    height: 100vh;
    margin-top: -1rem;
    background-color: #fff;
    padding-top: 2rem;
  }

  .jumbotron {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 0 1rem;
  }

  h2 {
    font-weight: 600;
    font-size: 2.3rem;
  }
</style>