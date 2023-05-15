<template>
  <v-app>
    <v-main>
      <v-app-bar app color="primary">
        <v-toolbar-title>Most Used Words</v-toolbar-title>
      </v-app-bar>
      <HomePageVue />
    </v-main>
  </v-app>
</template>

<script>
import HomePageVue from './components/HomePage.vue';

export default {
  name: "App",

  components: { HomePageVue },

  data: () => ({
    //
  }),
};
</script>
