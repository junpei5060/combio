<template>
    <div class="full">
        <div class="container">
            <div class="top_container">
                <h3 class="main_mess">
                    一人では
                    辿り着けない景色を
                </h3>
                <!-- <img src="image/top1.png" class="main_img"> -->
            </div>
                <span class="main_text">
                    師弟.comは、ビジネスのプロであり、マネジメントのプロでもあるプロ上司が<br>
                    あなたをトップビジネスマンへと成長させます。<br>
                    今、所属する組織での活躍、今、抱えている大きなプロジェクトの成功<br>
                    そんな未だ見たことない景色を私たちと一緒に見てみませんか？
                </span>
                <!-- <div class="btn"> -->
                <nuxt-link to="/form" class="btn_top">無料相談を予約する</nuxt-link>
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
  background: url('https://images.unsplash.com/photo-1544027993-37dbfe43562a?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=2250&q=80') top center / cover no-repeat;
}

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
width: 1440px;
margin-top: 300px;
margin-bottom: 152px;
margin-right: 0;
margin-left: 250px;
transition: all .5s;
font-size: 72px;
color:#DB0B40;
  text-shadow:
    0 0 2px rgba(204, 208, 212,0.9),
    0 15px 25px rgba(0, 0, 0, 0.3),
    0 -2px 3px rgba(0, 0, 0, 0.1),
    0 -5px 10px rgba(255, 255, 255, 0.5),
    0 5px 10px rgba(0, 0, 0, 0.3),
    0 3px 4px rgba(255, 255, 255, 0.2),
    0 0 20px rgba(255, 255, 255, 0.45);
    
  }

.main_mess:hover{
   transition: all .5s;
   color: #ffffff; 
}


/* .main_img{
width: 600px;
position: relative;
top:100px;
left: 10px;
} */

.text_btn{
display: flex;
}

.main_text{
display: flex;
color: #ffffff;
margin-left: 400px;
transition: all .5s;
font-size: 18px;
line-height: 35px;
font-weight: bold;
border-left:3px solid#DB0B40;
padding: 0.25em 1.5em;
letter-spacing: 0.1em;
  text-shadow:
0 0 2px rgba(204, 208, 212,0.9),
0 15px 25px rgba(0, 0, 0, 0.3),
0 -2px 3px rgba(0, 0, 0, 0.1),
0 -5px 10px rgba(255, 255, 255, 0.5),
0 5px 10px rgba(0, 0, 0, 0.3),
0 3px 4px rgba(255, 255, 255, 0.2),
0 0 20px rgba(255, 255, 255, 0.45);
}
/* 
.btn{
    display: flex;
} */

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
margin-top:30px;
margin-left: 600px;
}

.btn_top:hover {
background-color: #DB0B40;
transition: all .5s;
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
background-color: #DB0B40;
transition: all .5s;
}
.btn_top1:active {
top: 3px;
box-shadow: none;
} */

@media screen and (max-width: 959px) {
    .container{
    max-width: 959px;
}
.main_mess{
width: 465px;
margin-left: 53px;
font-size: 48px;
}

.main_img{
width: 400px;
height: 300px;
position: relative;
top:100px;
left: 10px;
}

.text_btn{
display: flex;
}

.main_text{
color: #273240;
margin-left: 53px;
font-size: 12px;
}

.btn_top{
border-radius: 5px;
font-size: 14px;
height: 45px;
letter-spacing: .5px;
line-height: 45px;
padding: 0 40px;
margin-top: 10px;
margin-left: 120px;
}

} /*ウィンドウ幅が最大959pxまでの場合に適用*/
/* ここまで */
</style>