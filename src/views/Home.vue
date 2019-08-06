<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App" color="blue" border="true"/>
    <HelloWorld msg="sfasfasf" color="red" border="true"/>
    <HelloWorld msg="34yh34yh34y3" color="yello" border="false"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
