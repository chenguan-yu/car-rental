<template>
  <div id="app">

    <router-view/>
    <Index></Index>

  </div>
</template>

<script>
  import Index from './components/index/index'
  export default {
  name: 'App',
  components:{
    Index
  }
}
</script>

<style>
  @import "../static/css/common.css";
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
