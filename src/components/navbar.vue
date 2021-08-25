<template>
    <nav class="navbar navbar-expand-lg navbar-light">
      <div class="container">
        <a class="navbar-brand" href="#">spense.</a>
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#conteudoNavbarSuportado" aria-controls="conteudoNavbarSuportado" aria-expanded="false" aria-label="Alterna navegação">
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="conteudoNavbarSuportado">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item">
              <a class="nav-link" href="#">{{menus[0]}}</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">{{ menus[1]}}</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">{{menus[2]}}</a>
            </li>
          </ul>
          <span class="navbar-nav">
            <li class="nav-item">
                <a class="nav-link" href="#">{{menus[3]}}</a>
            </li>
          </span>
          <button class="btn btn-dark my-2 my-sm-0" type="submit">Get Started</button>
        </div>
      </div>
    </nav>
</template>

<script>

export default {
  name: 'Navbar',
  props: {
    msg: String
  },
  data() {
    return {
      menus: [
        'Business',
        'Pricing',
        'Features',
        'Login'
        ]
    }
  }
}
</script>

<style scoped>
  .mr-auto, .mx-auto {
    margin-left: auto;
  }

  .navbar {
    position: fixed;
    width: 100%;
    z-index: 9998;
    background-color: #E9ECEF;
  }
  .navbar-light .navbar-nav .nav-link {
    color: rgba(0, 0, 0, .9);
  }
</style>
