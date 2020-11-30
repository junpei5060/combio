<template>
  <div class="container">
  <div class="bg"></div>
  <div class="bg bg2"></div>
  <div class="bg bg3"></div>
    <AppHeader></AppHeader>
     <Main></Main>
    <Pro></Pro>
    <About></About>
    <Point></Point>
     <Voice></Voice>
    <Characteristic></Characteristic>
    <Used></Used>
    <Footer></Footer>

  </div>
</template>

<script>
    import AppHeader from '@/components/AppHeader.vue';
    import Main from '@/components/Main.vue';
    import Pro from '@/components/ProIntroduction.vue';
    import About from '@/components/About.vue';
    import Point from '@/components/Point.vue';
     import Voice from '@/components/Voice.vue';
    import Characteristic from '@/components/Characteristic.vue';
    import Used from '@/components/Used.vue';
    import Footer from '@/components/Footer.vue';

    export default {
        components: {
            AppHeader,
            Main,
            Pro,
            About,
            Point,
            Voice,
            Characteristic,
            Used,
            Footer
        },


    };
</script>

<style scoped>
html {
  height:100%;
}

body {
  margin:0;
}

.bg {
  animation:slide 3s ease-in-out infinite alternate;
  background-image: linear-gradient(-60deg, #ffffff 50%, #DB0B40 50%);
  bottom:0;
  left:-50%;
  opacity:.5;
  position:fixed;
  right:-50%;
  top:0;
  z-index:-1;
}

.bg2 {
  animation-direction:alternate-reverse;
  animation-duration:4s;
}

.bg3 {
  animation-duration:5s;
}

@media (max-width: 479px) {
  .container{
    width: 100%;
  }
}
</style>