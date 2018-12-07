<template>
  <div>
    <geo></geo>
    <nav/>
    <user></user>

  </div>
</template>

<script>
import geo from './geo.vue'
import nav from './nav.vue'
import user from './user.vue'
export default {
  components: {
    geo,
    nav,
    user
  }
}
</script>

<style scoped>
</style>
