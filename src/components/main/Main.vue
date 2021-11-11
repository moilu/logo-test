<template>
  <main >
      <hero />
      <social-media />
      <buttons />
      <marketing />
      <prices />
      <contact />
      <blog />
  </main>
</template>

<script>
import Hero from "../sub/Hero.vue"
import SocialMedia from "../sub/SocialMedia.vue"
import Buttons from "../sub/Buttons.vue"
import Marketing from "../sub/Marketing.vue"
import Prices from '../sub/Prices.vue'
import Contact from '../sub/Contact.vue'
import Blog from '../sub/Blog.vue'

export default {
  name: 'Main',
  components: {
    Hero,
    SocialMedia,
    Buttons,
    Marketing,
    Prices,
    Contact,
    Blog
  }
}
</script>

<style scoped>
  main {
    padding: 0 20px 0 20px;
    display: grid;
      justify-content: center;
  }

</style>>