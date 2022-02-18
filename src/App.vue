<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <h1>Form with checkbox and radio button in vue js</h1>
    <sign-up />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import SignUp from './components/SignUp.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    SignUp
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


