<template>
  <div id="app">
    <Text />
    <img alt="Vue logo" src="./assets/slonce.png" />
    “Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur id lorem
    non lectus bibendum consequat non vel lectus. Sed sed neque et libero
    pulvinar tempor at sit amet nulla.”
  </div>
</template>

<script>
import Text from "./components/Text.vue";

export default {
  name: "App",
  components: {
    Text,
  },
};
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
