<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
    Vuetify App Music
    </v-app-bar>
    <v-main>
      <br/>
      <home-component></home-component>
    </v-main>
  </v-app>
</template>

<script>
import HomeComponent from './components/HomeComponent.vue';
export default {
  name: 'App',
  components: {
    HomeComponent
  },

  data: () => ({
    //
  }),
};
</script>
