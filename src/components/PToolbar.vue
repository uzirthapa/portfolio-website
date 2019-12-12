<template>
  <v-app-bar flat absolute color="transparent" dark height="120px">
    <v-layout justify-center>
      <v-container>
        <v-layout>
          <div class="display-1 font-weight-bold">Uzir T.</div>
          <v-spacer></v-spacer>
          <v-toolbar-items class="text-right">
            <v-btn @click="$vuetify.goTo('#about',options )" text>About</v-btn>
            <v-btn @click="$vuetify.goTo('#portfolio',options )" text>My Work</v-btn>
            <v-btn @click="$vuetify.goTo('#contact',options )" text>Contact</v-btn>
          </v-toolbar-items>
        </v-layout>
      </v-container>
    </v-layout>
  </v-app-bar>
</template>

<script>
// import * as easings from "vuetify/es5/services/goto/easing-patterns";
export default {
  data() {
    return {
      options: {
        duration: 300,
        offset: 0,
        easing: "easeInOutCubic"
      }
    };
  }
};
</script>

<style>
</style>