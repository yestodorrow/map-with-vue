<template>
  <div id="app">
    <Header></Header>
    <Gaode></Gaode>
  </div>
</template>

<script>
import Gaode from './components/gaode'
import Header from './components/header'
export default {
  name: 'App',
  components: {
    Header,Gaode
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
