<template>
  <div class="section-midia">
    <div class="contaner">
      <div class="row">
        <div class="col-2"></div>
        <div class="col-4">
          <img class="img-fluid" src="./../assets/text-editor.png" alt="">
        </div>
        <div class="col-4 align-self-center">
          <h2>{{ heading }}</h2>
          <p>{{ subHeading }}</p>
          <a href="#">{{ link }} <i class="fas fa-long-arrow-alt-right ml-2"></i></a>
        </div>
        <div class="col-2"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      heading: 'A text editor like no other.',
      subHeading: 'Our text editor pulls you info focus mode with it`s simplistic design and usability so you can put out your vest writings.',
      link: 'Text Editor Live Demo'
    }
  },
}
</script>

<style scoped>
  .section-midia {
    background-color: #fff;
  }

  a {
    display: flex;
    align-items: center;
    color: rgba(0, 0, 0, 0.719);
  }
</style>