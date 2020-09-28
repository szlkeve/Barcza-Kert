<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <StartScreen></StartScreen>
 
    
    
  </div>
</template>

<script lang="ts">
import Vue from "vue";

import StartScreen from "@/components/StartScreen.vue";

export default Vue.extend({
  name: "Home",
  components: {
    StartScreen,
   
    
  }
});
</script>
