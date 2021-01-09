<template>
  <div>
    <body>
      <header class="container">
            <h1>
                <a href="/" class="ppt"></a><i>kawano</i><br>
            </h1>
            <nav>
                <!-- <ul>
                    <li class="btn_top">無料相談を予約する</li>
                </ul> -->
                <nuxt-link to="/form" class="btn_top">無料相談を予約する</nuxt-link>
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
    border-bottom:1px solid #BA0527;
    box-shadow: 1px 2px #BA0527;
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

i{
  color: #DB0B40;
  font-size: 32px;
  margin: 0; padding: 0;
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
    border-radius: 20px;
    border: none;
    color: #fff;
    cursor: pointer;
    display: inline-block;
    font-size: 14px;
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
  background-color: #BA0527;
  font-weight: bold;
}
.btn_top:active {
  top: 3px;
  box-shadow: none;
}

@media  screen and (max-width: 959px) {
header {
   box-sizing: border-box;
    width: 100%;
    max-width: 100%;
    display: flex;
    flex-wrap: nowrap;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    /* padding: 15px 0; */
    overflow: hidden;
    border-bottom: 1px solid #DB0B40;
    box-shadow: 1px 2px #DB0B40;
    position: fixed;
    z-index: 2;
    background-color: #fff;
    overflow-x: hidden;
}

h1 {
margin: 0; 
padding: 0;
font-size: 16px;
display: flex;
justify-content: start;
padding-left: 20px;
}

i{
  color: #DB0B40;
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
    border-radius: 20px;
    border: none;
    color: #fff;
    cursor: pointer;
    display: inline-block;
    font-size: 10px;
    font-weight: 500;
    height: 24px;
    letter-spacing: .5px;
    line-height: 24px;
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
}


@media  screen and (max-width: 479px) {


header {
   box-sizing: border-box;
    width: 100%;
    max-width: 100%;
    display: flex;
    flex-wrap: nowrap;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
    /* padding: 15px 0; */
    overflow: hidden;
    border-bottom: 1px solid #DB0B40;
    box-shadow: 1px 2px #DB0B40;
    position: fixed;
    z-index: 2;
    background-color: #fff;
    overflow-x: hidden;
}

h1 {
margin: 0; 
padding: 0;
font-size: 16px;
display: flex;
justify-content: start;
padding-left: 5px;
}

i{
  color: #DB0B40;
  font-size: 20px;
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
    border-radius: 20px;
    border: none;
    color: #fff;
    cursor: pointer;
    display: inline-block;
    font-size: 10px;
    font-weight: 500;
    height: 24px;
    letter-spacing: .5px;
    line-height: 24px;
    padding: 0 11px;
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
}
</style>