<template>
  <v-app>
    <p-toolbar />
    <v-content style="background-color: white">
      <!-- <HelloWorld /> -->
      <router-view />
    </v-content>
    <p-footer />
  </v-app>
</template>

<script>
import PToolbar from "./components/PToolbar";
import PFooter from "./components/PFooter";
// import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",

  components: {
    // HelloWorld,
    PToolbar,
    PFooter
  },

  data: () => ({
    //
  })
};
</script>
