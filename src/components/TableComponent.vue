<template>
  <v-data-table
    :headers="headers"
    :items="tableItems"
    :items-per-page="5"
    class="elevation-1"
  ></v-data-table>
</template>

<script>
export default {
  name: "TableComponent",
  props:['tableItems'],
  data: () => ({
    headers: [
      {text: 'Name'},
      {text: 'Duration'},
    ],
    // localItems:[],
  }),
  // watch:{
  //   items(val) {
  //     this.localItems = val;
  //   }
  // },
};
</script>

<style>
</style>