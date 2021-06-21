<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <div id="app">
    <!-- 추가된 헤더 컴포넌트 사용 -->
    <Header />
      <HelloWorld msg="Welcome to Your Vue.js App"/>

    <!-- 추가된 푸터 컴포넌트 사용 -->
    <Footer />
  </div>
</template>

<script>
import Header from './components/common/Header.vue'
import HelloWorld from './components/HelloWorld.vue'
import Footer from './components/common/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    HelloWorld,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin: 0; padding: 0;
}
</style>
