<template>
  <div>
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
  background-color: #424980;
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
  style: italic;
  font-size: 2.7rem;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  padding: 30px;
  font-size: 2rem;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
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
