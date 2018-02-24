<template>
  <div id="app">
    <h1>{{ msg }}</h1>
    <Home/>
  </div>
</template>

<script>
import Home from './components/Home'

export default {
  name: 'app',
  components: {
    Home
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App!'
    }
  }
}
</script>

<style lang="css">
  #app {
    color: #56b983;
  }
</style>