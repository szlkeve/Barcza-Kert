<template>
  <div>
    <StartScreen />
    <Services></Services>
    <Reference></Reference>
    <About></About>
    <contact></contact>
    <Footer></Footer>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import StartScreen from "@/components/StartScreen.vue";
import About from "@/views/About.vue";
import Services from "@/views/Services.vue";
import Contact from "@/views/Contact.vue";
import Footer from "@/views/Footer.vue";
import Reference from "@/views/Reference.vue"


export default {
  name: "Home",
  components: {
    StartScreen,
    About,
    Services,
    Contact,
    Footer,
    Reference
  }
};
</script>


<style scoped>
</style>