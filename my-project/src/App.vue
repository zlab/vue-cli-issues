<template>
  <div id="app" :class="$style.app">
    <img src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
  import HelloWorld from './components/HelloWorld.vue';

  // import styles from './app.module.css';

  export default {
    name: 'app',
    components: {
      HelloWorld,
    },
  };
</script>

<style module>
/*<style module lang="less">*/
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    margin-top: 60px;
  }

  .app {
    background-image: url("./assets/bg.jpg");
    background-repeat: no-repeat;
    background-position: center 110px;
    background-size: 100%;
  }
</style>
