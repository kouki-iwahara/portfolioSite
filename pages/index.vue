<template>
  <div>
    <Header />
    <div class="wrapper">
      <about-me />
    </div>
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import AboutMe from '~/components/pages/AboutMe.vue'

export default {
  components: {
    Header,
    AboutMe
  }
}
</script>

<style></style>
