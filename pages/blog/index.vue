<template>
  <div>
    <h1>Deer Fences</h1>
    <h2 class="subtitle">
      We build affordable, low-profile fences to protect your landscaping from
      whitetail deer and other nuisance species. Quick fixes simply don't work
      against adaptable urban wildlife. Consider an old-fashioned fence and go
      to bed knowing that your hard work is safe.
    </h2>
    <div class="phone">703-963-8546</div>
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
}

.title {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  display: block;
  padding-bottom: 30px;
  font-weight: bold;
  
  font-size: 2.7rem;
 margin-bottom: 0px;
  padding-bottom: 0px;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  padding: 30px;
  font-size: 2rem;
padding-top: 0px;
  word-spacing: 5px;
  margin: 0px;
  padding-bottom: 5px;
  
}
a {
  font-weight: bold;
  color: rgb(97, 26, 26);
  font-size: 50;
  padding-top: 5px;
 
  padding: 7px;
}
.deploy-button {
  margin-top: 1rem;
}
</style>
