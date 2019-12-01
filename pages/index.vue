<template>
  <div>
    <Header />

    <about-me />
    <java-script />
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import AboutMe from '~/components/pages/AboutMe.vue'
import JavaScript from '~/components/pages/JavaScript.vue'

export default {
  components: {
    Header,
    AboutMe,
    JavaScript
  }
}
</script>

<style></style>
