<template>
  <section class="container">
    <img src="../assets/img/logo.png" alt="Nuxt.js Logo" class="logo" />
    <h1 class="title">
      Universal Vue.js Application Framework
    </h1>
    
    <!-- ABOUT LINK-->
    <nuxt-link class="button" to="/about">
      About page
    </nuxt-link>
    
    <!-- CONTACT LINK-->
    <router-link class="button" to="/contact">
      Contact Page
    </router-link>

  </section>
</template>

<script>
export default {
  beforeMount () {
    console.log('before mounting the Home page')
  }
}
</script>

<style scoped>
.title
{
  margin: 50px 0;
}
</style>
