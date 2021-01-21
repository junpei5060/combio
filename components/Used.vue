<template>
  <div class="container">
    <div class="used_container">
      <h5>
        Flow
      </h5>
      <p class="used_text">
        MeeeLookご利用までの流れ
      </p>
      <!-- <section class="card"> -->
      <div>
        <!-- <i class="far fa-envelope"></i>
          <p>無料相談に申し込む</p> -->
        <div class="box">
          <h2>
            <i class="far fa-envelope"></i
            ><span class="title">無料相談に申し込み</span><br />
            <span class="text"
              >まずは無料相談でMeeeLookをお試しください無料相談ではお客様に合わせたプランをご提案させていただきます</span
            >
          </h2>
        </div>
        <i class="fas fa-arrow-down"></i>
        <div class="box">
          <h2>
            <i class="far fa-handshake"></i
            ><span class="title">メンター決定</span><br />
            <span class="text"
              >無料相談にご満足いただき、お支払い完了後に初回カウンセリングを実施、ヒヤリング内容を基にお客様に合わせたメンターを紹介します</span
            >
          </h2>
        </div>
        <i class="fas fa-arrow-down"></i>
        <div class="box">
          <h2>
            <i class="fas fa-user-friends icon"></i
            ><span class="title">メンタリング開始</span><br />
            <span class="text"
              >日程調整を行い、いよいよ初回の面談がスタートです。ここから自分をふりかえり、新たな自分の出会いましょう</span
            >
          </h2>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  height: 100%;
  width: 100%;
  max-width: 1440px;
  margin: 0 auto;
}
.used_container {
  text-align: center;
}
h5 {
  width: 1000px;
  transition: all 0.5s;
  font-size: 72px;
  color: #263440;
  border-bottom: 3px solid #263440;
  margin: 0 auto;
}
.used_text {
  transition: all 0.5s;
  font-size: 32px;
  font-weight: bold;
  color: #263440;
}
.user_btn {
  position: relative;
  display: flex;
}
.Used_img {
  width: 1200px;
  position: relative;
  top: 30px;
  border-radius: 20px;
  box-shadow: 0 2px 5px #ccc;
  /* display: block; */
  margin: 0 auto;
}
.btn_top {
  background-color: #273340;
  border-radius: 20px;
  border: none;
  color: #fff;
  cursor: pointer;
  display: inline-block;
  font-size: 14px;
  font-weight: 500;
  height: 54px;
  letter-spacing: 0.5px;
  line-height: 54px;
  padding: 0 60px;
  text-align: center;
  text-decoration: none;
  white-space: nowrap;
  position: absolute;
  margin-top: 500px;
  left: 42%;
  z-index: 2;
}
.btn_top:hover {
  background-color: #4caf50;
  transition: all 0.5s;
}
.btn_top:active {
  top: 3px;
  box-shadow: none;
}
.Flow_img {
  display: none;
}
/* ここがレスポンシブ（ipad）対応 */
/* @media screen and (max-width: 959px) {
    .container{
max-width: 959px;
}
.Used_container{
text-align: center;
}
h5{
width: 666px;
font-size: 48px;
}
.Used_img{
width: 800px;
position: relative;
top:20px;
margin-bottom: 100px;
}
}  */
/*ウィンドウ幅が最大959pxまでの場合に適用*/
/* ここまで */

.far {
  font-size: 30px;
  color: #4caf50;
}
.fas {
  font-size: 50px;
  color: #273340;
}

.box {
  width: 70%;
  margin: 50px auto 10px;
}

h2 {
  position: relative;
  padding: 1.5rem;
  text-align: center;
  border: 2px solid #273340;
  background: #fff;
  color: #273340;
  height: 200px;
}

h2:before,
h2:after {
  position: absolute;
  content: "";
}

h2:before {
  top: -40px;
  left: calc(50% - 40px);
  width: 80px;
  height: 80px;
  border: 2px solid #273340;
  border-radius: 50%;
  background: #fff;
}

h2:after {
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: #fff;
}

h2 i {
  font-size: 30px;
  font-size: 3rem;
  line-height: 60px;
  position: absolute;
  z-index: 1;
  top: -40px;
  left: calc(50% - 40px);
  width: 80px;
  height: 60px;
  text-align: center;
}

h2 span {
  position: relative;
  z-index: 1;
}
.text {
  font-size: 20px;
}
.icon {
  font-size: 30px;
  color: #4caf50;
}

.title {
  position: relative;
  padding: 1.5rem;
  text-align: center;
  font-size: 30px;
}

.title:before {
  position: absolute;
  bottom: 20px;
  left: calc(50% - 30px);
  width: 60px;
  height: 5px;
  content: "";
  border-radius: 3px;
  background: #4caf50;
}

@media (max-width: 959px) {
  .container {
    height: 100%;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
  }
  .used_container {
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
  .used_text {
    transition: all 0.5s;
    font-size: 20px;
    font-weight: bold;
    color: #263440;
  }
  /* .user_btn{
position: relative;
display: flex;
} */
  .card {
    width: 100%;
    margin: 30px auto;
    width: 660px;
    background: #fff;
    border-radius: 5px;
    box-shadow: 0 2px 5px #ccc;
    height: 800px;
    border-radius: 20px;
  }
  .btn_top {
    background-color: #273340;
    border-radius: 20px;
    border: none;
    color: #fff;
    cursor: pointer;
    display: inline-block;
    font-size: 10px;
    font-weight: 500;
    height: 24px;
    letter-spacing: 0.5px;
    line-height: 24px;
    padding: 0 30px;
    text-align: center;
    text-decoration: none;
    white-space: nowrap;
    position: absolute;
    left: 40%;
    z-index: 2;
    margin-top: 300px;
  }
  .btn_top:hover {
    background-color: #4caf50;
    transition: all 0.5s;
  }
  .btn_top:active {
    top: 3px;
    box-shadow: none;
  }
  .far {
    font-size: 30px;
    color: #4caf50;
  }
  .fas {
    font-size: 50px;
    color: #273340;
  }

  .box {
    width: 80%;
    margin: 50px auto 10px;
  }

  h2 {
    position: relative;
    padding: 1.1rem;
    text-align: center;
    border: 2px solid #273340;
    background: #fff;
    color: #273340;
    height: 150px;
  }

  h2:before,
  h2:after {
    position: absolute;
    content: "";
  }

  h2:before {
    top: -40px;
    left: calc(50% - 40px);
    width: 80px;
    height: 80px;
    border: 2px solid #273340;
    border-radius: 50%;
    background: #fff;
  }

  h2:after {
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #fff;
  }

  h2 i {
    font-size: 30px;
    font-size: 3rem;
    line-height: 60px;
    position: absolute;
    z-index: 1;
    top: -40px;
    left: calc(50% - 40px);
    width: 80px;
    height: 60px;
    text-align: center;
  }

  h2 span {
    position: relative;
    z-index: 1;
  }
  .text {
    font-size: 16px;
  }
  .icon {
    font-size: 30px;
    color: #4caf50;
  }
}

@media (max-width: 479px) {
  .container {
    height: 100%;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
  }
  .used_container {
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
  .used_text {
    transition: all 0.5s;
    font-size: 20px;
    font-weight: bold;
    color: #263440;
  }
  /* .user_btn{
position: relative;
display: flex;
} */
  .card {
    width: 100%;
    margin: 30px auto;
    width: 330px;
    background: #fff;
    border-radius: 5px;
    box-shadow: 0 2px 5px #ccc;
    height: 800px;
    border-radius: 20px;
  }
  .btn_top {
    background-color: #273340;
    border-radius: 20px;
    border: none;
    color: #fff;
    cursor: pointer;
    display: inline-block;
    font-size: 10px;
    font-weight: 500;
    height: 24px;
    letter-spacing: 0.5px;
    line-height: 24px;
    padding: 0 30px;
    text-align: center;
    text-decoration: none;
    white-space: nowrap;
    position: absolute;
    left: 26%;
    z-index: 2;
    margin-top: 5px;
  }
  .btn_top:hover {
    background-color: #4caf50;
    transition: all 0.5s;
  }
  .btn_top:active {
    top: 3px;
    box-shadow: none;
  }
  .far {
    font-size: 30px;
    color: #4caf50;
  }
  .fas {
    font-size: 50px;
    color: #273340;
  }

  .box {
    width: 80%;
    margin: 50px auto 10px;
  }

  h2 {
    position: relative;
    padding: 1.1rem;
    text-align: center;
    border: 2px solid #273340;
    background: #fff;
    color: #273340;
    height: 200px;
  }

  h2:before,
  h2:after {
    position: absolute;
    content: "";
  }

  h2:before {
    top: -40px;
    left: calc(50% - 40px);
    width: 80px;
    height: 80px;
    border: 2px solid #273340;
    border-radius: 50%;
    background: #fff;
  }

  h2:after {
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #fff;
  }

  h2 i {
    font-size: 30px;
    font-size: 3rem;
    line-height: 60px;
    position: absolute;
    z-index: 1;
    top: -40px;
    left: calc(50% - 40px);
    width: 80px;
    height: 60px;
    text-align: center;
  }

  h2 span {
    position: relative;
    z-index: 1;
  }

.title{
  font-size:16px;
}

  .text {
    font-size: 12px;
  }
  .icon {
    font-size: 30px;
    color: #4caf50;
  }
}
</style>
