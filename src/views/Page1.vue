<template>

<div class="main-header">
      <div class='line'>
         <a href='https://drive.google.com/drive/folders/1-1QEaLrJzSRk9VVl1f1ZYCln6DhjrH7a?usp=sharing'>View more</a>
       </div>
  <div class="slideshow">
    <div class="slideshow__item">
      <img src="https://img.onl/nMJlhd" alt="">
    </div>
    <div class="slideshow__item">
      <img src="https://img.onl/HrfOKc" alt="">
    </div>
    <div class="slideshow__item">
      <img src="https://img.onl/1zs9Wx" alt="">
    </div>
    <div class="slideshow__item">
      <img src="https://img.onl/y9kQRW" alt="">
    </div>
    <div class="slideshow__item">
      <img src="https://img.onl/y9kQRW" alt="">
    </div>
  </div>
</div>
</template>

<style>
body{
  background-color:#e0e0e0;
}
#container {
  width: 400px;
  margin-top: 175px;
  -webkit-transform: rotate(-15deg);
  -moz-transform: rotate(-15deg);
  transform: rotate(-15deg);
}

.line {
  margin-left: 30px;
}

h1,
h2,
h3 {
  color: #555;
  font-family: Open Sans Condensed;
  font-size: 44px;
  line-height: 150%;
  letter-spacing: 2.5px;
  margin: 0;
  text-shadow: 1px 1px 4px #999, 4px 2px 8px #999;
}

a {
  color: #333;
  text-decoration: none;
  -webkit-transition: all 0.25s;
  -moz-transition: all 0.25s;
  transition: all 0.25s;
}

a:hover {
  padding-left: 50px;
}

hr {
  margin: -10px 0 60px -50px;
  background-color: #333;
  border: 0;
  height: 2px;
  width: 350px;
  box-shadow: 1px 1px 4px #999, 4px 2px 8px #999;
}

#container hr:nth-child(2) {
  margin-bottom: 80px;
}
/*Rezizing*/

#container .line:nth-child(2) {
  -webkit-transform: scale(0.75, 0.75);
  -moz-transform: scale(0.75, 0.75);
  transform: scale(0.75, 0.75);
  margin-left: -50px;
  margin-top: -35px;
}

#container .line:nth-child(3) {
  -webkit-transform: scale(0.5, 0.5);
  -moz-transform: scale(0.5, 0.5);
  transform: scale(0.5, 0.5);
  margin-left: -150px;
  margin-top: -50px;
}
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  background-color: #E3E3E3;
}

.main-header {
  width: 100%;
  height: 100vh;
  background-color: steelblue;
}

.slideshow {
  width: 100%;
  height: 100%;
  position: relative;
  display: flex;
  overflow: hidden;
}

.slideshow__item {
  width: 25%;
  position: relative;
  height: 100%;
  transition: .3s ease all;
}

.slideshow__item:hover {
  width: 190%;
}

.slideshow__item img {
  width: 100%;
  height: 100%;
  position: absolute;
  object-fit: none;
  top: 50%;
  transform: translateY(-50%);
}


</style>