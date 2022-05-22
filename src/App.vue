<template>
  <div id="app">
    <img class="ig" alt="Vue logo" src="https://www.meishujixun.com/uploads/03ce09f04af9c2d5b82e79fd41318af5.jpg">
    <HelloWorld message="Chen&Wan blog"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Moments from './components/Moments.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Moments
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

.ig {
  height:300px;
  margin-bottom:0px;
}
</style>
