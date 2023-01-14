<template>
    <div class="moviebooks">
        <Navbar/>
    <center>
        <h1 id="moviebookpageheading"> Movies I watched in 2023 and Fave Books of 2022:) </h1>
    </center>
     <div class="moviebooks">  
        <p id="moviepagecontent">During winter break, I had plenty of time on my hands to watch some movies and shows that I've always wanted to see. So this is my ranking:</p>
            <ol id="moviepagelist">
                <li data-aos="fade-right" data-aos-duration="1000">10 Things I Hate About You</li>
                <li data-aos="fade-right" data-aos-duration="1100">The Lost City</li>
                <li data-aos="fade-right" data-aos-duration="1200">Knives Out</li>
                <li data-aos="fade-right" data-aos-duration="1300">Glass Onion</li>
                <li data-aos="fade-right" data-aos-duration="1400">La La Land</li>
                <li data-aos="fade-right" data-aos-duration="1500">Fleabag</li>
                <li data-aos="fade-right" data-aos-duration="1600">The Nice Guys</li>
                <li data-aos="fade-right" data-aos-duration="1700">Something at Tiffany's</li>
                <li data-aos="fade-right" data-aos-duration="1800">Do Revenge</li>
                <li data-aos="fade-right" data-aos-duration="1900">Ginny and Georgia</li>
                <li data-aos="fade-right" data-aos-duration="2000">My Policeman</li>
            </ol>
        </div>
           <div class="moviebooks">
            <p id="bookpagecontent">I read 25 books in 2022, here are my favorites:</p>
            <ol class="booklist">
                <li data-aos="fade-right" data-aos-duration="1000">The 7 Husbands of Evelyn Hugo by Taylor Jenkins Reid</li>
                <li data-aos="fade-right" data-aos-duration="1100">Ember in the Ashes by Sabaa Tahir</li>
                <li data-aos="fade-right" data-aos-duration="1200">It Happened One Summer by Tessa Bailey</li>
                <li data-aos="fade-right" data-aos-duration="1300">Beach Read by Emily Henry</li>
                <li data-aos="fade-right" data-aos-duration="1400">The Unhoneymooners by Christina Lauren</li>
                <li data-aos="fade-right" data-aos-duration="1500">Song of Achilles by Madeline Miller</li>
                <li data-aos="fade-right" data-aos-duration="1600">Book Lovers by Emily Henry</li>
            </ol>
            </div>
            <div class="moviebooks">
            <img src="strand.ico" alt="strand pic image" width="400" height="556.2">
           </div>
            <center>
            <Footer/>
            </center>
    </div>
</template>

<style>
    @import url('https://fonts.googleapis.com/css2?family=Nunito:wght@200&display=swap');
    .moviebooks{
        font-family: 'Nunito', sans-serif;
    }
    #bookpagecontent{
        font-size: 24px;
    }
    .booklist{
        font-size: 20px;
    }
    #moviepageheading{
        font-size: 30px;
    }
    #bookpagecontent{
        font-size: 24px;
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