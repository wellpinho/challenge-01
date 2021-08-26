<template>
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-4">
          <h4>{{ sectionOne[0] }}</h4>
          <p>{{ sectionOne[1] }}</p>
        </div>
        <div class="col-2">
          <h4>{{ sectionTwo[0] }}</h4>
          <a href="#">{{ sectionTwo[1] }}</a>
        </div>
        <div class="col-2">
          <h4>{{ sectionThree[0] }}</h4>
          <a href="#">{{ sectionThree[1] }}</a> 
          <br>
          <a href="#">{{ sectionThree[2] }}</a>
        </div>
        <div class="col-2">
          <h4>{{ sectionFour[0] }}</h4>
          <a href="#">{{ sectionFour[1] }}</a> 
          <br>
          <a href="#">{{ sectionFour[2] }}</a>
          <br>
          <a href="#">{{ sectionFour[3] }}</a>
        </div>
        <div class="col-2">
          <h4>{{ sectionFive[0] }}</h4>
          <a href="#">{{ sectionFive[1] }}</a>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      sectionOne: [
        'spense.',
        'Spense is an open platform for individuals to share their infiltered thoughts. Discuss the topics you love, and get paid for doing just that.'
      ],
      sectionTwo: [
        'Sitemap',
        'Homepage'
      ],
      sectionThree: [
        'Support',
        'Contact',
        'FAQ'
      ],
      sectionFour: [
        'Company',
        'About',
        'Customers',
        'Blog'
      ],
      sectionFive: [
        'Opportunities',
        'Jobs'
      ]
    }
  },
}
</script>

<style scoped>
  footer {
    height: 10rem;
    background-color: black;
    color: #fff;
    padding-top: 1.5rem;
  }

  p {
    font-size: .8rem;
  }
  p, a {
    color: rgb(99, 96, 96);
  }
</style>