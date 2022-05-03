<template>
    <div class="header">
        <nav class="navbar">
            <div class="logo">
                <img src="@/assets/img/dc-logo.png" alt="Logo DC">
            </div>
            <div class="menu">
                <p>CHARACTERS</p>
                <p>COMICS</p>
                <p>MOVIES</p>
                <p>TV</p>
                <p>GAMES</p>
                <p>COLLECTIBLES</p>
                <p>VIDEOS</p>
                <p>FANS</p>
                <p>NEWS</p>
                <p>SHOP</p>
            </div>
        </nav>
    </div>
</template>

<style>
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
    .logo, .menu > p{
        padding: 1rem 0;
    }
    .menu > p{
        display: flex;
        align-items: center;
        font-weight: 700;
        height: 100%;
    }
    p:hover{
        color: blue;
        border-bottom: 5px solid blue;
        padding-top: calc(1rem + 5px);
    }
</style>