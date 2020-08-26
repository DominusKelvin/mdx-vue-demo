<template>
  <div id="app">
    <my-first-mdx />
  </div>
</template>

<script>
import MyFirstMdx from "./components/MyFirstMdx.mdx";
export default {
  name: "App",
  components: {
    MyFirstMdx,
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
