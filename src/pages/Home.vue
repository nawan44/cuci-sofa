<template>
  <div>
    <About />
    <Services />
    <Portofolio/>
  </div>
</template>
<script>
import About from "../views/About.vue";
import Services from "../views/Services.vue";
import Portofolio from "../views/Portofolio.vue";

export default {
  name: "Home",
  components: {
    About,
    Services, Portofolio
  }
};
</script>

<style></style>
