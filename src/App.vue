<template>
  <div id="app">
    <img alt="Vue logo" src="https://p.kindpng.com/picc/s/343-3433067_transparent-sanrio-png-cinnamoroll-png-download.png">
    <HelloWorld message="Chen&Wan blog"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Moments from './components/Moments.vue'
export default {
  name: 'App',
  components: {
    HelloWorld
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
