<template>
  <div id="app">
    <v-Header></v-Header>
    <v-ToDoList></v-ToDoList>
  </div>
</template>

<script>
import ToDoList from "./components/ToDoList";
import Header from "./components/Header";
export default {
  name: "app",
  components: {
    "v-ToDoList": ToDoList,
    "v-Header": Header
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
