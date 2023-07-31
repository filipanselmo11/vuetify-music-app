<template>
    <div>
        <card-component
            :name="name"
            :image-path="image"
            :first-album="firstAlbum"
            :second-album="secondAlbum"
            :third-album="thirdAlbum"
            :four-album="fourAlbum"
            :first-item="firstItem"
            :second-item="secondItem"
            :third-item="thirdItem"
            :four-item="fourItem">
        </card-component>
    </div>
</template>


<script>
import CardComponent from '../CardComponent.vue';
export default {
    name: 'SoundgardenComponent',
    components: { CardComponent },
    data: () => ({
        name: 'Soundgarden',
        image: require('../../assets/soundgarden.jpg'),
        firstAlbum: 'Superunknow',
        secondAlbum: 'Badmotorfinger',
        thirdAlbum: 'Down on the Upside',
        fourAlbum: 'Louder Than Love',
        firstItem: [
            {name: 'Black Hole Sun', duration: '5:18' },
            {name: 'Superunknown', duration: '5:06'},
            {name: 'Half', duration: '2:14'},
            {name: 'Kickstand', duration: '1:34'},
            {name: 'She Like Surprises', duration: '3:27'},
            {name: 'Like Suicide', duration: '7:02'},
            {name: 'Maliman', duration: '4:26'},
            {name: 'Let Me Drown', duration: '3:53'},
            {name: '4th Of July', duration: '5:09'},
            {name: 'Spoonman', duration: '4:06'},
            {name: 'Limo Wreck', duration: '5:47'},
        ],
        secondItem: [
            { name: 'Slaves & Bulldozers', duration: '6:56' },
            { name: 'Face Pollution', duration: '2:24' },
            { name: 'Holy Water', duration: '5:07' },
            { name: 'Somewhere', duration: '4:21' },
            { name: 'Room a Thousand Years', duration: '4:06' },
            { name: 'New Damage', duration: '5:40' },
            { name: 'Outshine', duration: '5:11' },
            { name: 'Drawing Flies', duration: '2:27' },
            { name: 'Searching With My Good Eye Closed', duration: '4:21' },
            { name: 'Mind Riot', duration: '4:49' },
            { name: 'Jesus Christ Pose', duration: '5:51' },
            { name: 'Rusty Cage', duration: '4:26' },
        ],
        thirdItem: [
            { name: 'Ty Cobb', duration: '3:05' },
            { name: 'Never The Machine Forever', duration: '3:36' },
            { name: 'Applebite', duration: '5:10' },
            { name: 'Tighter & Tighter', duration: '6:06' },
            { name: 'Pretty Noose', duration: '4:12' },
            { name: 'Boot Camp', duration: '2:59' },
            { name: 'Blow Up The Outside World', duration: '5:46' },
            { name: 'Rhinosaur', duration: '3:15' },
            { name: 'Overfloater', duration: '5:09' },
            { name: 'Burden in My Hand', duration: '4:50' },
            { name: 'No Attention', duration: '4:27' },
            { name: 'An Unkind', duration: '2:08' },
            { name: 'Dusty', duration: '4:34' },
            { name: 'Never Named', duration: '2:28' },
            { name: 'Switch Opens', duration: '3:53' },
            { name: 'Zero Chance', duration: '4:18' },
        ],
        fourItem: [
            { name: 'I Awake', duration: '4:21' },
            { name: 'Loud Love', duration: '4:57' },
            { name: 'Full On', duration: '2:42' },
            { name: 'No Wrong No Right', duration: '4:49' },
            { name: 'Hands All Over', duration: '6:00' },
            { name: 'Gun', duration: '4:42' },
            { name: 'Full on Kevin Mon', duration: '3:38' },
            { name: 'No Wrong No Right', duration: '4:49' },
            { name: 'Power Trip', duration: '4:12' },
            { name: 'Big Dumb Sex', duration: '4:11' },
            { name: 'Ugly Truth', duration: '5:27' },
            { name: 'Uncovered', duration: '4:32' },
            { name: 'Get on the Snake', duration: '3:44' },
        ],
    }),
}
</script>