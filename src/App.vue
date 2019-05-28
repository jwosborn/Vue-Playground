<template>
  <div id="app">
    <Nav/>
    <Header/>
    <Title msg="Blog Title" />
    <Post />
  </div>
</template>

<script>

export default {
  name: 'app',
  components: {
    Title,
    Nav,
    Post,
    Header
  }
}
import Title from './components/Title.vue';
import Nav from './components/Nav.vue';
import Post from './components/Post.vue';
import Header from './components/Header.vue';

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
