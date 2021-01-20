<template>
  <div class="full">
    <div class="container">
      <div class="top_container">
        <h3 class="main_mess">
          一人<span>では</span> 辿り着けない景色<span>を</span>
        </h3>
        <!-- <img src="image/top1.png" class="main_img"> -->
      </div>
      <span class="main_text">
        MeeeLookは、「ふりかえり」を中心としたコーチングサービスです。<br />
        ひとりでは継続することができない「ふりかえり」を専属メンターと行います<br />
        質の高い「ふりかえり」を通じて、自らの臨むキャリアを実現しましょう
      </span>
      <!-- <div class="btn"> -->
      <div class="btn">
        <nuxt-link to="/form" class="btn_top">無料相談を予約する</nuxt-link>
      </div>
      <!-- <nuxt-link to="/form" class="btn_top1">プロ上司を見つける</nuxt-link> -->
      <!-- </div> -->
    </div>
  </div>
</template>

<style scoped>
.full {
  position: relative;
  width: 100%;
  min-height: 100vh;
  background: url("https://images.unsplash.com/photo-1515487719147-ca1044b6b1d1?ixid=MXwxMjA3fDB8MHxzZWFyY2h8OTd8fHBlYWNlfGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=60")
    top center / cover no-repeat;
}

.container {
  height: 100%;
  width: 100%;
  max-width: 1440px;
  margin: 0 auto;
}

.top_container {
  display: flex;
}

.main_mess {
  width: 1440px;
  margin-top: 250px;
  margin-bottom: 110px;
  text-align: center;
  transition: all 0.5s;
  font-size: 82px;
  color: #4caf50;
  text-shadow: 0 0 2px rgba(204, 208, 212, 0.9), 0 15px 25px rgba(0, 0, 0, 0.3),
    0 -2px 3px rgba(0, 0, 0, 0.1), 0 -5px 10px rgba(255, 255, 255, 0.5),
    0 5px 10px rgba(0, 0, 0, 0.3), 0 3px 4px rgba(255, 255, 255, 0.2),
    0 0 20px rgba(255, 255, 255, 0.45);
  animation-name: fade-in1;
  animation-duration: 4s;
  animation-timing-function: ease-out;
  animation-delay: 0s;
  animation-iteration-count: 1;
  animation-direction: normal;
  animation-fill-mode: forwards;
}
@keyframes fade-in1 {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

.main_mess:hover {
  transition: all 0.5s;
  color: #ffffff;
}

span {
  font-size: 50px;
}

/* .main_img{
width: 600px;
position: relative;
top:100px;
left: 10px;
} */

.text_btn {
  display: flex;
}

.main_text {
  width: 54%;
  display: flex;
  color: #ffffff;
  margin-left: 400px;
  transition: all 0.5s;
  font-size: 18px;
  line-height: 35px;
  font-weight: bold;
  border-left: 3px solid#4caf50;
  padding: 0.25em 1.5em;
  letter-spacing: 0.1em;
  text-shadow: 0 0 2px rgba(204, 208, 212, 0.9), 0 15px 25px rgba(0, 0, 0, 0.3),
    0 -2px 3px rgba(0, 0, 0, 0.1), 0 -5px 10px rgba(255, 255, 255, 0.5),
    0 5px 10px rgba(0, 0, 0, 0.3), 0 3px 4px rgba(255, 255, 255, 0.2),
    0 0 20px rgba(255, 255, 255, 0.45);
}
/* 
.btn{
    display: flex;
} */

.btn_top {
  background-color: #273340;
  border-radius: 20px;
  border: none;
  color: #fff;
  cursor: pointer;
  display: inline-block;
  font-size: 14px;
  font-weight: bold;
  height: 54px;
  letter-spacing: 0.5px;
  line-height: 54px;
  padding: 0 60px;
  text-align: center;
  text-decoration: none;
  white-space: nowrap;
  margin-top: 30px;
  margin-left: 600px;
  font-weight: bold;
}

.btn_top:hover {
  background-color: #4caf50;
  transition: all 0.5s;
}
.btn_top:active {
  top: 3px;
  box-shadow: none;
}
/* .btn_top1{
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
margin-top:0px;
margin-top: 50px;
margin-left: 300px;
}

.btn_top1:hover {
background-color: #4caf50;
transition: all .5s;
}
.btn_top1:active {
top: 3px;
box-shadow: none;
} */

@media (max-width: 896px) {
  .full {
    position: relative;
    width: 100%;
    max-width: 100%;
    min-height: 600px;
    background: url("https://images.unsplash.com/photo-1515487719147-ca1044b6b1d1?ixid=MXwxMjA3fDB8MHxzZWFyY2h8OTd8fHBlYWNlfGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=60")
      top center / cover no-repeat;
  }

  .container {
    height: 100%;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
  }

  .top_container {
    display: flex;
  }

  .main_mess {
    width: 100%;
    margin-top: 200px;
    margin-bottom: 70px;
    text-align: center;
    transition: all 0.5s;
    margin-left: 0;
    font-size: 26px;
    color: #4caf50;
    text-shadow: 0 0 2px rgba(204, 208, 212, 0.9),
      0 15px 25px rgba(0, 0, 0, 0.3), 0 -2px 3px rgba(0, 0, 0, 0.1),
      0 -5px 10px rgba(255, 255, 255, 0.5), 0 5px 10px rgba(0, 0, 0, 0.3),
      0 3px 4px rgba(255, 255, 255, 0.2), 0 0 20px rgba(255, 255, 255, 0.45);
  }

  .main_mess:hover {
    transition: all 0.5s;
    color: #ffffff;
  }
  .text_btn {
    display: flex;
  }

  .main_text {
    width: 59%;
    margin: 0 auto;
    display: flex;
    color: #ffffff;
    transition: all 0.5s;
    font-size: 12px;
    line-height: 20px;
    font-weight: bold;
    border-left: 3px solid#4caf50;
    padding: 0.25em 1.5em;
    letter-spacing: 0.1em;
    text-shadow: 0 0 2px rgba(204, 208, 212, 0.9),
      0 15px 25px rgba(0, 0, 0, 0.3), 0 -2px 3px rgba(0, 0, 0, 0.1),
      0 -5px 10px rgba(255, 255, 255, 0.5), 0 5px 10px rgba(0, 0, 0, 0.3),
      0 3px 4px rgba(255, 255, 255, 0.2), 0 0 20px rgba(255, 255, 255, 0.45);
  }

  .btn {
    display: flex;
    margin-top: 30px;
  }

  .btn_top {
    background-color: #273340;
    border-radius: 20px;
    border: none;
    color: #fff;
    cursor: pointer;
    display: inline-block;
    font-size: 12px;
    font-weight: 500;
    height: 54px;
    letter-spacing: 0.5px;
    line-height: 54px;
    padding: 0 30px;
    text-align: center;
    text-decoration: none;
    white-space: nowrap;
    margin: 0 auto;
  }

  .btn_top:hover {
    background-color: #4caf50;
    transition: all 0.5s;
  }
  .btn_top:active {
    top: 3px;
    box-shadow: none;
  }
}

@media (max-width: 479px) {
  .full {
    position: relative;
    width: 100%;
    max-width: 100%;
    min-height: 700px;
    background: url("https://images.unsplash.com/photo-1515487719147-ca1044b6b1d1?ixid=MXwxMjA3fDB8MHxzZWFyY2h8OTd8fHBlYWNlfGVufDB8fDB8&ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=60")
      top center / cover no-repeat;
  }

  .container {
    height: 100%;
    width: 100%;
    max-width: 100%;
    margin: 0 auto;
  }

  .top_container {
    display: flex;
  }

  .main_mess {
    width: 100%;
    margin-top: 200px;
    margin-bottom: 70px;
    text-align: center;
    transition: all 0.5s;
    margin-left: 0;
    font-size: 26px;
    color: #4caf50;
    text-shadow: 0 0 2px rgba(204, 208, 212, 0.9),
      0 15px 25px rgba(0, 0, 0, 0.3), 0 -2px 3px rgba(0, 0, 0, 0.1),
      0 -5px 10px rgba(255, 255, 255, 0.5), 0 5px 10px rgba(0, 0, 0, 0.3),
      0 3px 4px rgba(255, 255, 255, 0.2), 0 0 20px rgba(255, 255, 255, 0.45);
  }

  .main_mess:hover {
    transition: all 0.5s;
    color: #ffffff;
  }

  span {
    font-size: 14px;
  }
  .text_btn {
    display: flex;
  }

  .main_text {
    width: 80%;
    margin: 0 auto;
    display: flex;
    color: #ffffff;
    transition: all 0.5s;
    font-size: 12px;
    line-height: 20px;
    font-weight: bold;
    border-left: 3px solid#4caf50;
    padding: 0.25em 1.5em;
    letter-spacing: 0.1em;
    text-shadow: 0 0 2px rgba(204, 208, 212, 0.9),
      0 15px 25px rgba(0, 0, 0, 0.3), 0 -2px 3px rgba(0, 0, 0, 0.1),
      0 -5px 10px rgba(255, 255, 255, 0.5), 0 5px 10px rgba(0, 0, 0, 0.3),
      0 3px 4px rgba(255, 255, 255, 0.2), 0 0 20px rgba(255, 255, 255, 0.45);
  }

  .btn {
    display: flex;
    margin-top: 30px;
  }

  .btn_top {
    background-color: #273340;
    border-radius: 20px;
    border: none;
    color: #fff;
    cursor: pointer;
    display: inline-block;
    font-size: 12px;
    font-weight: 500;
    height: 54px;
    letter-spacing: 0.5px;
    line-height: 54px;
    padding: 0 30px;
    text-align: center;
    text-decoration: none;
    white-space: nowrap;
    margin: 0 auto;
  }

  .btn_top:hover {
    background-color: #4caf50;
    transition: all 0.5s;
  }
  .btn_top:active {
    top: 3px;
    box-shadow: none;
  }
}
</style>
