<template>
  <div>
    <img src="https://www.linkpicture.com/q/unnamed_109.png" />
    
    <h1 class="title">WHITETAIL BARRIERS OF LYNCHBURG</h1>
    <h2 class="subtitle">Protect your Landscaping with Low-Profile Fencing</h2>

    <nuxt-link to="/blog">OUR SERVICES</nuxt-link>
    <div class="num">
      703-635-9598
    </div>
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
  background-color: #fff7f7;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: bold;
  font-size: 2.7rem;
  color: rgb(0, 0, 0);
  letter-spacing: 1px;
  margin-bottom: 0px;
  padding-bottom: 0px;
}

.num {
  font-size: 25px;
}

.subtitle {
  font-weight: 300;
  font-size: 2rem;
  color: rgb(0, 0, 0);
  word-spacing: 5px;
  padding-bottom: 15px;
  margin-top: 0px;
  padding-top: 0px;
}
a {
  font-weight: bold;
  color: rgb(243, 17, 17);
  font-size: 50;
  style: none;
}
.deploy-button {
  margin-top: 1rem;
}
</style>
