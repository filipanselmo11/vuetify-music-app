<template>
  <div>
    <card-component
      :name="name"
      :imagePath="image"
      :firstAlbum="firstAlbum"
      :secondAlbum="secondAlbum"
      :thirdAlbum="thirdAlbum"
      :fourAlbum="fourAlbum"
      :firstItem="firstItem"
      :secondItem="secondItem"
      :thirdItem="thirdItem"
      :fourItem="fourItem"
    ></card-component>
  </div>
</template>

<script>
import CardComponent from '../CardComponent.vue';
export default {
  name: "LinkinParkComponent",
  components: {CardComponent},
  data:() => ({
    name: 'Linkin Park',
    image: require('../../assets/linkin-park.jpg'),
    firstAlbum: 'Meteora',
    secondAlbum: 'Living Things',
    thirdAlbum: '',
    fourAlbum: '',
    firstItem: [
        {name: 'Foreword', duration: '0:13'},
        {name: 'Dont Stay', duration: '3:08'},
        {name: 'Somewhere I Belong', duration: '3:34'},
        {name: 'Lying from You', duration: '3:00'},
        {name: 'Hit the Floor', duration: '2:44'},
        {name: 'Easier to Run', duration: '3:24'},
        {name: 'Faint', duration: '2:42'},
        {name: 'Figure 09', duration: '3:00'},
        {name: 'Breaking the Habit', duration: '3:16'},
        {name: 'From the Inside', duration: '3:12'},
        {name: 'Nobody Listening', duration: '2:59'},
        {name: 'Session', duration: '2:00'},
        {name: 'Numb', duration: '3:07'},
    ],
    secondItem: [
        {name: 'Lost In the Echo', duration: '3:28'},
        {name: 'In My Remains', duration: '3:21'},
        {name: 'Burn it Down', duration: '3:50'},
        {name: 'Lies Greed Misery', duration: '2:27'},
        {name: 'Ill Be Gone', duration: '3:31'},
        {name: 'Castle of Glass', duration: '3:25'},
        {name: 'Victimized', duration: '1:46'},
        {name: 'Roads Untraveled', duration: '3:50'},
        {name: 'Skin to Bone', duration: '2:48'},
        {name: 'Until It Breakes', duration: '3:43'},
        {name: 'Tinfoll', duration: '1:12'},
        {name: 'Powerless', duration: '3:44'},
    ],
    thirdItem:[],
    fourItem:[],
  }),
};
</script>

<style>
</style>