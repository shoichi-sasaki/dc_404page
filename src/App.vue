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
#app{
  /* width:100%; */
}
.f-container{
  display:flex;
  flex-flow: row wrap;
  justify-content: space-around;
}
.img-box{
  flex-basis:43%;
}
.text-box{
  flex-basis:57%;
}
img {
  /* position: relative; */
  left: 10%;
  right: 57.21%;
  max-width:539.22px;
  max-height:447.43px;
}
.title{
  position: relative;
  width: 586px;
  height: 190px;

  font-family: Space Mono;
  font-style: normal;
  font-weight: bold;
  font-size: 64px;
  line-height: 95px;
  letter-spacing: -0.035em;

  color: #333333;
}

.detail{
  position: relative;
  width: 381px;
  height: 108px;
  top: 30px;

  font-family: Space Mono;
  font-style: normal;
  font-weight: normal;
  font-size: 24px;
  line-height: 36px;
  letter-spacing: -0.035em;

  color: #4F4F4F;
}
button{
  position: relative;
  width: 216px;
  height: 68px;
  top:80px;

  background: #333333;

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
@media screen and (max-width: 480px) {
	/* 480px以下に適用されるCSS（スマホ用） */
  img {
    width:286px;
    /* max-height:447.43px; */
  }
  .title{
    position: relative;
    width: 350px;
    height: 142px;

    font-family: Space Mono;
    font-style: normal;
    font-weight: bold;
    font-size: 48px;
    line-height: 71px;
    letter-spacing: -0.035em;

    color: #333333;
  }
  .detail{
    position: relative;
    width: 328px;
    height: 81px;

    font-size: 18px;
    line-height: 27px;
  }
  button{
    position: relative;
    width: 216px;
    height: 68px;
    top:80px;

    font-size: 14px;
    line-height: 21px;
  }
}
</style>
