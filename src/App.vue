<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <NewTitle />
    <Hero />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NewTitle from './components/NewTitle.vue'
import Hero from './components/Hero.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    NewTitle,
    Hero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
