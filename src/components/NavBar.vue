<template>
  <div>
    <v-app-bar
      fixed
      color="accent-4"
      dark
      scroll-target="#scrolling-techniques-6"
    >
      <template>
        <v-tabs centered>
          <v-tab>Szolgáltatások</v-tab>
          <v-tab>Eddigi munkáink</v-tab>
          <v-tab>Kapcsolat</v-tab>
        </v-tabs>
      </template>
    </v-app-bar>
  </div>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "NavBar"
});
</script>

<style scoped>
</style>