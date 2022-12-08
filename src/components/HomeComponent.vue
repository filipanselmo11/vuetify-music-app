<template>
  <div class="text-center">
    <div class="mt-3">
        <v-row>
            <v-col cols="4" sm="4" xs="4">
                <slipknot-component></slipknot-component>
            </v-col>
            <v-col cols="4" sm="4" xs="4">
                <korn-component></korn-component>
            </v-col>
            <v-col cols="4" sm="4" xs="4">
                <avril-lavigne-component></avril-lavigne-component>
            </v-col>
        </v-row>
         <v-row>
            <v-col cols="4" sm="4" xs="4">
                <limp-bizkit-component></limp-bizkit-component>
            </v-col>
            <v-col cols="4" sm="4" xs="4">
                <linkin-park-component></linkin-park-component>
            </v-col>
            <v-col cols="4" sm="4" xs="4">
                <korn-component></korn-component>
            </v-col>
        </v-row>
         <v-row>
            <v-col cols="4" sm="4" xs="4">
                <sepultura-component></sepultura-component>
            </v-col>
            <v-col cols="4" sm="4" xs="4">
                <metallica-component></metallica-component>
            </v-col>
            <v-col cols="4" sm="4" xs="4">
                <slayer-component></slayer-component>
            </v-col>
        </v-row>
         <v-row>
            <v-col cols="4" sm="4" xs="4">
                <nirvana-component></nirvana-component>
            </v-col>
            <v-col cols="4" sm="4" xs="4">
                <soundgarden-component></soundgarden-component>
            </v-col>
            <v-col cols="4" sm="4" xs="4">
                <korn-component></korn-component>
            </v-col>
        </v-row>
    </div>
  </div>
</template>

<script>
import AvrilLavigneComponent from './avrilLavigne/AvrilLavigneComponent.vue';
import KornComponent from './korn/KornComponent.vue';
import LimpBizkitComponent from './limpBizkit/LimpBizkitComponent.vue';
import SlipknotComponent from './slipknot/SlipknotComponent.vue';
import LinkinParkComponent from './linkinPark/LinkinParkComponent.vue';
import SepulturaComponent from './sepultura/SepulturaComponent.vue';
import MetallicaComponent from './metallica/MetallicaComponent.vue';
import SlayerComponent from './slayer/SlayerComponent.vue';
import NirvanaComponent from './nirvana/NirvanaComponent.vue';
import SoundgardenComponent from './soundgarden/SoundgardenComponent.vue';

export default {
  components: {
        SlipknotComponent,
        KornComponent,
        AvrilLavigneComponent,
        LimpBizkitComponent,
        LinkinParkComponent,
        SepulturaComponent,
        MetallicaComponent,
        SlayerComponent,
        NirvanaComponent,
        SoundgardenComponent
        },
  name: "HomeComponent",
  data: () => ({
  }),
};
</script>

<style>
</style>