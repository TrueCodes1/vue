
<template>

  <Navbar />

</template>

<script setup>

  import { RouterLink, RouterView } from "vue-router";
  import Navbar from "./components/partials/Navbar/Navbar.vue";

</script>

<style>

  @font-face {

    font-family: Poppins;
    src: url(./fonts/Poppins/Poppins-Regular.ttf);
    font-weight: regular;

  }

  #app {

    font-family: 'Poppins';

  }

</style>
