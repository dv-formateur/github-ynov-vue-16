<template>
  <div id="app">
    <img src="./assets/logo.png">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Multiselect from 'vue-multiselect'
import axios from 'axios';
import Datepicker from 'vuejs-datepicker';


export default {
  name: 'App',
  components: {
    HelloWorld,
      Multiselect,
      axios,
      Datepicker,

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
