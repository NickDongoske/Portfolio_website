<template>
  <section class="links">
      <!-- <a href="https://www.instagram.com/davidattenborough/"><img class="img-link" src="../assets/ig-logo-2.jpg"></a> -->
      <a href="https://www.github.com/nickdongoske"><img class="img-link" src="../assets/github-logo.png"></a>
      <a href="https://www.linkedin.com/in/nicholas-dongoske-7b03a7157/"><img class="img-link" src="../assets/linkedin-logo.png"></a>
      <!-- <img class="img-link" src="../assets/youtube-logo3.png"> -->
     <a href="https://open.spotify.com/playlist/37i9dQZF1Epm7B2mUsVALv?si=4Peei9aIQpilJ94d9O2dMQ"><img class="img-link" src="../assets/spotify-logo.svg" v=""></a>
  </section>
</template>

<script>
export default {
  name: 'Link'
  }
</script>

<style scoped>
.links {
    display: flex;
    flex-direction: row;
    justify-content: center;
}

.img-link {
    height: 100px;
    width: 100px;
  }
.img-link:hover {
    cursor: pointer;

  }
  
/* .poop {
    height: 100px;
    width: 100px;
    padding: 0;
    margin: 0;
  } */
  

</style>