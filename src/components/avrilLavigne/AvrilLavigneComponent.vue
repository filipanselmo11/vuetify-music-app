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
import CardComponent from "../CardComponent.vue"
export default{
  components: { CardComponent },
  name: "AvrilLavigneComponent",
  data: () => ({
    name: "Avril Lavigne",
    image: require("../../assets/avril-lavigne.jpg"),
    firstAlbum: 'Let Go',
    secondAlbum: 'Under My Skin',
    thirdAlbum: 'My World',
    fourAlbum: 'The Bes Damn Thing',
    firstItem:[
        {name: 'Losing Grip', duration: '3:54'},
        {name: 'Complicated', duration: '4:05'},
        {name: 'Sk8er Boi', duration: '3:24'},
        {name: 'Im with You', duration: '3:44'},
        {name: 'Mobile', duration: '3:32'},
        {name: 'Unwanted', duration: '3:41'},
        {name: 'Tomorrow', duration: '3:49'},
        {name: 'Anything But Ordinary', duration: '4:11'},
        {name: 'Things Ill Never Say', duration: '3:44'},
        {name: 'My World', duration: '3:27'},
        {name: 'Seed', duration: '5:55'},
        {name: 'Nobodys Fool', duration: '3:57'},
        {name: 'Top Much to Ask', duration: '3:45'},
        {name: 'Naked', duration: '3:29'},
    ],
    secondItem:[
      {name: 'Take Me Away', duration: '2:58'},
      {name: 'Together', duration: '3:15'},
      {name: 'Dont Tell Me', duration: '3:23'},
      {name: 'He Wasnt', duration: '3:00'},
      {name: 'How Does It Feel', duration: '3:45'},
      {name: 'My Happy Ending', duration: '4:02'},
      {name: 'Nobodys Home', duration: '3:32'},
      {name: 'Forgotten', duration: '3:17'},
      {name: 'Who Knows', duration: '3:30'},
      {name: 'Fall to Pieces', duration: '3:29'},
      {name: 'Freak Out', duration: '3:13'},
      {name: 'Slipped Away', duration: '3:34'},
    ],
    thirdItem:[
      {name: 'Fuel(live)', duration: '3:38'},
      {name: 'Basketcase(live)', duration: '3:04'},
      {name: 'Unwanted(live)', duration: '4:20'},
      {name: 'Sk8er Boi', duration: '4:11'},
      {name: 'Knockin on Heavers Doors', duration: '3:09'},
      {name: 'Why', duration: '4:00'},
    ],
    fourItem:[
      {name: 'Girlfriend(radio edit)', duration: '3:36'},
      {name: 'I Can Do Better', duration: '3:17'},
      {name: 'Runaway', duration: '3:49'},
      {name: 'The Best Damn Thing', duration: '3:10'},
      {name: 'When Youre Gone', duration: '4:00'},
      {name: 'Everything Back but You', duration: '3:03'},
      {name: 'Hot', duration: '3:24'},
      {name: 'Innocence', duration: '3:53'},
      {name: 'I Dont Have to Try', duration: '3:17'},
      {name: 'One of Thos Girls', duration: '2:56'},
      {name: 'Contagious', duration: '2:11'},
      {name: 'Keep Holding On', duration: '4:00'},
    ],
  }),
};
</script>

<style>
</style>