<template>
  <v-data-table
    :headers="headers"
    :items="tableItems"
    :items-per-page="5"
    class="elevation-1"
  >
    <template v-slot:body="{ items }">
      <tbody>
        <tr v-for="(item, index) in items" :key="index">
          <td>
            <span>{{item.name}}</span>
          </td>
          <td>
            <span>{{item.duration}}</span>
          </td>
        </tr>
      </tbody>
    </template>
  </v-data-table>
</template>

<script>
export default {
  name: "TableComponent",
  props: ["tableItems"],
  data: () => ({
    headers: [{ text: "Name" }, { text: "Duration" }],
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