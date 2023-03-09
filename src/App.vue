<template>
  <div id="app">

    <header-main></header-main>

    <history-main></history-main>

    <section id="modal-content">
      <router-view />
    </section>

    <footer-main></footer-main>
    
  </div>
</template>

<script>

import HeaderMain from "@/components/Header.vue";
import FooterMain from "@/components/Footer.vue";
import HistoryMain from "@/components/Menu.vue";


export default {
  name: "App",
  components: {
    HeaderMain,
    FooterMain,
    HistoryMain,

  
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
