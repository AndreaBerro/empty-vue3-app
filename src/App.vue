<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <Oui v-for="index in 200" :key="index"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Oui from "./components/Oui.vue"

export default {
  name: 'App',
  components: {
    HelloWorld,
    Oui
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
