<template>
    <div class="container">
        <div class="Characteristic_container">
        <h5>
            師弟.comの特徴
        </h5>
        <img src="image/Characteristic1.png" class="Characteristic_img">
        <img src="image/Characteristic2.png" class="Characteristic_img">
        <img src="image/Characteristic3.png" class="Characteristic_img" id="Characteristic_img3">
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

.Characteristic_container{
text-align: center;
}
h5{
width: 600px;
transition: all .5s;
font-size: 72px;
border-bottom:3px solid #DB0B40;
margin: 0 auto;
}
.Characteristic_img{
width: 1200px;
position: relative;
top:30px;
}
#Characteristic_img3{
margin-bottom: 150px;
}

@media screen and (max-width: 959px) {
  .container{
max-width: 959px;
}
h5{
width: 400px;
font-size: 48px;
}
.Characteristic_img{
width: 800px;
}

} /*ウィンドウ幅が最大959pxまでの場合に適用*/
/* ここまで */

</style>