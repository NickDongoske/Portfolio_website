<template>
  <button @click="play">Click Me</button>
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