<template>
  <div>
    <Header />
    <about-me />
    <java-script />
    <vue-page />
    <node-page />
    <cost-app-page />
  </div>
</template>

<script>
import Header from '~/components/Header.vue'
import AboutMe from '~/components/pages/AboutMe.vue'
import JavaScript from '~/components/pages/JavaScript.vue'
import VuePage from '~/components/pages/VuePage.vue'
import NodePage from '~/components/pages/NodePage.vue'
import CostAppPage from '~/components/pages/CostAppPage.vue'

export default {
  components: {
    Header,
    AboutMe,
    JavaScript,
    VuePage,
    NodePage,
    CostAppPage
  }
}
</script>

<style></style>
