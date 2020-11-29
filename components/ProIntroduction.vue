<template>
    <div class="container">
        <p class="pro_text">
        師弟.<i>com</i>で<br>
        あなたに最適な理想の<br>
        <span>プロ上司</span>が見つかります
        </p>
        
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
                    <span class="profile-intro">【話せる内容】#起業 #新規事業 #創業者 #教育 #デザイン #UX #組織づくり #ワークショップデザイン#サービス開発 #コンテンツディレクター#コミュニティ#不動産
                    </span>
                </div>
            </div>
        </div>
        <div class="second_stage">
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
                        <span class="profile-intro">【話せる内容】#起業 #新規事業 #創業者 #教育 #デザイン #UX #組織づくり #ワークショップデザイン#サービス開発 #コンテンツディレクター#コミュニティ#不動産
                        </span>
                    </div>
                </div>
            </div>
            <div class="profile-card">
                <div class="profile-card__inner">
                    <div class="profile-thumb">
                        <img src="image/pro_kawano.png">
                    </div>

                    <div class="profile-content">
                        <div class="pro_icom">
                        <div class="box">
                        <i>PRO</i>
                        </div>
                        <span class="profile-name">河野 淳平</span>
                        </div>
                        <span class="profile-job">CEO</span>
                        <span class="profile-intro">【話せる内容】#起業 #新規事業 #創業者 #教育 #デザイン #UX #組織づくり #ワークショップデザイン#サービス開発 #コンテンツディレクター#コミュニティ#不動産
                        </span>
                    </div>
                </div>
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

.pro_text{
width: 500px;
color: #273240;
font-size: 40px;
transition: all .5s;
line-height: 70px;
font-weight: bold;
border-bottom:3px solid #ffffff;
margin-left: 80px;
margin-top: 120px;
margin-bottom: 100px;
}

span{
    color: #fff;

}
/* 
.pro_img{
width: 1450px;
position: relative;
top:100px;
left: 50px;
margin-bottom: 200px;
} */

.profile-card{
  width: 100%;
  max-width:500px;
  position: relative;
  background: #fff; /*背景の色*/
  box-shadow: 0px 1px 3px rgba(0,0,0,.18);
  overflow: hidden;
  height: 400px;
  border-radius: 20px;
  box-shadow: 0 2px 5px #ccc;
  margin: 0 auto;

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
    margin-left: 60px;
}

.box{
  padding: 0.2em;
  background-color: #263440;
  width: 60px;
  text-align: center;
  margin-left: 10px;
  font-size: 14px;
  border-radius: 20px;
  margin-bottom: 3px;
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
    margin-top: 50px;
}
</style>