<template>
    <div class="nav-vue">
         <b-navbar toggleable="lg" type="dark" variant="dark">
        <img src="../assets/logo/logo-nav.png" class="logo-navbar">


    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>

      <!-- Right aligned nav items -->
      <b-navbar-nav class="ml-auto">
     
 <b-navbar-nav>
        <b-nav-item href="#about" class="nav-title">About</b-nav-item>
        <b-nav-item href="#services" class="nav-title">Services</b-nav-item>
        <b-nav-item href="#work" class="nav-title">Work</b-nav-item>
        <b-nav-item href="#contact" class="nav-title">Contact</b-nav-item>
        
      </b-navbar-nav>

       
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
    </div>
</template>
<style scoped>
@import "../assets/style/navmenu.css";
</style>