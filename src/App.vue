<template>
  <div id="app">
    <h1>{{ title }}</h1>
    <HelloWorld />
    <!-- Use PascalCase here if that's how you named the component -->
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue"; // Adjust the path as necessary

export default {
  name: "App",
  components: { HelloWorld }, // Register the component using PascalCase
  data() {
    return {
      title: "My First Vue App",
    };
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
