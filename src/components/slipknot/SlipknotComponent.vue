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
      :fourItem="fourItem"></card-component>
  </div>
</template>

<script>
import CardComponent from "../CardComponent.vue"

export default{
  components: { CardComponent },
  name: "SlipknotComponent",
  data: () => ({
    name: "Slipknot",
    image: require("../../assets/slipknot.jpg"),
    firstAlbum: 'Slipknot',
    secondAlbum: 'IOWA',
    thirdAlbum: 'The End So Far',
    fourAlbum: '.5: The Gray Chapter',
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
    secondItem:[
      {name: '(515)', duration: '1:00'},
      {name: 'People = Shit', duration: '3:36'},
      {name: 'Disasterpiece', duration: '5:08'},
      {name: 'My Plague', duration: '3:40'},
      {name: 'Everything Ends', duration: '4:14'},
      {name: 'The Heretic Anthem', duration: '4:00'},
      {name: 'Gently', duration: '4:54'},
      {name: 'Left Behind', duration: '4:01'},
      {name: 'The Shape', duration: '3:38'},
      {name: 'I Am Hated', duration: '2:38'},
      {name: 'Skin Ticket', duration: '6:41'},
      {name: 'New Abortion', duration: '3:37'},
      {name: 'Metabolic', duration: '3:59'},
      {name: 'IOWA', duration: '15:03'},
    ],
    thirdItem:[
      {name: 'Adderall', duration: '5:40'},
      {name: 'The Dying Song (Time to Sing)', duration: '3:24'},
      {name: 'The Chapeltown Rag', duration: '4:49'},
      {name: 'Yen', duration: '4:44'},
      {name: 'Hivemind', duration: '5:16'},
      {name: 'Warranty', duration: '3:51'},
      {name: 'Medicine for the Dead', duration: '6:16'},
      {name: 'Acidic', duration: '4;51'},
      {name: 'Heirloom', duration: '3:31'},
      {name: 'H377', duration: '4;23'},
      {name: 'De Sade', duration: '5:40'},
      {name: 'Finale', duration: '5:07'},
    ],
    fourItem:[
      {name: 'XIX', duration: '3:10'},
      {name: 'Sarcastrophe', duration: '5:06'},
      {name: 'AOV', duration: '5:33'},
      {name: 'The Devil in I', duration: '5:43'},
      {name: 'Killpop', duration: '3:45'},
      {name: 'Skeptic', duration: '4:47'},
      {name: 'Lech', duration: '4:50'},
      {name: 'Goodbye', duration: '4:35'},
      {name: 'Nomadic', duration: '4:18'},
      {name: 'The One That Kills the Least', duration: '4:12'},
      {name: 'Custer', duration: '4:14'},
      {name: 'Be Prepaered for Hell', duration: '1:58'},
      {name: 'The Negative One', duration: '5:25'},
      {name: 'If Rains is What You want', duration: '6:21'},
      {name: 'Override', duration: '5:37'},
      {name: 'The Burden', duration: '5:23'},
    ],
  }),
};
</script>

<style>
</style>