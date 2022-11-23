<template>
  <v-card class="mx-auto" max-width="344">
    <v-img :src="imagePath" width="480"></v-img>
    <v-card-title>{{ name }}</v-card-title>
    <v-card-actions>
        <v-dialog v-model="dialog" fullscreen hide-overlay transition="dialog-bottom-transition">
            <template v-slot:activator="{ on, attrs}">
                <v-btn text v-bind="attrs" v-on="on">
                    OK
                </v-btn>
            </template>
            <v-card>
                <v-toolbar dark color="primary">
                    <v-btn icon dark @click="dialog = false">
                        <v-icon>mdi-close</v-icon>
                    </v-btn>
                    <v-toolbar-title>{{name}}</v-toolbar-title>
                </v-toolbar>
                <v-card-text class="mt-4">
                    <expansion-component
                        :firstAlbum="firstAlbum"
                        :secondAlbum="secondAlbum"
                        :thirdAlbum="thirdAlbum"></expansion-component>
                </v-card-text>
            </v-card>
        </v-dialog>
    </v-card-actions>
  </v-card>
</template>

<script>
import ExpansionComponent from './ExpansionComponent.vue';
export default {
  components: { ExpansionComponent },
  name: "CardComponent",
  props: {
    name: {
      type: String,
      default: "",
    },
    imagePath: {
      type: String,
    },
  },
  data: () => ({
    dialog: false,
    firstAlbum: 'Slipknot',
    secondAlbum: 'IOWA',
    thirdAlbum: 'The End So Far',
  }),
};
</script>

<style>
</style>