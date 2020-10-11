<template>
  <v-card>
    <v-parallax
      dark
      height="800"
      class="parallax"
      src="https://cdn.vuetifyjs.com/images/parallax/material.jpg"
    >
      <v-row align="center" justify="center">
        <v-col class="text-center" cols="12">
          <h1 class="display-1 font-weight-thin mb-4">
            Barcza-Kert
          </h1>
          <h4 class="subheading">
            A TE kertészed
          </h4>
        </v-col>
      </v-row>
    </v-parallax>
  </v-card>
</template>

<script lang="ts">
import Vue from "vue";

export default Vue.extend({
  name: "StartScreen",

  data: () => ({})
});
</script>

<style lang="scss" scoped>
.parallax {
  height: 100vh;
}
</style>