<template>
    <div id="pagesection">
        <img src="" alt="" id="pagesectionimg">
        <h1 id="pagesectionheading"></h1>
        <p id="pagesectiontext"></p>
    </div>
</template>

<style>
    #pagesection{
        display: flex;
        flex-direction: column;
        padding: 20px;
        border: 1px solid black;
        border-radius: 5px;
        margin: 40px;
        align-items: center;
        justify-content: center;
    }

    #pagesectionimg{
        width: 250px;
    }

    #pagesectionheading{
        font-size: 30px;
        font-weight: bold;
        font-family: Helvetica;
        color: black;
    }

    #pagesectiontext{
        color: rgb(45, 45, 45);
        font-size: 18px;
        font-family: Roboto;
    }
</style>

<script>
    export default{
        props: {
            imgsrc: String,
            imgalt: String,
            heading: String,
            text: String,
        }
    }
</script>

<template>
    <div id="pagesection">
        <img :src="imgsrc" :alt="imgalt" id="pagesectionimg">
        <h1 id="pagesectionheading">{{ heading }}</h1>
        <p id="pagesectiontext">{{ text }}</p>
    </div>
</template>