<template>
  <v-app>
    <v-content>
      <Navigation />
    </v-content>
  </v-app>
</template>

<script>
import Navigation from "./components/Navigation";

export default {
  name: "App",

  components: {
    Navigation
  },

  data: () => ({
    //
  })
};
</script>
<style>
v-content {
  color: blue !important;
}
</style>