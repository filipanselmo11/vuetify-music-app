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
    name: 'RamComponent',
    components: { CardComponent },
    data: () => ({
        name: 'Rage Against The Machine',
        image: require('../../assets/ram.jpg'),
        firstAlbum: 'Evil Empire',
        secondAlbum: 'Rage Against The Machine',
        thirdAlbum: 'The Battle Of Los Angeles',
        fourAlbum: 'Renegades',
        firstItem: [
            {name: 'People Of The Sun', duration: '4:18' },
            {name: 'Bulls On Parade', duration: '5:06'},
            {name: 'Vietnow', duration: '3:11'},
            {name: 'Revolver', duration: '3:09'},
            {name: 'Snakecharmer', duration: '2:20'},
            {name: 'Tire Me', duration: '4:02'},
            {name: 'Down Rodeo', duration: '4:26'},
            {name: 'Without A Face', duration: '3:21'},
            {name: 'Wind Below', duration: '3:19'},
            {name: 'Roll Right', duration: '4:30'},
            {name: 'Year Of Tha Boomerang', duration: '5:47'},
        ],
        secondItem: [
            { name: 'Bombtrack', duration: '4:03' },
            { name: 'Kiling In The Name', duration: '3:24' },
            { name: 'Take The Power Back', duration: '5:00' },
            { name: 'Settle For Nothing', duration: '4:16' },
            { name: 'Bullet In The Head', duration: '3:01' },
            { name: 'Know Your Enemy', duration: '3:45' },
            { name: 'Wake Up', duration: '5:10' },
            { name: 'Fistful Of Steel', duration: '3:10' },
            { name: 'Township Rebellion', duration: '4:07' },
            { name: 'Freedom', duration: '3:20' },
        ],
        thirdItem: [
            { name: 'Testify', duration: '3:05' },
            { name: 'Guerilla Radio', duration: '3:36' },
            { name: 'Calm Like a Bomb', duration: '5:10' },
            { name: 'Mic Check', duration: '6:06' },
            { name: 'Sleep Now In The Fire', duration: '4:12' },
            { name: 'Born Of a Broken Man', duration: '2:59' },
            { name: 'Born As Ghosts', duration: '5:46' },
            { name: 'Maria', duration: '3:15' },
            { name: 'Voice Of The Voiceless', duration: '5:09' },
            { name: 'New Millenium Homes', duration: '4:50' },
            { name: 'Ashes In The Fall', duration: '4:27' },
            { name: 'War Within a Breath', duration: '2:08' },
        ],
        fourItem: [
            { name: 'Microphone Fiend', duration: '4:21' },
            { name: 'Pistol Grip Pump', duration: '4:57' },
            { name: 'Kick Out The Jams', duration: '2:42' },
            { name: 'Renegades Of Funk', duration: '4:49' },
            { name: 'Beautiful World', duration: '6:00' },
            { name: 'Im Housin', duration: '4:42' },
            { name: 'In My Eyes', duration: '3:38' },
            { name: 'How I Could Just Kill A Man', duration: '4:49' },
            { name: 'The Ghost Of Tom Joad', duration: '4:12' },
            { name: 'Down On The Street', duration: '4:11' },
            { name: 'Street Fighting Man', duration: '5:27' },
            { name: 'Maggies Farm', duration: '4:32' },
        ],
    }),
}
</script>