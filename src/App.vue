<template>
  <div id="app">
    <h1>Vuex</h1>
    <Result />
    <AnotherResult />
    <hr />
    <Counter />
    <AnotherCounter />
    <hr />
  </div>
</template>

<script>
import Counter from "./components/Counter";
import AnotherCounter from "./components/AnotherCounter";
import Result from "./components/Result";
import AnotherResult from "./components/AnotherResult";

export default {
  name: "app",

  components: {
    Counter,
    AnotherCounter,
    Result,
    AnotherResult
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
