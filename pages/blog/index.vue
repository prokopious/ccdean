<template>
  <div>
    <h1></h1>
    <h2 class="subtitle">
      We build affordable, low-profile fencing to protect your landscaping from
      whitetail deer and other nuisance species in Lynchburg, VA. 
    </h2>
    <div class="phone">703-963-8546</div>
<nuxt-link to="/">HOME</nuxt-link>

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
  margin: 10;
  
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.phone {
  font-size: 40px;
  color: rgb(255, 255, 10);
}

.title {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  display: block;
  padding-bottom: 30px;
  font-weight: bold;
  
  font-size: 2.3rem;
 margin-bottom: 0px;
  padding-bottom: 0px;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  color: rgb(238, 238, 248);
  padding: 30px;
  font-size: 1.5rem;
padding-top: 0px;
  word-spacing: 5px;
  margin: 0px;
  padding-bottom: 5px;
  
}
a {
  font-weight: bold;
  color: rgb(242, 251, 208);
  font-size: 50;
  padding-top: 25px;
 
  padding: 7px;
}
.deploy-button {
  margin-top: 1rem;
}
</style>
