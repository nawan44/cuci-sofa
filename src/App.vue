<template>
  <div id="app">
    <Header />
    <!--
      <router-view/>
           -->
    <Home />
    <Footer />
  </div>
</template>
<script>
import Footer from "./components/Footer.vue";
import Header from "./components/Header.vue";
import Home from "./pages/Home.vue";

export default {
  name: "App",
  components: {
    Header,
    Footer,
    Home
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
