<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->

 <navbar/>
</template>

<script>
import login from "../src/components/Login"
import navbar from "../src/components/Deshboard"
export default {
  name: 'App',
  components: {
   login,
   navbar,
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
