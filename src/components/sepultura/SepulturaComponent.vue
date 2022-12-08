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
  name: "SepulturaComponent",
  components: {CardComponent},
  data:() => ({
    name: 'Sepultura',
    image: require('../../assets/sepultura.jpg'),
    firstAlbum: 'Roots',
    secondAlbum: 'Quadra',
    thirdAlbum: 'Chaos A.D.',
    fourAlbum: 'Arise',
    firstItem: [
        {name: 'Roots Bloody Roots', duration: '3:32'},
        {name: 'Attitude', duration: '4:15'},
        {name: 'Cut-Throat', duration: '2:45'},
        {name: 'Ratamahatta', duration: '4:31'},
        {name: 'Breed Apart', duration: '4:01'},
        {name: 'Straighthate', duration: '5:22'},
        {name: 'Spit', duration: '2:46'},
        {name: 'Lookaway', duration: '5:26'},
        {name: 'Dusted', duration: '4:04'},
        {name: 'Born Stubborn', duration: '4:08'},
        {name: 'Jasco', duration: '1:58'},
        {name: 'Itsári', duration: '4:49'},
        {name: 'Ambush', duration: '4:39'},
        {name: 'Endangered Species', duration: '5:19'},
        {name: 'Dictatorshit', duration: '1:27'},
        {name: 'Canyon Jam', duration: '13:17'},
    ],
    secondItem: [
        {name: 'Isolation', duration: '4:56'},
        {name: 'Means to an End', duration: '4:27'},
        {name: 'Capital Enslavement', duration: '3:40'},
        {name: 'Ali', duration: '4:12'},
        {name: 'Raging Void', duration: '3:58'},
        {name: 'Guardians of Earth', duration: '5:11'},
        {name: 'The Pentagram', duration: '5:21'},
        {name: 'Autem', duration: '4:07'},
        {name: 'Quadra', duration: '0:47'},
        {name: 'Agony of Defeat', duration: '5:52'},
        {name: 'Tinfoll', duration: '1:12'},
        {name: 'Fear, Pain, Chaos, Suffering', duration: '4:09'},
    ],
    thirdItem:[
      {name: 'Refuse Resist', duration: '3:20'},
      {name: 'Territory', duration: '4:48'},
      {name: 'Slave New World', duration: '2:55'},
      {name: 'Amen', duration: '4:27'},
      {name: 'Kaiowas', duration: '3:44'},
      {name: 'Propaganda', duration: '3:33'},
      {name: 'Biotech Is Godzilla', duration: '1:53'},
      {name: 'Nomad', duration: '4:59'},
      {name: 'We Who Are Not as Others', duration: '3:43'},
      {name: 'Manifest', duration: '4:50'},
      {name: 'The Hunt', duration: '3:59'},
      {name: 'Clenched Fist', duration: '3:11'},
      {name: '[demonic laughing]', duration: '2:01'},
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