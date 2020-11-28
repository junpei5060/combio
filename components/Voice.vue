<template>
    <div class="container">
        <div class="voice_container">
        <h5>
            User’s voice
        </h5>
        <p class="voice_text">
            すでに多くのビジネスマンがCambioで成長しています
        </p>
        <div class="pic-ctn">
        <img src="image/Voice1.png" class="pic">
        <img src="image/Voice1.png" class="pic">
        <img src="image/Voice1.png" class="pic">
        <img src="image/Voice1.png" class="pic">
        <img src="image/Voice1.png" class="pic">
        </div>
        </div>
    </div>
</template>

<style scoped>
.container{
height: 100%;
width: 100%;
max-width: 1440px;
margin: 0 auto;
}

.voice_container{
text-align: center;
}
h5{
width: 600px;
transition: all .5s;
font-size: 72px;
border-bottom:3px solid #DB0B40;
margin: 0 auto;
}

.voice_text{
transition: all .5s;
font-size: 32px;
font-weight: bold;
}

.pic-ctn{
width: 100px;
margin-top: 80px;
position: relative;
left: 280px;

}


@keyframes display {
  0% {
    transform: translateX(200px);
    opacity: 0;
  }
  10% {
    transform: translateX(0);
    opacity: 1;
  }
  20% {
    transform: translateX(0);
    opacity: 1;
  }
  30% {
    transform: translateX(-200px);
    opacity: 0;
  }
  100% {
    transform: translateX(-200px);
    opacity: 0;
  }
}
.pic-ctn > img {
  position: absolute;
  top: 0;
  left: calc(50% - 100px);
  opacity: 0;
  animation: display 10s infinite;
  width: 1000px;
}

img:nth-child(2) {
  animation-delay: 2s;
}
img:nth-child(3) {
  animation-delay: 4s;
}
img:nth-child(4) {
  animation-delay: 6s;
}
img:nth-child(5) {
  animation-delay: 8s;
}
</style>