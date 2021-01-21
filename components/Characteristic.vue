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
            <h1 class="card-title">
              社内リソースでは<br />
              成長実感が得られない
            </h1>
            <p class="card-text">
              “職場にふりかえりを一緒に伴走してくれる先輩がいない“/”同僚に打ち明けづらい悩みがある“
ということはありませんか？職場で抱えている“自分だけの悩みや課題”の解決をサポートします。

            </p>
          </div>
        </section>
        <section class="card">
          <div class="card-content">
            <h1 class="card-title">多忙で自己研鑽が後回し</h1>
            <p class="card-text">
              「ふりかえり」は大事だと思うけど、ついつい後回しになってしまいますよね。質の高い振り返りの通して、自身を見つめ直す機会を提供します。
            </p>
          </div>
        </section>
        <section class="card">
          <div class="card-content">
            <h1 class="card-title">ロールモデルと呼べる人がいない</h1>
            <p class="card-text">
              “漠然と将来のキャリアに不安がある“/”他の業種の話を聞きたい”などキャリアの悩みはありませんか？経験豊富なメンターが、キャリアや将来に関する相談に乗り、実現したい姿を一緒に考えます。
            </p>
          </div>
        </section>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  height: 750px;
  width: 100%;
  margin: 0 auto;
  margin-top: 120px;
  margin-bottom: 120px;
}

.Characteristic_container {
  text-align: center;
}
h5 {
  width: 350px;
  transition: all 0.5s;
  font-size: 72px;
  color: #263440;
  border-bottom: 3px solid #263440;
  margin: 0 auto;
}

.Characteristic_text {
  transition: all 0.5s;
  font-size: 32px;
  font-weight: bold;
  color: #263440;
}

.Characteristic_card {
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
  color: #4caf50;
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
  .container {
    height: 100%;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
    margin-top: 100px;
    margin-bottom: 100px;
  }

  .Characteristic_container {
    text-align: center;
  }
  h5 {
    width: 250px;
    transition: all 0.5s;
    font-size: 40px;
    color: #263440;
    border-bottom: 3px solid #263440;
    margin: 0 auto;
  }

  .Characteristic_text {
    transition: all 0.5s;
    font-size: 20px;
    font-weight: bold;
    color: #263440;
  }

  .Characteristic_card {
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
    color: #4caf50;
  }
  .card-text {
    color: #263440;
    font-size: 14px;
    line-height: 1.9;
    font-weight: bold;
  }
}

@media (max-width: 479px) {
  .container {
    height: 100%;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
    margin-top: 100px;
    margin-bottom: 100px;
  }

  .Characteristic_container {
    text-align: center;
  }
  h5 {
    width: 250px;
    transition: all 0.5s;
    font-size: 40px;
    color: #263440;
    border-bottom: 3px solid #263440;
    margin: 0 auto;
  }

  .Characteristic_text {
    transition: all 0.5s;
    font-size: 20px;
    font-weight: bold;
    color: #263440;
  }

  .Characteristic_card {
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
    color: #4caf50;
  }
  .card-text {
    color: #263440;
    font-size: 14px;
    line-height: 1.9;
    font-weight: bold;
  }
}
</style>
