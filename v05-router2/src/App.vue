<template>
  <div id="app">
    <!--<img src="./assets/logo.png">-->
    <!--<Navlist/>-->
    <router-view/>

  </div>
</template>

<script>
// import Navlist from './components/navlist'

export default {
  name: 'App',
  // components: {Navlist},
}
</script>

<style>
/*#app {*/
  /*font-family: 'Avenir', Helvetica, Arial, sans-serif;*/
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*text-align: center;*/
  /*color: #2c3e50;*/
  /*margin-top: 60px;*/
/*}*/

  *{
    margin: 0;
  }

  a {
    text-decoration:none;
    color:#333;
  }

  .router-link-active, .active{
    color: red;
  }
</style>
