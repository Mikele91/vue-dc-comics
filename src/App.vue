<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
     <Header/>
     <ContentsTop/>
     <ContentsBottom/>
     <Footer/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'
import ContentsTop from './components/ContentsTop.vue'
import ContentsBottom from './components/ContentsBottom.vue'
import Footer from './components/Header.vue'



export default {
  name: 'App',
  components: {
    Header,
    ContentsTop,
    ContentsBottom,
    Footer,
  }
}
</script>

<style lang="scss">
@import "src/assets/style/common.scss";

</style>
