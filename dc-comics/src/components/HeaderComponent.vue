<template>
    <div class="header">
        <nav class="navbar">
            <div class="logo">
                <img src="@/assets/img/dc-logo.png" alt="Logo DC">
            </div>
            <div class="menu">
                <a href="item.href" v-for="item in menu" :key="item.id"> {{item.text}} </a>
            </div>
        </nav>
    </div>
</template>

<style scoped>
    .navbar{
        display: flex;
        justify-content: space-around;
        margin: 0 10%;
    }
    .menu{
        display: flex;
       align-items: center;
       column-gap: 1.5rem;
    }
    .logo, .menu > a{
        padding: 1rem 0;
        text-decoration: none;
    }
    .menu > a{
        display: flex;
        align-items: center;
        font-weight: 700;
        height: 100%;
        color: black;
    }
    a:hover{
        color: #0282f9;
        border-bottom: 5px solid #0282f9;
        padding-top: calc(1rem + 5px);
    }
</style>

<script>
export default {
    name: 'HeaderComponent',
    data(){
        return {
            menu : [
                {
                    id: 1,
                    href: '#',
                    text: 'CHARACTERS'
                },
                {
                    id: 2,
                    href: '#',
                    text: 'COMICS'
                },
                {
                    id: 3,
                    href: '#',
                    text: 'MOVIES'
                },
                {
                    id: 4,
                    href: '#',
                    text: 'TV'
                },
                {
                    id: 5,
                    href: '#',
                    text: 'GAMES'
                },
                {
                    id: 6,
                    href: '#',
                    text: 'COLLECTIBLES'
                },
                {
                    id: 7,
                    href: '#',
                    text: 'VIDEOS'
                },
                {
                    id: 8,
                    href: '#',
                    text: 'FANS'
                },
                {
                    id: 9,
                    href: '#',
                    text: 'NEWS'
                },
                {
                    id: 10,
                    href: '#',
                    text: 'SHOP'
                }
            ]
        }
    }
};
</script>
