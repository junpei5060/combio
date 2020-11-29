<template>
    <div class="container">
        <div class="used_container">
        <h5>
            Flow
        </h5>
        <p class="used_text">
            師弟.comご利用までの流れ
        </p>
        <div class="user_btn">
        
        <img src="image/Used1.png" class="Used_img">
        <nuxt-link to="/form" class="btn_top">無料相談を予約する</nuxt-link>
        </div>
        
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

.used_container{
text-align: center;
}
h5{
width: 1000px;
transition: all .5s;
font-size: 72px;
color: #263440;
border-bottom:3px solid #263440;
margin: 0 auto;
}


.used_text{
transition: all .5s;
font-size: 32px;
font-weight: bold;
color: #263440;
}

.user_btn{
position: relative;
}

.Used_img{
width: 1200px;
position: relative;
top:30px;
border-radius: 20px;
box-shadow: 0 2px 5px #ccc;

}

.btn_top{
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
position: absolute;
margin-top: 505px;
left: 42%;
z-index: 2;
}

.btn_top:hover {
background-color: #DB0B40;
transition: all .5s;
}
.btn_top:active {
top: 3px;
box-shadow: none;
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