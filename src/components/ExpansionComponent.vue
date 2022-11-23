<template>
  <v-expansion-panels>
    <v-expansion-panel>
      <v-expansion-panel-header>
        <template v-slot:default="{ open }">
          <v-row no-gutters>
            <v-col cols="4">{{ firstAlbum }}</v-col>
            <v-col cols="8" class="text--secondary">
              <v-fade-transition leave-absolute>
                <span v-if="open" key="0">{{ firstAlbum }}</span>
              </v-fade-transition>
            </v-col>
          </v-row>
        </template>
      </v-expansion-panel-header>
      <v-expansion-panel-content>
        <table-component :tableItems="firstItem"></table-component>
      </v-expansion-panel-content>
    </v-expansion-panel>
    <v-expansion-panel>
      <v-expansion-panel-header>
        <template v-slot:default="{ open }">
          <v-row no-gutters>
            <v-col cols="4">{{ secondAlbum }}</v-col>
            <v-col cols="8" class="text--secondary">
              <v-fade-transition leave-absolute>
                <span v-if="open" key="0">{{ secondAlbum }}</span>
              </v-fade-transition>
            </v-col>
          </v-row>
        </template>
      </v-expansion-panel-header>
      <v-expansion-panel-content>
        <h1>Conteúdo</h1>
      </v-expansion-panel-content>
    </v-expansion-panel>
    <v-expansion-panel>
      <v-expansion-panel-header>
        <template v-slot:default="{ open }">
          <v-row no-gutters>
            <v-col cols="4">{{ thirdAlbum }}</v-col>
            <v-col cols="8" class="text--secondary">
              <v-fade-transition leave-absolute>
                <span v-if="open" key="0">{{ thirdAlbum }}</span>
              </v-fade-transition>
            </v-col>
          </v-row>
        </template>
      </v-expansion-panel-header>
      <v-expansion-panel-content>
        <h1>Conteúdo</h1>
      </v-expansion-panel-content>
    </v-expansion-panel>
  </v-expansion-panels>
</template>

<script>
import TableComponent from "./TableComponent.vue";
export default {
  components: { TableComponent },
  props: ["firstAlbum", "secondAlbum", "thirdAlbum"],
  name: "ExpansionComponent",
  data: () => ({
    firstItem:[
        {name: '742617000027', duration: '0:36'},
        {name: '(Sic)', duration: '3:20'},
        {name: 'Eyeless', duration: '3:56'},
        {name: 'Wait and Bleed', duration: '2:28'},
        {name: 'Surfacing', duration: '3:38'},
        {name: 'Spit It Out', duration: '2:40'},
        {name: 'Tattred & Torn', duration: '2:54'},
        {name: 'Me Inside', duration: '2:39'},
        {name: 'Liberate', duration: '3:07'},
        {name: 'Prosthetics', duration: '4:58'},
        {name: 'No Life', duration: '2:47'},
        {name: 'Diluted', duration: '3:23'},
        {name: 'Only One', duration: '2:26'},
        {name: 'Scissors', duration: '8:25'},
        {name: 'Eeyore', duration: '2:48'},
    ],
    secondItem:[],
    thirdItem:[],
  }),
};
</script>

<style>
</style>