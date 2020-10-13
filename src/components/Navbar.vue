<template>
  <nav>
    <v-toolbar class="indigo" dark>
      <v-toolbar-title class="text-uppercase white--text">
        <span class="font-weight-light">todo</span>
        <span>ninja</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-btn icon>
        <v-app-bar-nav-icon @click="drawer = !drawer"></v-app-bar-nav-icon>
      </v-btn>
      <v-btn class="white" light>
        <span>sign out</span>
        <v-icon right>mdi-exit-to-app</v-icon>
      </v-btn>
    </v-toolbar>
    <v-navigation-drawer app
 v-model="drawer" class="grey lighten-4"  >
      test
    </v-navigation-drawer>
  </nav>
</template>
<script>
export default {
  data() {
    return {
      drawer: true,
    };
  },
};
</script>