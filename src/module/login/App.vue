<template>
  <div id="app">
    <img src="./images/logo.png">
    <div>login</div>
    <form>
      <input type="text" placeholder="用户名">
      <input type="password" placeholder="密码">
      <button type="button" @click="login">登陆</button>
    </form>
    <!-- <hello></hello> -->
  </div>
</template>

<script>
  import 'common/css/reset.css';
  // import Hello from 'components/Hello/Hello'

  export default {
    name: 'app',
    components: {
      // Hello
    },
    methods: {
      login: function(){
        console.log(12213)
        window.location = './index.html'
      }
    }
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }
</style>
