<template>
  <div id="app">
      <LOGIN />
  </div>
</template>

<script>
import LOGIN from './pages/login'

export default {
  name: 'App',
  components: {
    LOGIN
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
