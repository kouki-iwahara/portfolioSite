<template>
  <div class="container">
    <div class="header">
      <Header />
    </div>
  </div>
</template>

<script>
import Header from '~/components/Header.vue'

export default {
  components: {
    Header
  }
}
</script>

<style scoped>
.container {
  max-width: 1200px;
}
</style>
