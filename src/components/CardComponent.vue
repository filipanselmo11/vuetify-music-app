<template>
  <v-card class="mx-auto" max-width="344" color="color13">
    <v-img :src="imagePath" width="480"></v-img>
    <v-card-title style="color:#FFF323;">{{ name }}</v-card-title>
    <v-card-actions>
        <v-dialog v-model="dialog" fullscreen hide-overlay transition="dialog-bottom-transition">
            <template v-slot:activator="{ on, attrs}">
                <v-btn text v-bind="attrs" v-on="on" color="accent">
                    Abrir
                </v-btn>
            </template>
            <v-card>
                <v-toolbar dark color="color9">
                    <v-btn icon dark @click="dialog = false" color="color19">
                        <v-icon>mdi-close</v-icon>
                    </v-btn>
                    <v-toolbar-title style="color:#000000;">{{name}}</v-toolbar-title>
                </v-toolbar>
                <v-card-text class="mt-4">
                    <expansion-component
                        :firstAlbum="firstAlbum"
                        :secondAlbum="secondAlbum"
                        :thirdAlbum="thirdAlbum"
                        :fourAlbum="fourAlbum"
                        :firstItem="firstItem"
                        :secondItem="secondItem"
                        :thirdItem="thirdItem"
                        :fourItem="fourItem"></expansion-component>
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
    firstAlbum: {
      type: String,
      default: "",
    },
    secondAlbum: {
      type: String,
      default: "",
    },
    thirdAlbum: {
      type: String,
      default: "",
    },
    fourAlbum: {
      type: String,
      default: "",
    },
    firstItem: {
      type: Array,
    },
    secondItem: {
      type: Array,
    },
    thirdItem: {
      type: Array,
    },
    fourItem: {
      type: Array,
    },
  },
  data: () => ({
    dialog: false,
  }),
};
</script>

<style>
</style>