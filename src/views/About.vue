
<template>
 <h1>About</h1>
 <br>
  <div id="app">
    <button v-on:click="play" type="button">Click Me</button>
  </div>
   <router-view/>
  <router-link style="text-decoration: none; color: inherit;" to="/">Home</router-link>
  <Audio/>
</template>



<script>
import Audio from '@/components/Audio.vue'

export default {
  name: 'About',
  components: {
    Audio,
  }
}
</script>


<style scoped>
button {
  border: none;
  background: none;
}
</style>
