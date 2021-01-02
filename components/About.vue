<template>
    <div>
        <div class="container">
            <div class="about_container">
                <h5>
                    About
                </h5>
                <p class="about_text">
                    Joshi.comってなに？
                </p>
            </div>
            <section class="card">
            <!-- <img class="card-img" src="image/point1.jpeg" alt=""> -->
            <div class="card-content">
                <p class="title">もう
                    、<span>上司なんかいらない</span></p>
                <h1 class="card-title"><span>01</span>もう上司には悩まない</h1>
                <p class="card-text">ビジネスマンにとって非常に重要な上司や先輩の決定は運要素が強く、適切な指導が得られずに
                本来、ビジネスマンが持つ潜在可能性が引き出されていないと私たちは考えます。師弟.comではあなたに最適なプロ上司を
                マッチングしてあなたの成長角度を最大化します
                </p>
            </div>
            <div class="card-content">
                <h1 class="card-title"><span>02</span>個人に合わせた環境を提供</h1>
                <p class="card-text">ビジネスマンの成長にとって、「環境」は何よりも大切なものです。いくら意識を高く持っていたとしても
                社内に聞ける先輩がいない、自分と同じ悩みを抱えている人がおらず、プロジェクトが前に進まないという課題は優秀なビジネスマンであれば
                あるほど立ち塞がる壁です。師弟.comではあなたが解決したい課題に合わせて最適なプロ上司とメンタリング環境を提供することで、
                目の前のプロジェクトもあなた自身も前に進ませることができます
                </p>
            </div>
            <div class="card-content">
                <h1 class="card-title"><span>03</span>全てのビシネスマンになりたい姿を</h1>
                <p class="card-text">今の会社は好きだけど、なかなか成長が見込まれない、自分よりも優秀な同僚が少ないなどの悩みを抱えている
                ビジネスマンの皆さんのために師弟.comはマネジメント&ビジネスのプロであるプロ上司があなたが目指すべきゴールの設定と道のりを提案、伴走
                一人では辿り着けなかった場所に辿りつけます
                </p>
            </div>
            
            <p class="form_title">無料相談に申し込む</p>
            <p class="form_text">下記申し込みフォームより必要事項を記入し、<br>お申し込みください</p>
            <div class="btn">
            <nuxt-link to="/form" class="btn_top">無料相談を予約する</nuxt-link>
            </div>
        </section>
        </div>
    </div>
</template>

<style scoped>
.container{
height: 1300px;
width: 100%;
margin: 0 auto;
}

.about_container{
text-align: center;
margin-top: 160px;
}
h5{
width: 300px;
transition: all .5s;
font-size: 72px;
color: #263440;
border-bottom:3px solid #263440;
margin: 0 auto;
}

.about_text{
transition: all .5s;
font-size: 32px;
font-weight: bold;
color: #263440;
}    

.card {
  margin: 30px auto;
  width: 800px;
  border-radius: 5px;
  box-shadow: 0 2px 5px #fff;
  height: 1100px;
  border-radius: 20px;
  background:#fff;
}
.card-content {
  padding: 20px;
}

.title{
font-size: 30px;
  margin-bottom: 20px;
  text-align: center;
  color: #263440;
  font-weight: bold;
}

span{
color: #BA0527;
}


.card-title {
  font-size: 20px;
  margin-bottom: 20px;
  text-align: center;
  color: #BA0527;
}
.card-text {
  color: #263440;
  font-size: 15px;
  line-height: 1.9;
  font-weight: bold;
}

.form_title{
width: 300px;
transition: all .5s;
font-size: 20px;
color: #263440;
border-bottom:3px solid #DB0B40;
margin: 30px auto 20px;
font-weight: bold;
text-align: center;
}

.form_text{
width: 300px;
transition: all .5s;
font-size: 12px;
color: #263440;
margin: 0 auto;
font-weight: bold;
text-align: center;
}

.btn_top{
background-color: #273340;
border-radius: 20px;
border: none;
color: #fff;
cursor: pointer;
display: inline-block;
font-size: 14px;
font-weight: 500;
height: 54px;
letter-spacing: .5px;
line-height: 54px;
padding: 0 60px;
text-align: center;
text-decoration: none;
white-space: nowrap;
margin-top:15px;
margin-left: 280px;
}

.btn_top:hover {
background-color: #BA0527;
transition: all .5s;
}
.btn_top:active {
top: 3px;
box-shadow: none;
}

h1 {
  position: relative;
  overflow: hidden;
  padding: 1.5rem 2rem 1.5rem 130px;
  border: 2px solid #263440;
}

h1:before {
  position: absolute;
  top: -150%;
  left: -100px;
  width: 200px;
  height: 300%;
  content: '';
  -webkit-transform: rotate(25deg);
  transform: rotate(25deg);
  background: #263440;
}

h1 span {
  font-size: 16px;
  font-size: 3.2rem;
  position: absolute;
  z-index: 1;
  top: 0;
  left: 0;
  display: block;
  padding-top: 3px;
  padding-left: 16px;
  color: #fff;
}

@media (max-width: 959px) {
.container{
height: 100%;
width: 100%;
max-width: 100%;
margin: 0 auto;
}

.about_container{
text-align: center;
margin-top: 80px;
}
h5{
width: 250px;
transition: all .5s;
font-size: 40px;
color: #263440;
border-bottom:3px solid #263440;
margin: 0 auto;
}

.about_text{
transition: all .5s;
font-size: 20px;
font-weight: bold;
color: #263440;
}    

.card {
  width: 100%;
  margin: 30px auto;
  width: 660px;
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px #ccc;
  height: 750px;
  border-radius: 20px;
}
.card-content {
  padding: 20px;
}

.title{
font-size: 23px;
  margin-bottom: 20px;
  text-align: center;
  color: #263440;
  font-weight: bold;
}

span{
color: #DB0B40;
}


.card-title {
  font-size: 17px;
  margin-bottom: 20px;
  text-align: center;
  color: #DB0B40;
}
.card-text {
  color: #263440;
  font-size: 12px;
  line-height: 1.9;
  font-weight: bold;
}

.form_title{
width: 100%;
max-width: 150px;
transition: all .5s;
font-size: 14px;
color: #263440;
border-bottom:3px solid #DB0B40;
margin: 15px auto;
font-weight: bold;
text-align: center;
}

.form_text{
width: 100%;
max-width: 270px;
transition: all .5s;
font-size: 12px;
color: #263440;
margin: 0 auto;
font-weight: bold;
text-align: center;
}


.btn{
    display: flex;
    margin-top: 30px;
}

.btn_top{
background-color: #273340;
border-radius: 20px;
border: none;
color: #fff;
cursor: pointer;
display: inline-block;
font-size: 12px;
font-weight: 500;
height: 54px;
letter-spacing: .5px;
line-height: 54px;
padding: 0 30px;
text-align: center;
text-decoration: none;
white-space: nowrap;
margin: 0 auto;
}

.btn_top:hover {
background-color: #DB0B40;
transition: all .5s;
}
.btn_top:active {
top: 3px;
box-shadow: none;
}
}


@media (max-width: 479px) {
.container{
height: 100%;
width: 100%;
max-width: 100%;
margin: 0 auto;
}

.about_container{
text-align: center;
margin-top: 80px;
}
h5{
width: 250px;
transition: all .5s;
font-size: 40px;
color: #263440;
border-bottom:3px solid #263440;
margin: 0 auto;
}

.about_text{
transition: all .5s;
font-size: 20px;
font-weight: bold;
color: #263440;
}    

.card {
  width: 100%;
  margin: 30px auto;
  width: 330px;
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px #ccc;
  height: 1000px;
  border-radius: 20px;
}
.card-content {
  padding: 20px;
}

.title{
font-size: 23px;
  margin-bottom: 20px;
  text-align: center;
  color: #263440;
  font-weight: bold;
}

span{
color: #DB0B40;
}


.card-title {
  font-size: 17px;
  margin-bottom: 20px;
  text-align: center;
  color: #DB0B40;
}
.card-text {
  color: #263440;
  font-size: 12px;
  line-height: 1.9;
  font-weight: bold;
}

.form_title{
width: 100%;
max-width: 150px;
transition: all .5s;
font-size: 14px;
color: #263440;
border-bottom:3px solid #DB0B40;
margin: 15px auto;
font-weight: bold;
text-align: center;
}

.form_text{
width: 100%;
max-width: 270px;
transition: all .5s;
font-size: 12px;
color: #263440;
margin: 0 auto;
font-weight: bold;
text-align: center;
}


.btn{
    display: flex;
    margin-top: 30px;
}

.btn_top{
background-color: #273340;
border-radius: 20px;
border: none;
color: #fff;
cursor: pointer;
display: inline-block;
font-size: 12px;
font-weight: 500;
height: 54px;
letter-spacing: .5px;
line-height: 54px;
padding: 0 30px;
text-align: center;
text-decoration: none;
white-space: nowrap;
margin: 0 auto;
}

.btn_top:hover {
background-color: #DB0B40;
transition: all .5s;
}
.btn_top:active {
top: 3px;
box-shadow: none;
}
}

</style>