
<script setup>

  import Navbar from '../components/partials/Navbar/Navbar.vue';
  import AboutInfo from '../components/partials/About/AboutInfo.vue';

</script>

<template>

  <div>

    <Navbar />
    <AboutInfo />
    <h1>
      Hellooooo
    </h1>

  </div>

</template>

<script>

  export default {

    name: 'AboutView',
    components: {

      Navbar,
      AboutInfo

    }

  }

</script>

<style>

</style>