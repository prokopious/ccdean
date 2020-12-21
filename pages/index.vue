<template>
  <div>
 <Gallery :imgs="[{src: 'https://picsum.photos/200/300', thumbnail: 'https://picsum.photos/200/300', w: 200, h: 300, alt: 'random picture from picsum.photos to demonstrate the vue-picture-swipe component', title: 'Some Picture'}, {src: 'https://picsum.photos/200/300', thumbnail: 'https://picsum.photos/200/300', w: 200, h: 300, alt: 'random picture from picsum.photos to demonstrate the vue-picture-swipe component', title: 'Some Picture'}]" />
    <img src="https://www.linkpicture.com/q/ezgif.com-gif-maker-5.webp" />

    
    <h1 class="title">WHITETAIL BARRIERS OF LYNCHBURG, VA</h1>
    <h2 class="subtitle">Protect your Landscaping from Nocturnal Raids</h2>

    <nuxt-link to="/blog">OUR SERVICES</nuxt-link>
    <div class="num">
      703-963-8546
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
  background-color: #2a3e8d;
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
  font-size: 1rem;
  color: rgb(255, 255, 255);
  letter-spacing: 1px;
  margin-bottom: 0px;
  padding-bottom: 0px;
}

.num {
  font-size: 35px;
  color: rgb(251, 255, 28);
}

.subtitle {
  font-weight: 300;
  font-size: 1rem;
  color: rgb(174, 180, 86);
  word-spacing: 5px;

  margin: 0px;
  padding-bottom: 5px;
}
a {
  font-weight: bold;
  color: rgb(238, 234, 234);
  font-size: 50;
  
  
  padding-top: 20px;
}
.deploy-button {
  margin-top: 1rem;
}
</style>
