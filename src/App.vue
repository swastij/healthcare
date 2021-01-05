<template>
  <div class="container">
    
    <Nav/>
    <div class="comp-container">
      <Hero/>
      <Services/>
      <Leading/>
      <Download/>
      <Articles/>
      <Footer/>
    </div>
  </div>
</template>

<script>
import Nav from "./components/Nav.vue"
import Hero from "./components/Hero.vue"
import Services from "./components/Services.vue"
import Leading from "./components/Leading.vue"
import Download from "./components/Download.vue"
import Articles from "./components/Articles.vue"
import Footer from "./components/Footer.vue"



export default {
  name: "App",
  components: {
    Nav,
    Hero,
    Services,
    Leading,
    Download,
    Articles,
    Footer
  }
};
</script>

<style>
/* .container{
  background: #E5E5E5;
} */
.comp-container{
  width: 80%;
  margin:auto;
}
</style>
