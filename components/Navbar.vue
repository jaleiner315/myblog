<template>
    <div class="Navbar">
        <ul id="navlinks">
            <NuxtLink to="/" id="home"> Home</NuxtLink>
            <NuxtLink to="/contact">Contact</NuxtLink>
            <NuxtLink to="/tourist">Tourism</NuxtLink>
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
        justify-content: center;
        gap: 10px;
    }
</style>
