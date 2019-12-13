<template>
<div id="post-wrapper">
  <div class="toggle-block" @click="toggleBlock = !toggleBlock">Toggle Blue Block</div>
  <div class="blue-block" v-if="toggleBlock"></div>
  <p>{{ content }}</p>
  <div class="count-up" @click="count++">+1</div>
  <div class="count-down" @click="count--">-1</div>
  <p>The count is {{count}}.</p>
  <div>
    <span>Gas Mileage Calculator</span>
    <div class="fuel">
      <input name="fuel" type="text" :value="fuel"/>
      <input name="miles" type="text" value="miles"/>
      <p>
        Your gas mileage is {{ mileage }}.
      </p>
    </div>
  </div>
</div>
</template>

<script>
export default {
  data() {
    return {
      content:
        "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.",
      toggleBlock: false,
count: 0,
fuel: 0,
miles: 0,
mileage: this.miles/this.fuel,
    };
  },
  name: "Post"
};
</script>

<style>
#post-wrapper {
  padding: 1em 0;
  margin: 0 10vw;
}
p {
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  font-size: 1.5em;
}
.toggle-block {
  height: 40px;
  width: 80px;
  margin: 1em auto;
  background-color: lightgreen;
  cursor: pointer;
  font-weight: inherit;
  color: inherit;
}
.blue-block {
  height: 100px;
  width: 150px;
  background-color: blue;
  margin: auto;
}
</style>
