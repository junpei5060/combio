<template>
  <div class="container">
    <div class="point_container">
      <h5>
        Point
      </h5>
      <p class="pro_text">
        MeeeLookだからできること
      </p>
      <!-- <img src="image/point1.png" class="point_img"> -->
      <div class="point_card">
        <section class="card">
          <img class="card-img" src="image/point1.jpeg" alt="" />
          <div class="card-content">
            <h1 class="card-title">目標設定/伴奏サポート</h1>
            <p class="card-text">
              自分が成し遂げたい目標設定や現状の課題の整理等プラニングをサポート。
              スポットでの相談ではなく、最低2ヵ月間、継続的に目標や課題解決の進捗度を振り返り、
              必要なアドバイスを提供することで自己実現に向けて伴走します。
            </p>
          </div>
        </section>

        <section class="card">
          <img class="card-img" src="image/point2.jpeg" alt="" />
          <div class="card-content">
            <h1 class="card-title">
              第一線で活躍するメンターと<br />
              1on1ミーティング
            </h1>
            <p class="card-text">
              メンターはそれぞれ第一線で活躍する経験豊富な方が集まっており、
              自分のキャリアの一歩、二歩先を行く彼らに仕事の相談が可能。またマネジメントや営業等、
              自らの課題認識に最適なサポートをしてもらえるメンターを指名可能。
              週次でメンタリングを行うことで「ふりかえり」の質を高めます。
            </p>
          </div>
        </section>
        <section class="card">
          <img class="card-img" src="image/point3.png" alt="" />
          <div class="card-content">
            <h1 class="card-title">
              マンツーマンオンライン<br />
              カウンセリング
            </h1>
            <p class="card-text">
              自身が設定した課題や同僚に打ち明けづらい悩みの相談等、
              ざっくばらんに事務局サポーターと話すことができます。
              日報に対して毎日事務局目線でのフィードバックを実施し、
              自己実現できるようサポートします。
            </p>
          </div>
        </section>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  height: 100%;
  width: 100%;
  margin: 0 auto;
}

.point_container {
  text-align: center;
  margin-top: 160px;
}
h5 {
  width: 300px;
  transition: all 0.5s;
  font-size: 72px;
  color: #263440;
  border-bottom: 3px solid #263440;
  margin: 0 auto;
}

.pro_text {
  transition: all 0.5s;
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

.point_card {
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
  color: #4caf50;
}
.card-text {
  color: #263440;
  font-size: 14px;
  line-height: 1.5;
  font-weight: bold;
}

@media screen and (max-width: 959px) {
  .container {
    height: 100%;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
  }

  .point_container {
    text-align: center;
    margin-top: 80px;
  }
  h5 {
    width: 250px;
    transition: all 0.5s;
    font-size: 40px;
    color: #263440;
    border-bottom: 3px solid #263440;
    margin: 0 auto;
  }

  .pro_text {
    transition: all 0.5s;
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

  .point_card {
    display: flex;
    flex-direction: column;
  }

  .card {
    margin: 30px auto;
    width: 550px;
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
    color: #4caf50;
  }
  .card-text {
    color: #263440;
    font-size: 14px;
    line-height: 1.5;
    font-weight: bold;
  }
}

@media (max-width: 479px) {
  .point_card {
    display: flex;
    flex-direction: column;
  }
  .container {
    height: 100%;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
  }

  .point_container {
    text-align: center;
    margin-top: 80px;
  }
  h5 {
    width: 250px;
    transition: all 0.5s;
    font-size: 40px;
    color: #263440;
    border-bottom: 3px solid #263440;
    margin: 0 auto;
  }

  .pro_text {
    transition: all 0.5s;
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

  .point_card {
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
    color: #4caf50;
  }
  .card-text {
    color: #263440;
    font-size: 14px;
    line-height: 1.5;
    font-weight: bold;
  }
}
</style>
