<template>
  <div id="app">
    "It'll be 404 page. please wait..."

    404 NOT FOUND
    <img alt="404 image character." src="./assets/Scarecrow.png">
    I have bad news for you

    <br/>
    The page you are looking for might be removed or is temporarily unavailable

    <button>BACK TO HOMEPAGE</button>

    Your name @ DevChallenges.io
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

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
