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
  name: "MetallicaComponent",
  components: {CardComponent},
  data:() => ({
    name: 'Metallica',
    image: require('../../assets/metallica.jpg'),
    firstAlbum: '...And Justice for All',
    secondAlbum: 'Master of Puppets',
    thirdAlbum: 'Death Magnetic',
    fourAlbum: 'S&M',
    firstItem: [
        {name: 'Blackened', duration: '6:42'},
        {name: '...And Justice for All', duration: '9:46'},
        {name: 'Eye of the Beholder', duration: '6:26'},
        {name: 'One', duration: '7:26'},
        {name: 'The Shortest Straw', duration: '6:35'},
        {name: 'Havester of Sorrow', duration: '5:45'},
        {name: 'The Frayed Ends of Sanity', duration: '7:43'},
        {name: 'To Live Is to Die', duration: '9:48'},
        {name: 'Dyers Eve', duration: '5:13'},
    ],
    secondItem: [
        {name: 'Battery', duration: '5:12'},
        {name: 'Master of Puppets', duration: '8:35'},
        {name: 'The Thing That Should N...', duration: '6:36'},
        {name: 'Welcome Home (Sanitarium)', duration: '6:27'},
        {name: 'Disposable Heroes', duration: '8:17'},
        {name: 'Leper Messiah', duration: '5:40'},
        {name: 'Orion', duration: '8:12'},
        {name: 'Damage, Inc', duration: '5:08'},
    ],
    thirdItem:[
      {name: 'That Was Just Your Life', duration: '7:08'},
      {name: 'The End of the Line', duration: '7:52'},
      {name: 'Broken, Beat & Scarred', duration: '6:25'},
      {name: 'The Day That Never Comes', duration: '7:56'},
      {name: 'All Nightrame Long', duration: '7:58'},
      {name: 'Cyanide', duration: '6:40'},
      {name: 'The Unforgivem 3', duration: '7:47'},
      {name: 'The Judas Kiss', duration: '8:01'},
      {name: 'Suicide & Redemption', duration: '9:58'},
      {name: 'My Apocalypse', duration: '5:01'},
    ],
    fourItem:[
      {name: 'Arise', duration: '3:18'},
      {name: 'Dead Embryonic', duration: '4:52'},
      {name: 'Desperate Cry', duration: '6:41'},
      {name: 'Murder', duration: '3:26'},
      {name: 'Subtraction', duration: '4:48'},
      {name: 'Altered State', duration: '6:34'},
      {name: 'Under Siege (Regnum Irae)', duration: '4:54'},
      {name: 'Meaningles Movements', duration: '4:41'},
      {name: 'Infected Voice', duration: '3:19'},
    ],
  }),
};
</script>

<style>
</style>