<template>
  <div>
    <Header />

    <about-me />
    <java-script />
    <vue-page />
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import AboutMe from '~/components/pages/AboutMe.vue'
import JavaScript from '~/components/pages/JavaScript.vue'
import VuePage from '~/components/pages/VuePage.vue'

export default {
  components: {
    Header,
    AboutMe,
    JavaScript,
    VuePage
  }
}
</script>

<style></style>
