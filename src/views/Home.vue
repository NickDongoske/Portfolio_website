<template>
  <div class="home">
    <HelloWorld msg="Nick Dongoske"/>
    <Image/>
    <Links/>
    <router-view/>
    <br>
  <div>
    <router-link style="text-decoration: none; color: inherit;" to="/about">About</router-link>
  </div>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/Home.vue'
import Image from '@/components/Image.vue'
import Links from '@/components/Links.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld,
    Image,
    Links
  }
}
</script>
