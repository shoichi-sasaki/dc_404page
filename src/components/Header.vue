<template>
    <div id="header">
        <div class="header-text">
            404 NOT FOUND
        </div>
    </div>
</template>

<style>
#header{
    width:100%;
    height:200px;
}
.header-text {
    position: absolute;
    width: 300px;
    height: 25px;
    left: 77px;
    top: 40px;

    font-family: Inconsolata;
    font-style: normal;
    font-weight: bold;
    font-size: 24px;
    line-height: 25px;
    letter-spacing: -0.08em;
    text-transform: uppercase;

    color: #333333;
}
@media screen and (max-width: 480px) {
	/* 480px以下に適用されるCSS（スマホ用） */
  .header-text {
    position: absolute;
    width: 300px;
    height: 25px;
    left: 24px;
    top: 20px;
  }
  #header{
    /* width:100%; */
    height:110px;
  }
}
</style>