<template>
  <div>
      <h1>{{msg}}</h1>
      <img alt="Tard meem" src="../assets/tard.jpg">
  </div>
</template>

<script>
export default {
  name: "Tard",
  props: {
      msg: String
  }
};
</script>

<style>
</style>