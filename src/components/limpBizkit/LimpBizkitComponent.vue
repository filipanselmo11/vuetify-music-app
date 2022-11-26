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
  name: "LimpBizkitComponent",
  data: () => ({
    name: "Limp Bizkit",
    image: require("../../assets/limp-bizkit.jpg"),
    firstAlbum: 'Chocolate Starfish and the Hot Dog Flavored Watter',
    secondAlbum: 'Still Sucks',
    thirdAlbum: 'Three Dollar Bill, Yall',
    fourAlbum: 'Results May Vary',
    firstItem:[
        {name: 'Intro', duration: '0:48'},
        {name: 'Hot Dog', duration: '3:50'},
        {name: 'My Generation', duration: '3:41'},
        {name: 'Full Nelson', duration: '4:07'},
        {name: 'My Way', duration: '4:33'},
        {name: 'Rollin', duration: '3:34'},
        {name: 'Livin It Up', duration: '4:24'},
        {name: 'The One', duration: '5:43'},
        {name: 'Get Your Groove On', duration: '4:29'},
        {name: 'Take a Look Around', duration: '5:20'},
        {name: 'Itll Be Ok', duration: '5:06'},
        {name: 'Boiler', duration: '7:00'},
        {name: 'Hold On', duration: '5:48'},
        {name: 'Rollin', duration: '6:19'},
        {name: 'Outro', duration: '9:50'},
    ],
    secondItem:[
      {name: 'Out of Style', duration: '3:23'},
      {name: 'Dirty Rotten Bizkit', duration: '3:02'},
      {name: 'Dad Vibes', duration: '2:13'},
      {name: 'Turn It Up, Bitch', duration: '2:21'},
      {name: 'Dont Change', duration: '2:56'},
      {name: 'You Bring out the Worst in Me', duration: '3:13'},
      {name: 'Love the Hate', duration: '1:57'},
      {name: 'Barnacle', duration: '1:56'},
      {name: 'Empty Hole', duration: '1:53'},
      {name: 'Pill Popper', duration: '2:25'},
      {name: 'Snacky Poo', duration: '4:12'},
      {name: 'Goodbye', duration: '2:36'},
    ],
    thirdItem:[
      {name: 'Intro', duration: '0:48'},
      {name: 'Pollution', duration: '3:53'},
      {name: 'Counterfeit', duration: '5:08'},
      {name: 'Stuck', duration: '5:25'},
      {name: 'Nobody Loves Me', duration: '4:28'},
      {name: 'Sour', duration: '3:33'},
      {name: 'Stalemate', duration: '6:15'},
      {name: 'Clunk', duration: '4:03'},
      {name: 'Faith', duration: '3:52'},
      {name: 'Stinkfinger', duration: '3:04'},
      {name: 'Indigo Flow', duration: '2:23'},
      {name: 'Leech', duration: '2:11'},
      {name: 'Everything', duration: '16:26'},
    ],
    fourItem:[
      {name: 'Re-Entry', duration: '2:38'},
      {name: 'Eat You Alive', duration: '3:58'},
      {name: 'Gimme the Mic', duration: '3:05'},
      {name: 'Underneath the Gun', duration: '5:42'},
      {name: 'Down Another Day', duration: '4:06'},
      {name: 'Almost Over', duration: '4:39'},
      {name: 'Build a Bridge', duration: '3:57'},
      {name: 'Red Light - Green Light', duration: '3:55'},
      {name: 'The Only One', duration: '4:09'},
      {name: 'Let Me Down', duration: '4:16'},
      {name: 'Lonely World', duration: '4:34'},
      {name: 'Creamer (Radio is Dead)', duration: '4:31'},
      {name: 'Head for the Barricade', duration: '3:35'},
      {name: 'Behind Blue Eyes', duration: '4:30'},
      {name: 'Drown', duration: '3:51'},
    ],
  }),
};
</script>

<style>
</style>