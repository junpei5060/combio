<template>
    <div class="container">
        <div class="Characteristic_container">
        <h5>
            Use Case
        </h5>
        <p class="Characteristic_text">
            こんな悩みを抱えるあなたにおすすめ
        </p>
        <div class="Characteristic_card">
        <section class="card">
            <div class="card-content">
                <h1 class="card-title">社内リソースでは<br>
                成長実感が得られない</h1>
                <p class="card-text">自分が成し遂げたい目標設定や現状の課題の整理等プラニングをサポート。
                    スポットでの相談ではなく、最低1ヵ月間、毎日継続的に目標の進捗度を測ったり、
                    必要なアドバイスを提供することで自己実現を伴奏してサポートします。</p>
            </div>
        </section>
        <section class="card">
            <div class="card-content">
                <h1 class="card-title">多忙で自己研鑽が後回し</h1>
                <p class="card-text">メンター（プロ上司）はそれぞれ第一線で活躍する経験豊富な方が集まっており、
                    自分のキャリアの一歩、二歩先を行く彼らに仕事の相談が可能。またマネジメントや営業等、
                    自らの課題認識に最適なサポートをしてもらえるメンターを指名可能。
                    週次でメンタリングを行うことで成長の加速を図ります。
</p>
            </div>
        </section>
        <section class="card">
            <div class="card-content">
                <h1 class="card-title">ロールモデルと呼べる人がいない</h1>
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
height: 750px;
width: 100%;
margin: 0 auto;
margin-top: 720px;
margin-bottom: 120px;
}

.Characteristic_container{
text-align: center;
}
h5{
width: 350px;
transition: all .5s;
font-size: 72px;
color: #263440;
border-bottom:3px solid #263440;
margin: 0 auto;
}


.Characteristic_text{
transition: all .5s;
font-size: 32px;
font-weight: bold;
color: #263440;
}

.Characteristic_card{
    /* display: flex; */
}

.card {
  margin: 30px auto;
  width: 700px;
  background: #fff;
  border-radius: 20px;
  box-shadow: 0 2px 5px #ccc;
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
/*ウィンドウ幅が最大959pxまでの場合に適用*/
/* ここまで */

@media (max-width: 959px) {
.container{
height: 100%;
width: 100%;
max-width: 100%;
margin: 0 auto;
margin-top: 100px;
margin-bottom: 100px;
}

.Characteristic_container{
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


.Characteristic_text{
transition: all .5s;
font-size: 20px;
font-weight: bold;
color: #263440;
}

.Characteristic_card{
    /* display: flex; */
}

.card {
  margin: 30px auto;
  width: 550px;
  background: #fff;
  border-radius: 20px;
  box-shadow: 0 2px 5px #ccc;
}

.card-content {
  padding: 12px;
}
.card-title {
  font-size: 15px;
  margin-bottom: 20px;
  text-align: center;
  color: #DB0B40;
}
.card-text {
  color: #263440;
  font-size: 14px;
  line-height: 1.9;
  font-weight: bold;
}
}

@media (max-width: 479px) {
.container{
height: 100%;
width: 100%;
max-width: 100%;
margin: 0 auto;
margin-top: 100px;
margin-bottom: 100px;
}

.Characteristic_container{
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


.Characteristic_text{
transition: all .5s;
font-size: 20px;
font-weight: bold;
color: #263440;
}

.Characteristic_card{
    /* display: flex; */
}

.card {
  margin: 30px auto;
  width: 330px;
  background: #fff;
  border-radius: 20px;
  box-shadow: 0 2px 5px #ccc;
}

.card-content {
  padding: 12px;
}
.card-title {
  font-size: 15px;
  margin-bottom: 20px;
  text-align: center;
  color: #DB0B40;
}
.card-text {
  color: #263440;
  font-size: 14px;
  line-height: 1.9;
  font-weight: bold;
}
}
</style>