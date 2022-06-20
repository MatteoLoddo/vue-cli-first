<template>
  <div id="app">
  <MyTitles></MyTitles>
  </div>
</template>

<script>
import MyTitles from './components/MyTitles.vue'

export default {
  name: 'App',
  components: {
    MyTitles
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
