<template>
  <div id="app">
    <HeaderBar/>
    <div class="main-section columns">
      <main class="column">
        <Heroes/>
      </main>
    </div>
  </div>
</template>

<script>
import HeaderBar from "./components/header-bar";
import Heroes from "./components/heroes";

export default {
  name: "App",
  components: { HeaderBar, Heroes }
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