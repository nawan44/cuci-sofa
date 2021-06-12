<template>
  <div id="app">
    <Header />
    <!--
      <router-view/>
           -->
    <Home />
    <AppFooter />
  </div>
</template>
<script>
import Header from "./components/Header";

import Home from "./pages/Home";
import AppFooter from "./components/Footer";
export default {
  name: "App",
  components: {
    Header,
    Home, AppFooter
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
* {
  padding: 0;
  margin: 0;
}
</style>
