<script src="https://cdn.jsdelivr.net/npm/vue@2.6.10/dist/vue.js"></script>


<template>
  <div id="app">
    <HelloWorld msg="Hello, W0rld!" />
    <ItWorks/>
  </div>
</template>

<script>

export default {
  name: 'app',
  components: {
    ItWorks,
    HelloWorld
  }
}
import ItWorks from './ItWorks.vue';
import HelloWorld from './components/HelloWorld.vue';
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
