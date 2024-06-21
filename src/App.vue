<template>
  <div class="container">
    <div class="row">
      <FriendS />
    </div>

  </div>
</template>

<script>
/* import HelloWorld from './components/HelloWorld.vue' */
import FriendS from './components/Friends.vue'

export default {
  name: 'App',
  components: {
    FriendS
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


</style>
