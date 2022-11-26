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
  name: "KornComponent",
  data: () => ({
    name: "Korn",
    image: require("../../assets/korn.jpg"),
    firstAlbum: 'Follow the Leader',
    secondAlbum: 'Issues',
    thirdAlbum: 'Korn',
    fourAlbum: 'Untitled',
    firstItem:[
        {name: 'Its On', duration: '4:30'},
        {name: 'Freak On a Leash', duration: '4:16'},
        {name: 'Got the Life', duration: '3:45'},
        {name: 'Dead Bodies Everywhere', duration: '4:45'},
        {name: 'Children of the Korn', duration: '3:53'},
        {name: 'B.B.K', duration: '3:57'},
        {name: 'Pretty', duration: '4:13'},
        {name: 'All In the Family', duration: '4:49'},
        {name: 'Reclaim My Place', duration: '4:33'},
        {name: 'Justin', duration: '4:18'},
        {name: 'Seed', duration: '5:55'},
        {name: 'Cameltosis', duration: '4:38'},
        {name: 'My Gift to You', duration: '7:16'},
        {name: 'Earache My Eye', duration: '6:27'},
    ],
    secondItem:[
      {name: 'Dead', duration: '1:12'},
      {name: 'Falling Away from Me', duration: '4:31'},
      {name: 'Trash', duration: '3:27'},
      {name: '4U', duration: '1:42'},
      {name: 'Beg for Me', duration: '3:54'},
      {name: 'Make Me Bad', duration: '3:55'},
      {name: 'Its Gonna Go Away', duration: '1:31'},
      {name: 'Wake Up', duration: '4:08'},
      {name: 'Am I Going Crazy', duration: '0:59'},
      {name: 'Hey Daddy', duration: '3:44'},
      {name: 'Somebody Someone', duration: '3:47'},
      {name: 'No Way', duration: '4:08'},
      {name: 'Lets Get This Party Started', duration: '3:41'},
      {name: 'Wish You Could Be Me', duration: '1:07'},
      {name: 'Counting', duration: '3:38'},
      {name: 'Dirty', duration: '3:03'},
    ],
    thirdItem:[
      {name: 'Blind', duration: '4:19'},
      {name: 'Ball Tongue', duration: '4:29'},
      {name: 'Need To', duration: '4:02'},
      {name: 'Clown', duration: '4:37'},
      {name: 'Divine', duration: '2:51'},
      {name: 'Faget [Explicit]', duration: '5:50'},
      {name: 'Shoots and Ladders', duration: '5:23'},
      {name: 'Predictable', duration: '4:33'},
      {name: 'Fake', duration: '4:51'},
      {name: 'Lies', duration: '3:22'},
      {name: 'Helmet In The Bush', duration: '4:03'},
    ],
    fourItem:[
      {name: 'Intro', duration: '1:57'},
      {name: 'Starting Over', duration: '4:02'},
      {name: 'Bitch We Got a Problem', duration: '3:23'},
      {name: 'Evolution', duration: '3:38'},
      {name: 'Hold On', duration: '3:06'},
      {name: 'Kiss', duration: '4:10'},
      {name: 'Do What They Say', duration: '4:17'},
      {name: 'Ever Be', duration: '4:49'},
      {name: 'Love & Luxury', duration: '3:01'},
      {name: 'Innocent Bystander', duration: '3:28'},
      {name: 'Killing', duration: '3:37'},
      {name: 'Hushabye', duration: '3:53'},
      {name: 'The Negative One', duration: '5:25'},
      {name: 'I Will Protect You', duration: '5:33'},
    ],
  }),
};
</script>

<style>
</style>