<template>
  <div>
    <Header></Header>
    <nuxt/>
    <a href="https://nuxtjs.org/" target="_blank" class="button--green">Documentation</a>
  </div>
</template>

<script>
import Header from '../components/public/header'
export default {
  components: {
    Header
  }
}
</script>

<style scoped>
</style>
