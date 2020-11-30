<template>
    <div class="container">
        <div class="voice_container">
        <h5>
            User’s voice
        </h5>
        <p class="voice_text">
            すでに多くのビジネスマンが師弟.comで成長しています
        </p>
        <div class="pic-ctn">
        <img src="image/Voice1.png" class="pic">
        <img src="image/Voice2.png" class="pic">
        <img src="image/Voice1.png" class="pic">
        <img src="image/Voice2.png" class="pic">
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
color: #263440;
border-bottom:3px solid #263440;
margin: 0 auto;
margin-top: 160px;
}

.voice_text{
transition: all .5s;
font-size: 32px;
font-weight: bold;
color: #263440;
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
  border-radius: 30px;
box-shadow: 0 2px 5px #ccc;
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

@media screen and (max-width: 959px) {
.container{
max-width: 959px;
}

.voice_container{
}
h5{
width: 400px;
font-size: 48px;
}

.voice_text{
font-size: 21px;
}
.pic-ctn{
width: 67px;
margin-top: 53px;
left: 180px;

}
@keyframes display {
  0% {
    transform: translateX(133px);
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
    transform: translateX(-133px);
    opacity: 0;
  }
  100% {
    transform: translateX(-133px);
    opacity: 0;
  }
}
.pic-ctn > img {
  position: absolute;
  top: 0;
  left: calc(50% - 67px);
  opacity: 0;
  animation: display 30s infinite;
  width: 667px;
}
} /*ウィンドウ幅が最大959pxまでの場合に適用*/
/* ここまで */

@media (max-width: 479px) {
.container{
height: 100%;
width: 100%;
max-width: 100%;
margin-top: 80px;
}

.voice_container{
text-align: center;
}
h5{
width: 250px;
transition: all .5s;
font-size: 40px;
color: #263440;
border-bottom:3px solid #263440;
margin: 0 auto;
}

.voice_text{
transition: all .5s;
font-size: 20px;
font-weight: bold;
color: #263440;
width: 70%;
margin: 0 auto;
}

.pic-ctn{
width: 20px;
margin-top: 30px;
position: relative;
left: 120px;
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
  width: 330px;
  border-radius: 30px;
box-shadow: 0 2px 5px #ccc;
height: 350px;
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
}
</style>