<template>
  <div id="app">
    <MMHeader/>
    <HelloWorld msg="Memo Jisho is a powerful English dictionary"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MMHeader from './components/MMHeader.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MMHeader
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
  margin-top: 30px;
}
</style>
