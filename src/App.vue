<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hello></hello>
    <github></github>
  </div>
</template>

<script>
  import Hello from './components/Hello'
  import Github from './components/Github'

  export default {
    name: 'app',
    components: {
      Hello,
      Github
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
  a {
    color: #097af1;
  }
</style>
