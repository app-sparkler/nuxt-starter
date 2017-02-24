<template>
<div>
  This is the Contacts Page
  <br>
  <nuxt-link to="/">
    To Home
  </nuxt-link
</div> 
  
</template>

<script>
export default {
  layout: 'other',
  beforeMount () {
    console.log('before Mounting the Contact Page')
  }
}
</script>
