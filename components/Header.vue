<template>
  <div>
    <b-navbar toggleable="md" type="dark" variant="info">
      <b-navbar-brand>岩原 公貴 Portfolio Site</b-navbar-brand>

      <b-navbar-toggle target="nav-collapse" />

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item to="/">about me</b-nav-item>
          <b-nav-item href="#">JavaScript</b-nav-item>
          <b-nav-item href="#">Vue.js</b-nav-item>
          <b-nav-item href="#">Nuxt.js</b-nav-item>
          <b-nav-item href="#">Node.js</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {}
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
