<template>
    <div class="container">
        <div class="Used_container">
        <h5>
            師弟.comの利用までの流れ
        </h5>
        <img src="image/Used1.png" class="Used_img">
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

.Used_container{
text-align: center;
}
h5{
width: 1000px;
transition: all .5s;
font-size: 72px;
border-bottom:3px solid #DB0B40;
margin: 0 auto;
}
.Used_img{
width: 1200px;
position: relative;
top:30px;
margin-bottom: 150px;
}

/* ここがレスポンシブ（ipad）対応 */
@media screen and (max-width: 959px) {
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
} /*ウィンドウ幅が最大959pxまでの場合に適用*/
/* ここまで */
</style>