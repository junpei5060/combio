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

        <ul class="pic-smp">
        <li>
        <!-- <div class="pic-smp"> -->
          <div class="profile-card">
            <div class="profile-card__inner">
                <div class="profile-thumb">
                    <img src="image/pro_kitou.png">
                </div>

                <div class="profile-content">
                    <div class="pro_icom">
                        <div class="box">
                        <i>PRO</i>
                        </div>
                        <span class="profile-name">鬼頭 史到</span>
                    </div>
                    <span class="profile-job">CEO</span>
                    <span class="profile-intro">【話せる内容】#起業 #新規事業 </span>
                </div>
            </div>
        </div>
        </li>
        <li>
        <!-- <div class="second_stage"> -->
            <div class="profile-card">
                <div class="profile-card__inner">
                    <div class="profile-thumb">
                        <img src="image/pro_hamasaka.png">
                    </div>

                    <div class="profile-content">
                        <div class="pro_icom">
                        <div class="box">
                        <i>PRO</i>
                        </div>
                        <span class="profile-name">濱坂 愛音</span>
                        </div>
                        <span class="profile-job">株式会社10X PM</span>
                        <span class="profile-intro">【話せる内容】#起業 #新規事業 
                        </span>
                    </div>
                </div>
            </div>
      <!-- </div> -->
      </li>
        <li>
        <!-- <div class="second_stage"> -->
            <div class="profile-card">
                <div class="profile-card__inner">
                    <div class="profile-thumb">
                        <img src="image/pro_hamasaka.png">
                    </div>

                    <div class="profile-content">
                        <div class="pro_icom">
                        <div class="box">
                        <i>PRO</i>
                        </div>
                        <span class="profile-name">濱坂 愛音</span>
                        </div>
                        <span class="profile-job">株式会社10X PM</span>
                        <span class="profile-intro">【話せる内容】#起業 #新規事業 
                        </span>
                    </div>
                </div>
            </div>
      <!-- </div> -->
      </li>
      <li>
        <!-- <div class="pic-smp"> -->
          <div class="profile-card">
            <div class="profile-card__inner">
                <div class="profile-thumb">
                    <img src="image/pro_kitou.png">
                </div>

                <div class="profile-content">
                    <div class="pro_icom">
                        <div class="box">
                        <i>PRO</i>
                        </div>
                        <span class="profile-name">鬼頭 史到</span>
                    </div>
                    <span class="profile-job">CEO</span>
                    <span class="profile-intro">【話せる内容】#起業 #新規事業 
                    </span>
                </div>
            </div>
        </div>
        </li>
    
        <!-- </div> -->
        </ul>
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
display: block;
}

.pic-smp{
  display: none;
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

@media (max-width: 959px) {
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
padding-bottom: 30px;
}

.profile-card{
  width: 80%;
  max-width:550px;
  position: relative;
  background: #fff; /*背景の色*/
  box-shadow: 0px 1px 3px rgba(0,0,0,.18);
  overflow: hidden;
  height: 400px;
  border-radius: 20px;
  box-shadow: 0 2px 5px #ccc;
  margin: 0 auto;
  padding-top: 50px;

}

.profile-card:before{
 width:120%;
 height:100px;
 content:"";
 transform:skew(15deg,10deg);
 background: #DB0B40; /*斜め背景の色*/
 position:  absolute;
 top:-15%;
 left:-10%;
 z-index: 0;
}

.pro_icom{
    display: flex;
    text-align: center;
    margin-left: 20px;
}

.box{
  padding: 0.2em;
  background-color: #263440;
  width: 40px;
  text-align: center;
  margin-left: 60px;
  font-size: 8px;
  border-radius: 20px;
  margin-bottom: 3px;
  line-height: 20px;
}

.box i{
  text-align: center;
  color: #fff;
  font-weight: bold;
}

.profile-card__inner{
 position: relative;
}

.profile-thumb{
    overflow: hidden;
    width: 110px;
    height: 110px;
    border: #fff 3px solid;
    border-radius: 55px;
    margin-left: auto;
    margin-right: auto;
    margin-top: 20px;
    background: #fff;
}

.profile-thumb img{
  display: block;
    width: 100%;
    height: auto;
}

.profile-content{
  padding: 15px;
}

.profile-content span{
  display: block;
}

.profile-name{
  margin-bottom: 3px;
  font-weight: bold;
  text-align: center;
  color: #273240;
  margin-left: 10px;
}

.profile-job{
  margin-bottom: 10px;
  color:#DB0B40;
  font-size: 20px;
  text-align: center;
  font-weight: bold;
}

.profile-intro{
  font-size: 12px;
  color: #273240;
  font-weight: bold;
}

.second_stage{
    display: flex;
    flex-direction: column;
    margin-top: 50px;
}

.pic-ctn{
display: none;
}

.pic-smp{
  display: block;
  overflow-x: auto;
      white-space: nowrap;
      -webkit-overflow-scrolling: touch;
}

li{
  display: inline-block;
      width: 90%;
}

}

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
padding-bottom: 30px;
}

.profile-card{
  width: 100%;
  max-width:390px;
  position: relative;
  background: #fff; /*背景の色*/
  box-shadow: 0px 1px 3px rgba(0,0,0,.18);
  /* overflow: hidden; */
  height: 400px;
  border-radius: 20px;
  box-shadow: 0 2px 5px #ccc;
  margin: 0 auto;
  padding-top: 50px;
  

}

.profile-card:before{
 width:120%;
 height:100px;
 content:"";
 transform:skew(15deg,10deg);
 background: #DB0B40; /*斜め背景の色*/
 position:  absolute;
 top:-15%;
 left:-10%;
 z-index: 0;
}

.pro_icom{
    display: flex;
    text-align: center;
    margin-left: 20px;
}

.box{
  padding: 0.2em;
  background-color: #263440;
  width: 40px;
  text-align: center;
  margin-left: 90px;
  font-size: 8px;
  border-radius: 20px;
  margin-bottom: 3px;
  line-height: 20px;
}

.box i{
  text-align: center;
  color: #fff;
  font-weight: bold;
}

.profile-card__inner{
 position: relative;
}

.profile-thumb{
    overflow: hidden;
    width: 110px;
    height: 110px;
    border: #fff 3px solid;
    border-radius: 55px;
    margin-left: auto;
    margin-right: auto;
    margin-top: 20px;
    background: #fff;
}

.profile-thumb img{
  display: block;
    width: 100%;
    height: auto;
}

.profile-content{
  padding: 15px;
}

.profile-content span{
  display: block;
}

.profile-name{
  margin-bottom: 3px;
  font-weight: bold;
  text-align: center;
  color: #273240;
  margin-left: 10px;
}

.profile-job{
  margin-bottom: 10px;
  color:#DB0B40;
  font-size: 20px;
  text-align: center;
  font-weight: bold;
}

.profile-intro{
  font-size: 12px;
  color: #273240;
  font-weight: bold;
}

.second_stage{
    display: flex;
    flex-direction: column;
    margin-top: 50px;
}

.pic-ctn{
display: none;
}

.pic-smp{
  display: block;
  overflow-x: auto;
  white-space: nowrap;
  -webkit-overflow-scrolling: touch;
  padding: 0;
}

li{
  display: inline-block;
  width: 90%;
  margin-right: 10px;
}
}

</style>