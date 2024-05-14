<script lang="ts">
    import Aboutme from "./aboutme.svelte";
    import Textbox from "./textbox.svelte";
    import Titlebox from "./titlebox.svelte";
    import Leftbox from "./leftbox.svelte";
</script>

<style>
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
</style>

<body lang="en">
    <Titlebox title="The Locust Problem"></Titlebox>
    <Textbox description="Locust swarms aren't just a distant problem, something out of the bible or something that only affects far-off lands. 
    In reality, the impact of locust swarms are immediate, vast, and can have global repercussions.
    Locust swarms, one of a few hundred to a few thousand, contain millions, sometimes billions of locusts. The number of locusts in these swarms means one swarm can eat the same amount of food as 35,000 people in one day.
    " />

    <Leftbox imagesrc="/locust.png" title="test" description="test" />

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
</body>