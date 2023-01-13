<template>
    <div>
        <Navbar/>
    <center>
        <h1 id="moviepageheading"> Movies I watched in 2023 :) </h1>
    </center>
        <p id="moviepagecontent">During winter break, I had plenty of time on my hands to watch some movies and shows that I've always wanted to see. So this is my ranking:</p>
            <ol id="moviepagelist">
                <li data-aos="fade-right" data-aos-duration="1000">10 Things I Hate About You</li>
                <li data-aos="fade-right" data-aos-duration="1250">The Lost City</li>
                <li data-aos="fade-right" data-aos-duration="1500">Knives Out</li>
                <li data-aos="fade-right" data-aos-duration="1750">Glass Onion</li>
                <li data-aos="fade-right" data-aos-duration="2000">La La Land</li>
                <li data-aos="fade-right" data-aos-duration="2250">Fleabag</li>
                <li data-aos="fade-right" data-aos-duration="2500">The Nice Guys</li>
                <li data-aos="fade-right" data-aos-duration="3750">Something at Tiffany's</li>
                <li data-aos="fade-right" data-aos-duration="4000">Do Revenge</li>
                <li data-aos="fade-right" data-aos-duration="5500">Ginny and Georgia</li>
                <li data-aos="fade-right" data-aos-duration="6000">My Policeman</li>
            </ol>
    </div>
</template>

<style>

    #moviepageheading{
        font-size: 30px;
    }
    #moviepagecontent{
        font-size: 24px;
    }
    #moviepagelist{
        font-size: 20px;
    }
</style>

<script>
import Vue from 'vue'
import aosMixin from '~/mixins/aos'
export default{
    mixins: [aosMixin]
}
</script>