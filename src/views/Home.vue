<template>
  <div class="home">
    <HelloWorld msg="Nick D"/>
    <Image/>
    <Links/>
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
