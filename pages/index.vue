<template>
  <div>
    <b-navbar toggleable="md" type="dark" variant="info">
      <b-navbar-brand>岩原 公貴 Portfolio Site</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse" />

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item v-scroll-to="'#aboutme'" to>about me</b-nav-item>
          <b-nav-item v-scroll-to="'#javascript'" to>JavaScript</b-nav-item>
          <b-nav-item v-scroll-to="'#vue'" to>Vue.js</b-nav-item>
          <b-nav-item v-scroll-to="'#nuxt'" to>Nuxt.js</b-nav-item>
          <b-nav-item v-scroll-to="'#node'" to>Node.js</b-nav-item>
          <b-nav-item v-scroll-to="'#develop'" to>個人開発</b-nav-item>
          <b-nav-item v-scroll-to="'#others'" to>Others</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
    <about-me id="aboutme" />
    <java-script id="javascript" />
    <vue-page vue-id="vue" nuxt-id="nuxt" />
    <node-page id="node" />
    <cost-app-page id="develop" />
    <others id="others" />
    <Footer />
  </div>
</template>

<script>
// import Header from '~/components/Header.vue'
import AboutMe from '~/components/pages/AboutMe.vue'
import JavaScript from '~/components/pages/JavaScript.vue'
import VuePage from '~/components/pages/VuePage.vue'
import NodePage from '~/components/pages/NodePage.vue'
import CostAppPage from '~/components/pages/CostAppPage.vue'
import Others from '~/components/pages/Others.vue'
import Footer from '~/components/Footer.vue'

export default {
  components: {
    // Header,
    AboutMe,
    JavaScript,
    VuePage,
    NodePage,
    CostAppPage,
    Others,
    Footer
  }
}
</script>

<style scoped>
b-navbar {
  max-width: 1200px;
}
.navbar-collapse {
  flex-grow: 0;
  margin: 0 0 0 auto;
}

.nav-link {
  font-weight: bold;
}
</style>
