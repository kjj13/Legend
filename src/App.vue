<template>
  <div>
    <main-header></main-header>
    <main-img></main-img>
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <main-footer></main-footer>
  </div>
</template>

<script>
import MainHeader from './components/common/MainHeader.vue';
import MainFooter from './components/common/MainFooter.vue';
import MainImg from './components/MainImg.vue';

export default {
  name: 'App',
  components: {
    MainHeader,
    MainFooter,
    MainImg
  }
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */

</style>
