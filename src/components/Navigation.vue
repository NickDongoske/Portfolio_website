<template>
  <div id="navigation">
    <ul>
      <li>
        <router-link class="nav-link" to="/about">About</router-link>
        <!-- <button id="about-btn" -->
      </li>
      <br>
      <!-- <li>Fun</li> -->
    </ul>
  </div>
  
</template>


<script>
export default {
  name: 'Navigation'
}
</script>


<style scoped>
  ul {
    display: flex;
    /* flex-wrap: wrap; */
    justify-content: center;
    list-style-type: none;
    padding-left: 0;
  }

  li:hover {
    cursor: pointer;
    
  }
  
</style>