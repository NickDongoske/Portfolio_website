<template>
  <Header msg="Nick Dongoske"/>
  <About/>
  <Links />
</template>

<script>
import Header from './components/Header.vue'
import About from './components/About.vue'
import Links from './components/Links.vue'

export default {
  name: 'App',
  components: {
    Header,
    About,
    Links,
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
