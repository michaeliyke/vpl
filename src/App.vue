<template>
  <v-app>
    <nav-bar />
    <v-main><router-view/></v-main>
  </v-app>
</template>

<script>

import NavBar from "@/components/NavBar.vue";

export default {
  name: "App",
  components: {
    NavBar,
  },
};
</script>

<style>
.v-main{
  width: 100%;
}
</style>
