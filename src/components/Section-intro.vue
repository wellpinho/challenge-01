<template>
  <div class="jumbotron">
    <div class="container">
      <div class="row">
        <div class="col-7 align-self-center">
          <h1>{{ title }}</h1>
          <h6>{{ subTitle }}</h6>
          <ul>
            <li>
              <i class="fas fa-check-circle"></i>
                <span class="ml-2">{{list[0]}}</span>
            </li>
            <li>
              <i class="fas fa-check-circle"></i>
                <span class="ml-2">{{list[1]}}</span>
            </li>
            <li>
              <i class="fas fa-check-circle"></i>
                <span class="ml-2">{{list[2]}}</span>
            </li>
          </ul>

          <form class="form-inline">
            <div class="form-group mb-2 mr-2">
              <label for="inputPassword2" class="sr-only">Senha</label>
              <input type="password" class="form-control" id="inputPassword2" placeholder="john@example.com">
            </div>
            <button type="submit" class="btn btn-dark mb-2">Get Started</button>
          </form>

        </div>
        <div class="col-1"></div>
        <div class="col-4">
          <img class="img-fluid" src="./../assets/hero-large.png" alt="">
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'SectionIntro',
  data() {
    return {
      title: 'Share your infiltered thoughts. Get paid.',
      subTitle: `Spense is an open platform for individuals to share their unfiltered thoughts.
                  Discuss the topics you love, and get paid for doing just that.`,
      list: [
        'Receive 99% off the earnings.',
        'Get paid via Debit Card, ACH, or PayPal.',
        'Whithraw your earnings anytime.'
      ]
    }
  }
}
</script>

<style scoped>
  ul {
    list-style: none;
  }
  h1 {
    font-weight: 600;
    font-size: 3.5rem;
  }


</style>