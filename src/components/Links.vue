<template>
  <section class="links">
    <a href="https://www.github.com/nickdongoske"><img class="img-link" src="../assets/github-logo.png"></a>
    <a href="https://www.linkedin.com/in/nicholas-dongoske-7b03a7157/"><img class="img-link" src="../assets/linkedin-logo.png"></a>
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