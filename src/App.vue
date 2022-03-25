<template>
  <div id="app">
    <MyHeader />
    <MainUno />
    <MainDue />
    <MainTre />
    <MainQuattro />
    <PrimaDelFooter />
    <MyFooter />
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'

import MainUno from './components/MainUno.vue'

import MainDue from './components/MainDue.vue'

import MainTre from './components/MainTre.vue'

import MainQuattro from './components/MainQuattro.vue'

import PrimaDelFooter from './components/PrimaDelFooter.vue'

import MyFooter from './components/MyFooter.vue'



import '@fortawesome/fontawesome-free/css/all.css'
import '@fortawesome/fontawesome-free/js/all.js'

export default {
  name: 'App',
  components: {
    MyHeader,
    MainUno,
    MainDue,
    MainTre,
    MainQuattro,
    PrimaDelFooter,
    MyFooter
  },
 
}
</script>


<style lang="scss">
@import './assets/scss/main.scss';
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#app {
  /* font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
  
  font-family: Assistant,  sans-serif;

}
</style>
