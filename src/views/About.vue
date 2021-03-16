
<template>
 <h1>About</h1>
 <br>
 <div>
  <Audio/>
  <router-view/>
  <router-link style="text-decoration: none; color: inherit;" to="/">Home</router-link>
 </div>
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
div {
  display: flex;  
  flex-direction: column;
}
button {
  border: none;
  background: none;
}
</style>
