<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/burleigh-heads-surfers.jpg" />
    <NewWorld msg="Welcome to my vue app" />
  </div>
</template>

<script>
import NewWorld from "./components/NewWorld.vue";

export default {
  name: "app",
  components: {
    NewWorld
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
