<template>
  <div class="home">
    <img alt="Vue logo" class="img-01" src="https://i.postimg.cc/3xWQgxvk/wp7453736.jpg">
    <HelloWorld msg="Welcome To My Portfolio"/>
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

<style scoped>
 
.img-01 {
  width: 100%;
  background-attachment: fixed;
  box-shadow: black 6px 6px 12px 12px;
}

</style>
