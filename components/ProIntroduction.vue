<template>
  <div class="container">
    <p class="pro_text">
      <i>MeeeLook</i>には<br />
      あなたに最適な理想の<br />
      <span>メンター</span>が待っています
    </p>

    <div class="second_stage">
      <div class="profile-card">
        <div class="profile-card__inner">
          <div class="profile-thumb">
            <img src="image/pro_kitou.png" />
          </div>

          <div class="profile-content">
            <div class="pro_box">
              <div class="pro_icom">
                <div class="box">
                  <i>Menter</i>
                </div>
                <span class="profile-name">鬼頭 史到</span>
              </div>
            </div>
            <span class="profile-job">CEO</span>
            <span class="profile-intro"
              >【メッセージ】<br />
              「ふりかえり」を実施することはとても大切なことです。日々、仕事に追われなかなか自分自身を振り返る時間もない方はぜひ一度、MeeeLookをご利用ください！私が責任を持ってサポートさせていただきます！ビジネスの観点だけでなく、キャリアとしての観点でも振り返りのサポートをいたします。
              一緒に理想の自分を見つけましょう！
            </span>
          </div>
        </div>
      </div>
      <div class="profile-card">
        <div class="profile-card__inner">
          <div class="profile-thumb">
            <img src="image/pro_hamasaka.png" />
          </div>

          <div class="profile-content">
            <div class="pro_icom">
              <div class="box">
                <i>Menter</i>
              </div>
              <span class="profile-name">濱坂 愛音</span>
            </div>
            <span class="profile-job">株式会社10X PM</span>
            <span class="profile-intro"
              >【メッセージ】<br />
              忙しい毎日、山のように来るタスクに追われているとなかなか自分自身を振り返る時間、自らの仕事を振り返る時間もないですよね。しかし、自分自身の振り返りや仕事の振り返りは自分らしい生き方、働き方をする上で非常に大切です。ひとりではサボってしまう「ふりかえり」を私と一緒にしてみませんか？あなたのサポートができることを楽しみにしています。お待ちしてます！
            </span>
          </div>
        </div>
      </div>
      <div class="profile-card">
        <div class="profile-card__inner">
          <div class="profile-thumb">
            <img src="image/pro4.png" />
          </div>

          <div class="profile-content">
            <div class="pro_icom">
              <div class="box">
                <i>Menter</i>
              </div>
              <span class="profile-name">中沢 惇平</span>
            </div>
            <span class="profile-job">教育関係</span>
            <span class="profile-intro"
              >【メッセージ】<br>
            最近、忙しくて毎日の「ふりかえり」ができていない。。。自分が何をしたいのか、どうなりたいのかわからなくなってしまった。そんなことをお悩みの方にこそ、MeeeLookはおすすめです。MeeeLookはメンターと一緒に「ふりかえり」を実践できるので、毎日自らの仕事を振り返る習慣が自ずと定着します。振り返りを習慣化して、新たな自分に出会いましょう
            </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      showModal: false
    };
  },
  methods: {
    click01: function(ev) {
      this.showModal = false;
      ev.preventDefault();
    }
  }
};
</script>

<style scoped>
.container {
  height: 100%;
  width: 100%;
  max-width: 1440px;
  margin: 0 auto;
}

.pro_text {
  width: 100%;
  max-width: 500px;
  color: #273240;
  font-size: 40px;
  transition: all 0.5s;
  line-height: 70px;
  font-weight: bold;
  border-bottom: 3px solid #ffffff;
  margin: 120px 0 120px 0;
}

span {
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

.profile-card {
  width: 100%;
  max-width: 360px;
  position: relative;
  background: #fff; /*背景の色*/
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.18);
  overflow: hidden;
  height: 400px;
  border-radius: 20px;
  box-shadow: 0 2px 5px #ccc;
  margin: 0 auto;
  background: rgba(255, 255, 255, 0.864);
  
}

.profile-card:before {
  width: 120%;
  height: 100px;
  content: "";
  transform: skew(15deg, 10deg);
  background: #4caf50; /*斜め背景の色*/
  position: absolute;
  top: -15%;
  left: -10%;
  z-index: 0;
}

.pro_icom {
  display: flex;
  text-align: center;
  margin-left: 90px;
}

.box {
  padding: 0.2em;
  background-color: #263440;
  width: 60px;
  text-align: center;
  margin-left: 0px;
  font-size: 14px;
  border-radius: 20px;
  margin-bottom: 3px;
}

.box i {
  text-align: center;
  color: #fff;
  font-weight: bold;
}

.profile-card__inner {
  position: relative;
}

.profile-thumb {
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

.profile-thumb img {
  display: block;
  width: 100%;
  height: auto;
}

.profile-content {
  padding: 15px;
}

.profile-content span {
  display: block;
}

.profile-name {
  margin-bottom: 3px;
  font-weight: bold;
  text-align: center;
  color: #273240;
  margin-left: 10px;
}

.profile-job {
  margin-bottom: 10px;
  color: #4caf50;
  font-size: 20px;
  text-align: center;
  font-weight: bold;
}

.profile-intro {
  font-size: 12px;
  color: #273240;
  font-weight: bold;
}

.second_stage {
  display: flex;
  justify-content: space-around;
  margin-top: 50px;
  margin-right: 50px;
}

@media (max-width: 959px) {
  .container {
    height: 100%;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
  }

  .pro_text {
    width: 260px;
    color: #273240;
    font-size: 20px;
    transition: all 0.5s;
    line-height: 40px;
    font-weight: bold;
    border-bottom: 3px solid #ffffff;
    margin-left: 30px;
    margin-top: 60px;
    margin-bottom: 100px;
  }

  /* span{
    color: #fff;

} */
  /* 
.pro_img{
width: 1450px;
position: relative;
top:100px;
left: 50px;
margin-bottom: 200px;
} */

  .profile-card {
    width: 80%;
    max-width: 320px;
    position: relative;
    background: #fff; /*背景の色*/
    box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.18);
    overflow: hidden;
    height: 400px;
    border-radius: 20px;
    box-shadow: 0 2px 5px #ccc;
    margin: 20px auto;
  }

  .profile-card:before {
    width: 120%;
    height: 100px;
    content: "";
    transform: skew(15deg, 10deg);
    background: #4caf50; /*斜め背景の色*/
    position: absolute;
    top: -15%;
    left: -10%;
    z-index: 0;
  }

  .pro_icom {
    display: flex;
    text-align: center;
    margin-left: 0px;
  }

  .box {
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

  .box i {
    text-align: center;
    color: #fff;
    font-weight: bold;
  }

  .profile-card__inner {
    position: relative;
  }

  .profile-thumb {
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

  .profile-thumb img {
    display: block;
    width: 100%;
    height: auto;
  }

  .profile-content {
    padding: 15px;
  }

  .profile-content span {
    display: block;
  }

  .profile-name {
    margin-bottom: 3px;
    font-weight: bold;
    text-align: center;
    color: #273240;
    margin-left: 10px;
  }

  .profile-job {
    margin-bottom: 10px;
    color: #4caf50;
    font-size: 20px;
    text-align: center;
    font-weight: bold;
  }

  .profile-intro {
    font-size: 12px;
    color: #273240;
    font-weight: bold;
  }

  .second_stage {
    display: flex;
    margin: 50px 30px;
    flex-direction: column-reverse;
  }
}

@media (max-width: 479px) {
  .container {
    height: 100%;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
  }

  .pro_text {
    width: 260px;
    color: #273240;
    font-size: 20px;
    transition: all 0.5s;
    line-height: 40px;
    font-weight: bold;
    border-bottom: 3px solid #ffffff;
    margin-left: 30px;
    margin-top: 60px;
    margin-bottom: 100px;
  }

  /* span{
    color: #fff;

} */
  /* 
.pro_img{
width: 1450px;
position: relative;
top:100px;
left: 50px;
margin-bottom: 200px;
} */

  .profile-card {
    width: 80%;
    max-width: 390px;
    position: relative;
    background: #fff; /*背景の色*/
    box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.18);
    overflow: hidden;
    height: 400px;
    border-radius: 20px;
    box-shadow: 0 2px 5px #ccc;
    margin-bottom: 50px;
    background: rgba(255, 255, 255, 0.864);
    display: inline-block;
    width: 90%;
  }

  .profile-card:before {
    width: 120%;
    height: 100px;
    content: "";
    transform: skew(15deg, 10deg);
    background: #4caf50; /*斜め背景の色*/
    position: absolute;
    top: -15%;
    left: -10%;
    z-index: 0;
  }

  .pro_box {
    text-align: center;
  }

  .pro_icom {
    display: flex;
  }

  .box {
    padding: 0.2em;
    background-color: #263440;
    width: 40px;
    font-size: 8px;
    border-radius: 20px;
    margin-bottom: 3px;
    line-height: 20px;
  }

  .box i {
    text-align: center;
    color: #fff;
    font-weight: bold;
  }

  .profile-card__inner {
    position: relative;
  }

  .profile-thumb {
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

  .profile-thumb img {
    display: block;
    width: 100%;
    height: auto;
  }

  .profile-content {
    padding: 15px;
  }

  .profile-content span {
    display: block;
  }

  .profile-name {
    margin-bottom: 3px;
    font-weight: bold;
    text-align: center;
    color: #273240;
    margin-left: 10px;
  }

  .profile-job {
    margin-bottom: 10px;
    color: #4caf50;
    font-size: 20px;
    text-align: center;
    font-weight: bold;
  }

  .profile-intro {
    font-size: 12px;
    color: #273240;
    font-weight: bold;
  }

  .second_stage {
    display: flex;
    flex-direction: column-reverse;
    margin-top: 50px;
  }
}
</style>
