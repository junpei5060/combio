<template>
  <div>
    <body>
      <header>
            <h1>
                <a href="/" class="ppt"></a>Cambio<br>
            </h1>
            <nav class="pc-nav">
                <!-- <ul>
                    <li class="btn_top">無料相談を予約する</li>
                </ul> -->
                <nuxt-link to="/" class="btn_top">無料相談を予約する</nuxt-link>
            </nav>
        </header>
    </body>
  </div>
</template>

<script>
</script>

<style scoped>

header {
    width: 100%;
    display: flex;
    flex-wrap: nowrap;
    flex-direction: row;
    align-items: center;
    justify-content: space-between; 
    padding: 10px 64px;
    overflow: hidden;
    border-bottom:1px solid #707070;
    box-shadow: 1px 2px #707070;
    position: fixed;
    z-index: 2;
    background-color: #fff;
}

h1 {
margin: 0; padding: 0;
font-size: 32px;
display: flex;
justify-content: start;
}

nav {
margin: 0 0 0 auto;
}
ul {
list-style: none;
margin: 0 auto;
display: flex;
font-weight: bold;
}
li {
margin: 0;
font-size: 20px;
font-weight: bold;
text-decoration: none;
color: #666666;
display: flex;
justify-content: end;
}
v-enter-active, .v-leave-active {
  transition: opacity .5s;
}
.v-enter, .v-leave-to {
  opacity: 0;
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
    height: 36px;
    letter-spacing: .5px;
    line-height: 36px;
    padding: 0 16px;
    text-align: center;
    text-decoration: none;
    transition: background-color .15s,color .15s ease-in-out;
    white-space: nowrap;
}

.btn_top:hover {
  background-color: #DB0B40;
}
.btn_top:active {
  top: 3px;
  box-shadow: none;
}
/* スマホ対応 */
@media screen and (max-width: 479px) { /*ウィンドウ幅が最大479pxまでの場合に適用*/
body{
  overflow:hidden;
}


header {
padding: 30px 4% 10px;
position: fixed;
top: 0;
width: 100%;
background-color: transparent;
display: flex;
align-items: center;
z-index: 2;
}

h1{
margin: 0; padding: 0;
font-size: 16px;
}

ul{
list-style: none;
display: flex;
margin-right: 100px;
font-weight: bold;
}

li{
font-size: 12px;
}
}


</style>