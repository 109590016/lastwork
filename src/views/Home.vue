<template>
  <div class="home">
    <div id = "crop">
<div id = "pic">  
 <img src = "https://image.freepik.com/free-vector/flat-design-winter-landscape-concept_23-2148358542.jpg"/>
</div>

<div id = "slide">
<svg xmlns="http://www.w3.org/2000/svg" id = "penguin" viewBox="0 0 46 21">
  <defs/>
  <g data-name="Layer 2">
    <g data-name="Layer 1-2">
      <path d="M14 8S5 7 3 15c-4 2-3 6-3 6l7-3s28 4 36-10c5-5 3-8 3-8l-8 2S16 1 14 8z"/>
      <path fill="#fff" d="M7 18S25 8 43 8C36 18 17 19 7 18z"/>
      <path id = "arm" d="M20 11a5 5 0 016-2c4 1 10 8 10 8s-15 1-16-6zM25 3l7-3-1 2-6 1z"/>
    </g>
  </g>
</svg>
</div>
</div>

  </div>
</template>

<style>
*{
  margin:0;
  padding:0;
}
body{
  background-color:#26547C;
}

//
img{
  width:150%;
  height:auto;
}

#penguin{
  width:100px;
  height:auto;
  transform: scale(-1,-1);
   motion-path: path("M519.2,338.3S426.77,356,353.6,416.09,168,433.81,168,433.81");
  offset-path: path("M519.2,338.3S426.77,356,353.6,416.09,168,433.81,168,433.81");

  animation: move 5s infinite;
}

#slide{
  transform: translate(0px,-110px);
}

@keyframes move {
  100% {
    motion-offset: 100%;
    offset-distance: 100%;
  }
}

#pic {
  position:absolute;
    top:50%;
  left:50%;
  transform:translate(-50%,-50%);
   filter: drop-shadow(0 0 100px #333);

}

#crop{
  width:500px;
  height:400px;
   top:50%;
   left:50%;
   transform:translate(-50%,-50%);
   filter: drop-shadow(0 0 100px #333);
  position:fixed;
   filter: drop-shadow(0 0 100px #333);
     border-radius:50%;
  overflow:hidden;
}

#arm{
 animation: flap 1s infinite;
}

@keyframes flap {
  100%{
    transform: rotate(-10deg);
  }
}


</style>>


