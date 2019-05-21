<script src="https://cdn.jsdelivr.net/npm/vue@2.6.10/dist/vue.js"></script>


<template>
  <div id="app">
    <Nav/>
    <HelloWorld msg="Hello, W0rld!" />
  </div>
</template>

<script>

export default {
  name: 'app',
  components: {
    HelloWorld,
    Nav
  }
}
import HelloWorld from './components/HelloWorld.vue';
import Nav from './components/Nav.vue';
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #DDD;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
