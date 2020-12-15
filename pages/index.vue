<template>
  <div>
    <logo />
    <h1 class="title">WHITETAIL BARRIERS OF LYNCHBURG</h1>
    <h2 class="subtitle">Protect your Landscaping with Low-Profile Fencing</h2>
   <div class="phone">703-963-8546</div>
      <nuxt-link to="/blog">our services</nuxt-link>
  
     
    
   
  </div>
</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  },
  head() {
    return {
      script: [
        { src: 'https://identity.netlify.com/v1/netlify-identity-widget.js' }
      ]
    }
  }
}
</script>

<style>
.container {
  margin: 0 auto;
  background-color: #89b099;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.phone {
font-size: 40px;
}

.title {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: bold;
  font-size: 2.7rem;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 2rem;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 0px;
}
a {
  font-weight: bold;
  color: black;
  font-size: 50;
  style: none;
}
.deploy-button {
  margin-top: 1rem;
}
</style>
