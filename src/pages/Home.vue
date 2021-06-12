<template>
  <div>
    <About />
    <Services />
  </div>
</template>
<script>
import About from "../views/About.vue";
import Services from "../views/Services.vue";

export default {
  name: "Home",
  components: {
    About,
    Services
  }
};
</script>

<style></style>
