<template>
  <div id="app">
    <aaa />
    <login />
  </div>
</template>

<script>
import aaa from './components/AAA'
import login from './pages/login'

export default {
  name: 'App',
  components: {
    aaa,
    login
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
