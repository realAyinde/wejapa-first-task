<template>
  <div id="app">
    <MyName name="Ayinde Sodiq Ojo"/>
  </div>
</template>

<script>
import MyName from './components/MyName.vue'

export default {
  name: 'App',
  components: {
    MyName
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
  margin-top: 60px;
}
</style>
