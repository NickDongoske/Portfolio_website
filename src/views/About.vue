
<template>
 <h2>Just a young warthog</h2>
 <h3>(Who enjoys coding)</h3>
 <br>
 <a href="https://open.spotify.com/playlist/37i9dQZF1Epm7B2mUsVALv?si=4Peei9aIQpilJ94d9O2dMQ"><img class="img-link" src="../assets/spotify-logo.svg" v=""></a>
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
img {
  height: 100px;
  width: 100px;
}

div {
  display: flex;  
  flex-direction: column;
  justify-content: center;
}
button {
  border: none;
  background: none;
}
</style>
