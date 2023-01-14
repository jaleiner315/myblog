<template>
    <div class="Navbar">
        <NuxtLink to="/" id="home"> julie aleiner</NuxtLink>
        <ul id="navlinks">
            <NuxtLink to="/experiences">Experience</NuxtLink>
            <NuxtLink to="/tourist">Tourism</NuxtLink>
            <NuxtLink to="/Moviesbooks">Movies and Books</NuxtLink>
            <NuxtLink to="/contact">Contact</NuxtLink>
        </ul>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@200&display=swap');

.Navbar{
    font-size: 20px;
    font-family:'Nunito', sans-serif;
}
    #navlinks{
        display: flex; 
        justify-content: right;
    }
    #navlinks a{
        text-decoration: none;
        color: black;
        padding: 25px;
    }

    #home{
        float: left;
        text-decoration: none;
        font-size: 50px;
    }
    #home{
        display: flex;
        align-items: center;
        margin-left: 10px;
        color: black;
        font-weight: bold;
    }
    
</style>
