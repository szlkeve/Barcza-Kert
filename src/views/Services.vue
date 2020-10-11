<template>
  <div>
    <h1 class="text-center my-8">Szolgáltatásaink</h1>
    <v-row
      ><v-flex v-for="i in 4" :key="i" xl3 lg3 md6 sm6 xs12
        ><service class="text-center"></service> </v-flex
    ></v-row>
  </div>
</template>

<script lang="ts">
import Vue from "vue";
import Service from "../components/Service.vue";

export default Vue.extend({
  name: "Services",

  components: {
    Service
  }
});
</script>

<style scoped>
</style>