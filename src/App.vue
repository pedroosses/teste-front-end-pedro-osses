<template>
  <div id="app">
    <!-- START HEADER -->
    <header-main></header-main>
    <!-- END HEADER -->

  </div>
</template>

<script>

import HeaderMain from "@/components/Header.vue";


export default {
  name: "App",
  components: {
    HeaderMain,
  
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; 
   position: relative;
   min-height: calc(100vh - 168px);
}
</style>
