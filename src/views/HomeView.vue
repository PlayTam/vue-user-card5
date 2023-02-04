<template>
  <div class="home">
    <HelloWorld/>
    <img src = "../assets/off.png" alt="">
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>
