<template>
  <Home msg="Nick Dongoske"/>
  <Image/>
  <Links/>
  <Navigation/>
</template>

<script>
import Home from './components/Home.vue'
// import About from './components/About.vue'
import Image from './components/Image.vue'
import Links from './components/Links.vue'
import Navigation from './components/Navigation.vue'

export default {
  name: 'App',
  components: {
    Home,
    // About,
    Image,
    Links,
    Navigation,
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
