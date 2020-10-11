<template>
  <v-app>
    <v-main>
      <nav-bar> </nav-bar>
      <Home></Home>
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";

import NavBar from "@/components/NavBar.vue";

import Home from "@/views/Home.vue";

export default Vue.extend({
  name: "App",
  

  components: {
    NavBar,
    Home
  },

  data: () => ({
    //
  })
});
</script>
