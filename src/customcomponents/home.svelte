<script lang="ts">
    import Aboutme from "./aboutme.svelte";
    import Textbox from "./textbox.svelte";
    import Titlebox from "./titlebox.svelte";
    import Leftbox from "./leftbox.svelte";
    import Rightbox from "./rightbox.svelte";
    import Gap from "./gap.svelte";
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
    <Textbox description="Locust swarms are one of nature's most devastating phenomena, capable of causing widespread destruction to crops and threatening food security across entire regions. These swarms, often spanning vast areas, can consume as much food in a day as thousands of people, turning thriving fields into barren wastelands almost overnight. As our world becomes increasingly interconnected, the impact of locust swarms is no longer a distant concern but a global issue with far-reaching consequences.
    "/>
    <Gap />

    <Leftbox imagesrc="/locust.png" title="Lessons from the Past" description="Throughout history, locust swarms have left a trail of destruction, profoundly impacting societies and economies. Notable examples include the massive Rocky Mountain locust swarm of 1874, which devastated the Great Plains, and more recent outbreaks such as the 2016 Argentina locust swarms and the 2019-2021 Desert Locust plague that ravaged parts of Africa and the Middle East. These historical events underscore the persistent threat posed by locusts and the critical importance of developing effective strategies to mitigate their impact. For more detailed accounts, visit our Historical Precedent page." />
    <Rightbox imagesrc="/locust2.png" title="The Toxic Toll of Pesticides" description="To combat the relentless advance of locust swarms, chemical pesticides have been employed extensively. While these substances can effectively reduce locust populations, their use comes at a steep price. Pesticides like Organophosphates, Pyrethroids, and Fenitrothion have been widely used despite their severe environmental and health impacts. These chemicals contaminate soil and water, harm beneficial insects such as bees, and pose significant risks to human health. The reliance on these toxic solutions highlights the urgent need for safer, more sustainable pest control methods." />
<!-- 
    <Gap />

    <Titlebox title="About Us"></Titlebox>
    <Gap />
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
    </div> -->
</body>