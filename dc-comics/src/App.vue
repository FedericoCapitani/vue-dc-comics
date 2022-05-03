<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from "@/components/HeaderComponent.vue"
import Main from "@/components/MainComponent.vue"
import Footer from "@/components/FooterComponent.vue"

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
