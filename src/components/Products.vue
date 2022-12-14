<template>
    <div class="videoGames">
        <div v-for="items in games" key="items" class="card">
            <img :src="items.image" alt="">
        <div class="container">
            <p>{{items.gameName}}</p>
            <p>{{items.price}}</p>
            <button>Buy game</button>
        </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Products',
        data() {
            return {
                games :[{
                    id: 1,
                    image:'https://i.postimg.cc/Gp7kXzTS/567922-cyberpunk-2077-xbox-one-front-cover.jpg',
                    gameName:'CyberPunk 2077',
                    price:'R800.00'
                },
                {
                    id: 2,
                    image: 'https://i.postimg.cc/26PysGM8/red-dead-redemption-2-cover-art-1.jpg',
                    gameName: 'Red Dead Redemption 2',
                    price:'R550.00'
                },
                {
                    id: 3,
                    image: 'https://i.postimg.cc/C1FVrQFV/538006-apex-legends-xbox-one-front-cover.jpg',
                    gameName: 'Apex Legends',
                    price:'Free to Play'
                },
                {
                    id: 4,
                    image: 'https://i.postimg.cc/0NGLR0Qd/AC-Mirage-cover.webp',
                    gameName: 'Assasins Creed Mirage',
                    price:'R850.00'
                }
                   
                ]
            }
        }
    }
</script>

<style scoped>
.videoGames {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
}
.card {
    width: 40%;
   
}
.container {
    padding: 2px 16px;
}

img {
    width: 15rem;
}
</style>