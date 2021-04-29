<template>
  <button @click="play" ><img src="../assets/playbutton2.jpg"></button>
</template>

<script>
import useSound from 'vue-use-sound'
import buttonSfx from '/Users/nicholasdongoske/jobsearch/portfolio-website/src/assets/warthog.mp3'

export default {
  setup() {
    const [play] = useSound(buttonSfx)

    return {
      play,
    }
  },
}
</script>

<style scoped>
img {
  height: 100px;
  width: 100px;
  margin: 0px;
}

button:focus {
  outline: none;
}
img {
    height: 100px;
    width: 100px;
    
  }
  
img:hover {
    cursor: pointer;

  }
</style>

