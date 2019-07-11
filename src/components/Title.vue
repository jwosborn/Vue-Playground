<template>
  <div class="title-wrapper">
    <h2>{{ msg }}</h2>
  </div>
</template>

<script>
export default {
  name: "Title",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h2 {
  margin: auto;
}
.title-wrapper {
  height: 500px;
  width: 95vw;
}
</style>
