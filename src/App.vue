<template>
  <div id="app">
    <MyHeader />
    <MainUno />
  </div>
</template>

<script>
import MyHeader from './components/MyHeader.vue'
import MainUno from './components/MainUno.vue'
import '@fortawesome/fontawesome-free/css/all.css'
import '@fortawesome/fontawesome-free/js/all.js'

export default {
  name: 'App',
  components: {
    MyHeader,
    MainUno
  }
}
</script>

<style lang="scss">
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
