<template>
  <div id="app-container">
    <router-view />
  </div>
</template>

<script>
export default {
  name: 'App',
  data() {
    return {}
  }
}
</script>

<style scoped>
#app-container {
  width: 100%;
  height: 100vh;
}
</style>
