<template>
    <div class="Navbar">
        <ul id="navlinks">
            <NuxtLink to="/" id="home"> Home</NuxtLink>
            <NuxtLink to="/contact">Contact</NuxtLink>
            <NuxtLink to="/about">About Me</NuxtLink>
        </ul>
    </div>
</template>

<style>
    #navlinks{
        display: flex; 
        justify-content: center;
        gap: 10px;
    }
</style>
