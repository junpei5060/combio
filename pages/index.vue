<template>
  <div>
    <AppHeader></AppHeader>
    <Main></Main>
    <Pro></Pro>
    <Point></Point>
    <Characteristic></Characteristic>
    <Used></Used>
    <Voice></Voice>
    <Footer></Footer>
  </div>
</template>

<script>
    import AppHeader from '@/components/AppHeader.vue';
    import Main from '@/components/Main.vue';
    import Pro from '@/components/ProIntroduction.vue';
    import Point from '@/components/Point.vue';
    import Characteristic from '@/components/Characteristic.vue';
    import Used from '@/components/Used.vue';
    import Voice from '@/components/Voice.vue';
    import Footer from '@/components/Footer.vue';

    export default {
        components: {
            AppHeader,
            Main,
            Pro,
            Point,
            Characteristic,
            Used,
            Voice,
            Footer
        },

    };
</script>
