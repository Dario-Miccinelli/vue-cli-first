<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <AppTitle/>
    <JumbotronBonus/>
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue'
import JumbotronBonus from './components/JumbotronBonus.vue'

export default {
  name: 'App',
  components: {
    AppTitle,
    JumbotronBonus
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

#Jumbo {
  width: 300px;
  height: 300px;
  background-color: black;
  margin: auto;
  color: white;
}
</style>