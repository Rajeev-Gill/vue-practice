<template>
  <div id="app">
    <!-- <HelloWorld msg="This is a prop of the component HelloWorld.vue"/>
    <Stonx msg="This is Jeevos Stonx component" />
    <Tard msg="NGGGHHHHHGEEEENEHHFHHGGHH"/> -->
    <Todos v-bind:todos="todos" />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import Stonx from './components/Stonks'
// import Tard from './components/Tard'
import Todos from './components/Todos'

export default {
  name: 'App',
  components: {
    //HelloWorld
    // Stonx,
    // Tard
    Todos
  },
  data() {
    return {
      todos: [
        {
          id: 1,
          title: "Todo 1",
          completed: false
        },
        {
          id: 2,
          title: "Todo 2",
          completed: false
        },
        {
          id: 3,
          title: "Todo 3",
          completed: false
        }
      ]
    }
  }
}
</script>

<style>

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.4;
}

</style>
