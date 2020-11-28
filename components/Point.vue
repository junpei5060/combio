<template>
    <div class="container">
        <div class="point_container">
        <h5>
            Point
        </h5>
        <p class="pro_text">
            師弟.comだからできること
        </p>
        <img src="image/point1.png" class="point_img">
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
}
h5{
width: 300px;
transition: all .5s;
font-size: 72px;
border-bottom:3px solid #DB0B40;
margin: 0 auto;
}

.pro_text{
transition: all .5s;
font-size: 32px;
font-weight: bold;
}

.point_img{
width: 1200px;
position: relative;
top:30px;
margin-bottom: 150px;
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

</style>