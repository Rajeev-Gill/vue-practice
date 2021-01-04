<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="This is a prop of the component HelloWorld.vue"/>
    <Stonx msg="This is Jeevos Stonx component" />
    <Tard msg="NGGGHHHHHGEEEENEHHFHHGGHH"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Stonx from './components/Stonks'
import Tard from './components/Tard'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Stonx,
    Tard
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
