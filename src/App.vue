<template>
  <div id="app">
    <Header/>
    <img alt="404 image character." src="./assets/Scarecrow.png">
    I have bad news for you
    <br/>
    The page you are looking for might be removed or is temporarily unavailable

    <button>BACK TO HOMEPAGE</button>
    <Footer/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    // HelloWorld
    Header,
    Footer
  }
}
</script>

<style>
img {
  position: absolute;
  left: 5.35%;
  right: 57.21%;
  top: 24.54%;
  bottom: 34.03%;
  max-width:539.22px;
  max-height:447.43px;
}
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>
