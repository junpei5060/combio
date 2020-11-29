<template>
    <div>
        <div class="container">
            <div class="about_container">
                <h5>
                    About
                </h5>
                <p class="about_text">
                    師弟.comってなに？
                </p>
            </div>
            <section class="card">
            <!-- <img class="card-img" src="image/point1.jpeg" alt=""> -->
            <div class="card-content">
                <p class="title">目の前のプロジェクトも
                    、<span>あなた自身も前に進む</span></p>
                <h1 class="card-title">①もう上司には悩まない</h1>
                <p class="card-text">ビジネスマンにとって非常に重要な上司や先輩の決定は運要素が強く、適切な指導が得られずに
                本来、ビジネスマンが持つ潜在可能性が引き出されていないと私たちは考えます。師弟.comではあなたに最適なプロ上司を
                マッチングしてあなたの成長角度を最大化します
                </p>
            </div>
            <div class="card-content">
                <h1 class="card-title">②個人に合わせた環境を提供</h1>
                <p class="card-text">ビジネスマンの成長にとって、「環境」は何よりも大切なものです。いくら意識を高く持っていたとしても
                社内に聞ける先輩がいない、自分と同じ悩みを抱えている人がおらず、プロジェクトが前に進まないという課題は優秀なビジネスマンであれば
                あるほど立ち塞がる壁です。師弟.comではあなたが解決したい課題に合わせて最適なプロ上司とメンタリング環境を提供することで、
                目の前のプロジェクトもあなた自身も前に進ませることができます
                </p>
            </div>
            <div class="card-content">
                <h1 class="card-title">③全てのビシネスマンになりたい姿を</h1>
                <p class="card-text">今の会社は好きだけど、なかなか成長が見込まれない、自分よりも優秀な同僚が少ないなどの悩みを抱えている
                ビジネスマンの皆さんのために師弟.comはマネジメント&ビジネスのプロであるプロ上司があなたが目指すべきゴールの設定と道のりを提案、伴走
                一人では辿り着けなかった場所に辿りつけます
                </p>
            </div>
            <nuxt-link to="/form" class="btn_top">無料相談を予約する</nuxt-link>
        </section>
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

.about_container{
text-align: center;
margin-top: 160px;
}
h5{
width: 300px;
transition: all .5s;
font-size: 72px;
color: #263440;
border-bottom:3px solid #263440;
margin: 0 auto;
}

.about_text{
transition: all .5s;
font-size: 32px;
font-weight: bold;
color: #263440;
}    

.card {
  margin: 30px auto;
  width: 800px;
  background: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px #ccc;
  height: 800px;
  border-radius: 20px;
}
.card-content {
  padding: 20px;
}

.title{
font-size: 30px;
  margin-bottom: 20px;
  text-align: center;
  color: #263440;
  font-weight: bold;
}

span{
color: #DB0B40;
}


.card-title {
  font-size: 20px;
  margin-bottom: 20px;
  text-align: center;
  color: #DB0B40;
}
.card-text {
  color: #263440;
  font-size: 15px;
  line-height: 1.9;
  font-weight: bold;
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
margin-top:30px;
margin-left: 280px;
}

.btn_top:hover {
background-color: #DB0B40;
transition: all .5s;
}
.btn_top:active {
top: 3px;
box-shadow: none;
}

</style>