<template>
  <div id="app">
    <my-header></my-header>
  </div>
</template>

<script>
  import Header from './components/my-header.vue'

  export default {
    name: 'App',
    components: {
      'my-header': Header
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
