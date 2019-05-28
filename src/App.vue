<template>
  <div id="app">
    <Nav/>
    <HelloWorld msg="Hello, W0rld!" />
    <Post />
  </div>
</template>

<script>

export default {
  name: 'app',
  components: {
    HelloWorld,
    Nav,
    Post
  }
}
import HelloWorld from './components/HelloWorld.vue';
import Nav from './components/Nav.vue';
import Post from './components/Post.vue';
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #DDD;
  color: #2c3e50;
}
</style>
