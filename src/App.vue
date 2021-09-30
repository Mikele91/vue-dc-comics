<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
     <Header/>
     <main>
       <Hero/>
      <ContentsTop/>
      <ContentsBottom/>
     </main>
     <Footer/>
  </div>
</template>

<script>

// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import Hero from './components/Hero.vue'
import ContentsTop from './components/ContentsTop.vue'
import ContentsBottom from './components/ContentsBottom.vue'
import Footer from './components/Footer.vue'



export default {
  name: 'App',
  components: {
    Header,
    Hero,
    ContentsTop,
    ContentsBottom,
    Footer,
  }
}
</script>

<style lang="scss">
@import "src/assets/style/common.scss";

</style>
