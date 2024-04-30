<script lang="ts">
    import Aboutme from "./aboutme.svelte";
    import Titlebox from "./titlebox.svelte";
</script>

<style>
    html{
        margin: 0;
        width: 100%;
        height: 100%;
    }
    .aboutmesection{
        width: 100%;
        height: 100%;
        /* padding-top: 5%; */
        padding-bottom: 5%;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center !important;
        gap: 10px;
    }
    /* .titlesection {
        min-height: min-content;
        height: 20%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .title {
        font-size: 45px;
    } */
</style>

<html lang="en">
    <Titlebox title="About Us"></Titlebox>
    <div class="aboutmesection">
        <Aboutme
        imagesource="https://d1l3jc4magixw.cloudfront.net/cases/2008/NA_2008_2451/2008_NA_2008_2451_hero_1.jpg"
        header="Jeremy"
        description="awesome"
        />
        <Aboutme
        imagesource="https://d1l3jc4magixw.cloudfront.net/cases/2008/NA_2008_2451/2008_NA_2008_2451_hero_1.jpg"
        header="Nicholas"
        description="awesome"
        />
        <Aboutme
        imagesource="https://d1l3jc4magixw.cloudfront.net/cases/2008/NA_2008_2451/2008_NA_2008_2451_hero_1.jpg"
        header="Ronin"
        description="awesome"
        />
    </div>
</html>