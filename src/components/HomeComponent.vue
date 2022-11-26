<template>
  <div class="text-center">
    <div class="mt-3">
        <v-row>
            <v-col cols="4">
                <slipknot-component></slipknot-component>
            </v-col>
            <v-col cols="4">
            </v-col>
            <v-col cols="4">
            </v-col>
        </v-row>
        <!-- <v-row>
            <v-col cols="4">
                <card-component :name="fourthName" :imagePath="fourthImage"></card-component>
            </v-col>
            <v-col cols="4">
                <card-component :name="fifthName" :imagePath="fifthImage"></card-component>
            </v-col>
            <v-col cols="4">
                <card-component :name="sixName" :imagePath="sixImage"></card-component>
            </v-col>
        </v-row>
        <v-row>
            <v-col cols="4">
                <card-component :name="sevenName" :imagePath="sevenImage"></card-component>
            </v-col>
            <v-col cols="4">
                <card-component :name="eightName" :imagePath="eightImage"></card-component>
            </v-col>
            <v-col cols="4">
                <card-component :name="nineName" :imagePath="nineImage"></card-component>
            </v-col>
        </v-row> -->
    </div>
  </div>
</template>

<script>
import SlipknotComponent from './slipknot/SlipknotComponent.vue';

export default {
  components: { SlipknotComponent },
  name: "HomeComponent",
  data: () => ({
    // firstName: "Slipknot",
    // firstImage: require("../assets/slipknot.jpg"),
    // secondName: 'KoRn',
    // secondImage: require('../assets/korn.jpg'),
    // thirdName: 'Metallica',
    // thirdImage: require('../assets/metallica.jpg'),
    // fourthName: 'Slayer',
    // fourthImage: require('../assets/slayer.jpg'),
    // fifthName: 'Limp Bizkit',
    // fifthImage: require('../assets/limp-bizkit.jpg'),
    // sixName: 'Soundgarden',
    // sixImage: require('../assets/soundgarden.jpg'),
    // sevenName: 'Nirvana',
    // sevenImage: require('../assets/nirvana.jpg'),
    // eightName: 'Avril Lavigne',
    // eightImage: require('../assets/avril-lavigne.jpg'),
    // nineName: 'Linkin Park',
    // nineImage: require('../assets/linkin-park.jpg'),
  }),
};
</script>

<style>
</style>