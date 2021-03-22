<template>
  <button @click="play" ><img src="../assets/playbutton2.jpg"></button>
</template>

<script>
import useSound from 'vue-use-sound'
import buttonSfx from '/Users/nicholasdongoske/jobsearch/portfolio-website/src/assets/portfolio-fart.mp3'

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
button {
  margin: 0px;
  padding: 0px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    border: none;
}
button:active {
    outline: none;
    border: none;
    box-shadow: none;
    outline: none !important;
}
img {
    height: 100px;
    width: 100px;
    
  }
  
img:hover {
    cursor: pointer;

  }
</style>

