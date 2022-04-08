<template>
  <div id="app">
    <h1>Bem vindo</h1>
    <Texts :dados="'Sou um component'"/>
  </div>
</template>

<script>
import Texts from './component/Texts.vue'

export default {
  name: 'App',
  components: {
    Texts
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
