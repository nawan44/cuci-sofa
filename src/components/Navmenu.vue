<template>
  <div class="nav-vue">
    <b-navbar toggleable="sm" class=" fixed-top">
      <img src="../assets/logo/logo-nav.png" class="logo-navbar" />
      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav class="nav-link">
          <b-nav-item href="#about" class="nav-title">About</b-nav-item>
          <b-nav-item href="#services" class="nav-title">Services</b-nav-item>
          <b-nav-item href="#work" class="nav-title">Work</b-nav-item>
          <b-nav-item href="#contact" class="nav-title">Contact</b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>
<style scoped>
@import "../assets/style/navmenu.css";
.navbar.navbar-toggler.icon-bar {
  background: white !important;
}

@media only screen and (max-width: 990px) {
  .navbar {
    padding: 0.5rem !important;
  }
  .nav-link {
    margin: 0 10px 0 10px;
  }
}
</style>
