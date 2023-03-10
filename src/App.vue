<template>
  <div id="app">

    <header-main></header-main>

    <history-main></history-main>

    <section id="content">
      <BolsasFavoritas/>
    </section>

    <footer-main></footer-main>
    
  </div>
</template>

<script>

import HeaderMain from "@/components/Header.vue";
import HistoryMain from "@/components/Menu.vue";
import FooterMain from "@/components/Footer.vue";
import BolsasFavoritas from "./views/BolsasFavoritas.vue";



export default {
  name: "App",
  components: {
    HeaderMain,
    HistoryMain,
    BolsasFavoritas,
    FooterMain,
 

  
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
