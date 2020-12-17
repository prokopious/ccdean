<template>
  <div>
    <logo />
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
  background-color: #678198;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.num {
  font-size: 25px;
}

.title {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto,
    'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: bold;
  font-size: 2.7rem;
  color: black;
  letter-spacing: 1px;
  margin-bottom: 0px;
  padding-bottom: 7px;
}

.subtitle {
  font-weight: 300;
  font-size: 2rem;
  color: #293851;
  word-spacing: 5px;
  padding-bottom: 15px;
  margin-top: 0px;
  padding-top: 0px;
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
