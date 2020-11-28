<template>
    <div class="container">
        <p class="pro_text">
        師弟.comで<br>
        あなたに最適な理想の上司が見つかります
        </p>

        <img src="image/pro1.png" class="pro_img">
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
border-bottom:3px solid #DB0B40;
margin-left: 80px;
}

.pro_img{
width: 1450px;
position: relative;
top:100px;
left: 50px;
margin-bottom: 200px;
}

@media screen and (max-width: 959px) {
  .container{
max-width: 900px;
}

.pro_text{
width: 333px;
color: #273240;
line-height: 47px;
font-size: 27px;
margin-left: 53px;
}

.pro_img{
width: 900px;
position: relative;
top:67px;
left: 33px;
margin-bottom: 133px;
}

} /*ウィンドウ幅が最大959pxまでの場合に適用*/
/* ここまで */


</style>