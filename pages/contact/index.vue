<template>
  <div>
    <h1>This is the Contact Page</h1>
    <nuxt-link to="/">Back Home</nuxt-link>
  </div>
</template>

<script>
export default {
  layout: 'other',
  transition: false,
  beforeMount () {
    console.log('before mounting the Contact Page')
  }
}
</script>
