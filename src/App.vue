<template>
  <v-app>
    <v-content>
      <Navbar />
      <router-view />
    </v-content>
  </v-app>
</template>

<script>
import Navbar from "./views/Navbar";

export default {
  name: "App",

  components: {
    Navbar
  },

  data: () => ({
    //
  })
};
</script>
