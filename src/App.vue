<template>
  <div id="app">
    <app-header/>
    <router-view/>
  </div>
</template>

<script>
import header from '@/components/header'
export default {
  name: 'App',
  components: {
    'app-header': header
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
