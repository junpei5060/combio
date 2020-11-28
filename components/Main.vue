<template>
    <div class="container">
        <div class="top_container">
            <h3 class="main_mess">
                一人では<br>
                辿り着けない景色を
            </h3>
            <img src="image/top1.png" class="main_img">
        </div>
        <div class="text_btn">
            <span class="main_text">
                Cambioは、ビジネスのプロであり、マネジメントのプロでもあるプロ上司が<br>
                あなたをトップビジネスマンへと成長させます。<br>
                今、所属する組織であなたが活躍する姿を想像してみてください<br>
                そんな未来をお届けします。(要検討)
            </span>
            <nuxt-link to="/form" class="btn_top">無料相談を予約する</nuxt-link>
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

.top_container{
display: flex;
}

.main_mess{
width: 700px;
margin-top: 130px;
margin-bottom: 172px;
margin-right: 0;
margin-left: 80px;
transition: all .5s;
font-size: 72px;
}

.main_img{
width: 600px;
position: relative;
top:100px;
left: 10px;
}

.text_btn{
display: flex;
}

.main_text{
color: #273240;
margin-bottom: 200px;
margin-left: 80px;
transition: all .5s;
font-size: 18px;
line-height: 35px;
font-weight: bold;
border-left:3px solid #DB0B40;
padding: 0.25em 1.5em;
}

.btn_top{
background-color: #273340;
border-radius: 5px;
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
margin-top: 120px;
margin-left: 200px;
}

.btn_top:hover {
background-color: #DB0B40;
}
.btn_top:active {
top: 3px;
box-shadow: none;
}
</style>