<template>
    <div>
        <Navbar/>
    <center>
    <h1 id="contactpageheader"> Wanna contact me?</h1>
    <p class="contactpagetext">My email is
        <a href="mailto:julie.aleiner@gmail.com" target="_blank" id="personalgmaillink">
            julie.aleiner@gmail.com </a> </p>
    <p class="contactpagetext">My phone number is 347-225-1934
        </p>
            <h1 id="connectpageheader"> Wanna connect?</h1>
            <p class="contactpagetext"> Follow me on Instagram! 
            <a href="https://www.instagram.com/julie.aleiner/" target="_blank" id="instgramlink">
                <br>
                here's the link </a> </p>
            <p class="contactpagetext"> Follow me on Linkedin!
            <a href="https://www.linkedin.com/in/julie-aleiner-27931522a/" target="_blank" id="linkedinlink">
                <br>
                here's the link </a> </p>
    </center>
    </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Nunito:wght@200&display=swap');

    #contactpageheader{
        font-family:'Nunito', sans-serif;
        font-size: 40px;
    }

    #connectpageheader{
        font-family:'Nunito', sans-serif;
        font-size: 40px;
    }

    .contactpageheader{
        font-family:'Nunito', sans-serif;
        font-size: 20px;
    }
</style>

<script>
    export default{
        mounted() {
            document.body.style.backgroundColor = '#89CFF0'
        }
    }
</script>