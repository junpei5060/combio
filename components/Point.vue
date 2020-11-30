<template>
    <div class="container">
        <div class="point_container">
        <h5>
            Point
        </h5>
        <p class="pro_text">
            師弟.comだからできること
        </p>
        <!-- <img src="image/point1.png" class="point_img"> -->
        <div class="point_card">
        <section class="card">
            <img class="card-img" src="image/point1.jpeg" alt="">
            <div class="card-content">
                <h1 class="card-title">目標設定/伴奏サポート</h1>
                <p class="card-text">自分が成し遂げたい目標設定や現状の課題の整理等プラニングをサポート。
                    スポットでの相談ではなく、最低1ヵ月間、毎日継続的に目標の進捗度を測ったり、
                    必要なアドバイスを提供することで自己実現を伴奏してサポートします。</p>
            </div>
        </section>
        <section class="card">
            <img class="card-img" src="image/point2.jpeg" alt="">
            <div class="card-content">
                <h1 class="card-title">第一線で活躍するメンターと<br>
                    1on1ミーティング</h1>
                <p class="card-text">メンター（プロ上司）はそれぞれ第一線で活躍する経験豊富な方が集まっており、
                    自分のキャリアの一歩、二歩先を行く彼らに仕事の相談が可能。またマネジメントや営業等、
                    自らの課題認識に最適なサポートをしてもらえるメンターを指名可能。
                    週次でメンタリングを行うことで成長の加速を図ります。
</p>
            </div>
        </section>
        <section class="card">
            <img class="card-img" src="image/point3.png" alt="">
            <div class="card-content">
                <h1 class="card-title">マンツーマンオンライン<br>
                    カウンセリング</h1>
                <p class="card-text">自身が掲げた目標設定の進捗状況や現状抱えている悩みの相談等、
                    ざっくばらんに事務局サポーターと話すことができます。
                    日報に対して毎日事務局目線でのフィードバックを実施し、
                    成長を促進できるよう尽力します。</p>
            </div>
        </section>
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

.point_container{
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

.pro_text{
transition: all .5s;
font-size: 32px;
font-weight: bold;
color: #263440;
}

/* .point_img{
width: 1200px;
position: relative;
top:30px;
margin-bottom: 150px;
} */

.point_card{
    display: flex;
}

.card {
  margin: 30px auto;
  width: 350px;
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px #ccc;
}
.card-img {
  border-radius: 5px 5px 0 0;
  max-width: 100%;
  height: auto;
}
.card-content {
  padding: 20px;
}
.card-title {
  font-size: 20px;
  margin-bottom: 20px;
  text-align: center;
  color: #DB0B40;
}
.card-text {
  color: #263440;
  font-size: 14px;
  line-height: 1.5;
  font-weight: bold;
}

@media screen and (max-width: 959px) {
.container{
max-width: 959px;
}
.point_container{
text-align: center;
}
h5{
width: 200px;
font-size: 48px;
}
.pro_text{
font-size: 14px;
}

.point_img{
width: 800px;
}

} /*ウィンドウ幅が最大959pxまでの場合に適用*/
/* ここまで */


@media (max-width: 479px) {

 .point_card{
    display: flex;
    flex-direction: column;
}
.container{
height: 100%;
width: 100%;
max-width: 100%;
margin: 0 auto;
}

.point_container{
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


.pro_text{
transition: all .5s;
font-size: 20px;
font-weight: bold;
color: #263440;
}

/* .point_img{
width: 1200px;
position: relative;
top:30px;
margin-bottom: 150px;
} */

.point_card{
    display: flex;
}

.card {
  margin: 30px auto;
  width: 330px;
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px #ccc;
}
.card-img {
  border-radius: 5px 5px 0 0;
  max-width: 100%;
  height: auto;
}
.card-content {
  padding: 20px;
}
.card-title {
  font-size: 20px;
  margin-bottom: 20px;
  text-align: center;
  color: #DB0B40;
}
.card-text {
  color: #263440;
  font-size: 14px;
  line-height: 1.5;
  font-weight: bold;
}

}
</style>