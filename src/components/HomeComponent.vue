<template>
  <div class="text-center">
    <div class="mt-3">
        <v-row>
            <v-col cols="4">
                <card-component :name="firstName" :imagePath="firstImage"></card-component>
            </v-col>
            <v-col cols="4">
                <card-component :name="secondName" :imagePath="secondImage"></card-component>
            </v-col>
            <v-col cols="4">
                <card-component :name="thirdName" :imagePath="thirdImage"></card-component>
            </v-col>
        </v-row>
        <v-row>
            <v-col cols="4">
                <card-component :name="firstName" :imagePath="firstImage"></card-component>
            </v-col>
            <v-col cols="4">
                <card-component :name="secondName" :imagePath="secondImage"></card-component>
            </v-col>
            <v-col cols="4">
                <card-component :name="thirdName" :imagePath="thirdImage"></card-component>
            </v-col>
        </v-row>
        <v-row>
            <v-col cols="4">
                <card-component :name="firstName" :imagePath="firstImage"></card-component>
            </v-col>
            <v-col cols="4">
                <card-component :name="secondName" :imagePath="secondImage"></card-component>
            </v-col>
            <v-col cols="4">
                <card-component :name="thirdName" :imagePath="thirdImage"></card-component>
            </v-col>
        </v-row>
    </div>
  </div>
</template>

<script>
import CardComponent from "./CardComponent.vue";

export default {
  components: { CardComponent },
  name: "HomeComponent",
  data: () => ({
    firstName: "Slipknot",
    firstImage: require("../assets/slipknot.jpg"),
    secondName: 'KoRn',
    secondImage: require('../assets/korn.jpg'),
    thirdName: 'Metallica',
    thirdImage: require('../assets/metallica.jpg'),
  }),
};
</script>

<style>
</style>