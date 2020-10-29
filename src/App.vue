<template>
  <div id="app">
    <Header/>
    <div class="f-container">
      <div class="img-box">
        <img alt="404 image character." src="./assets/Scarecrow.png">
      </div>
      <div class="text-box">
        <div class="title">
          I have bad news for you
        </div>
        <div class="detail">
          The page you are looking for might be removed or is temporarily unavailable
        </div>
        <button>BACK TO HOMEPAGE</button>
      </div>
    </div>
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
.f-container{
  display:flex;
}
.img-box{
  flex-basis:43%;
}
.text-box{
  flex-basis:57%;
}
img {
  position: absolute;
  left: 5.35%;
  right: 57.21%;
  top: 24.54%;
  bottom: 34.03%;
  max-width:539.22px;
  max-height:447.43px;
}
.title{
  position: absolute;
  width: 586px;
  height: 190px;
  left: 735px;
  top: 265px;

  font-family: Space Mono;
  font-style: normal;
  font-weight: bold;
  font-size: 64px;
  line-height: 95px;
  letter-spacing: -0.035em;

  color: #333333;
}

.detail{
  position: absolute;
  width: 381px;
  height: 108px;
  left: 736px;
  top: 491px;

  font-family: Space Mono;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 36px;
  letter-spacing: -0.035em;

  color: #4F4F4F;
}
button{
  position: absolute;
  width: 216px;
  height: 68px;
  left: 740px;
  top: 663px;

  background: #333333;

  /* text style */
  /* position: absolute; */
  /* width: 130px;
  height: 21px;
  left: 783px;
  top: 687px; */

  font-family: Space Mono;
  font-style: normal;
  font-weight: bold;
  font-size: 14px;
  line-height: 21px;
  /* identical to box height */

  letter-spacing: -0.035em;
  text-transform: uppercase;

  color: #FFFFFF;
}
</style>
