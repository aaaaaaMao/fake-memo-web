<template>
  <div id="app">
    <MMHeader/>
    <MMSearch/>
    <HelloWorld msg="Memo Jisho is a powerful English dictionary"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MMHeader from './components/MMHeader.vue'
import MMSearch from './components/MMSearch.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    MMHeader,
    MMSearch
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
  margin-top: 10px;
  margin-left: 420px;
  margin-right: 420px;
}
</style>
