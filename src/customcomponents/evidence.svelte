<script>
    import Textbox from "./textbox.svelte";
    import Titlebox from "./titlebox.svelte";
    import Triplebox from "./triplebox.svelte";
    import Gap from "./gap.svelte";

    // import { onMount } from "svelte";
    
    // onMount(() => {
    //     var test1 = document.getElementsByClassName("org").innerHTML
    //     console.log(test1)
    // });
</script>

<style>
    .wrapper {
        width: 100%;
        height: 100%;
        padding-bottom: 5%;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center !important;
        gap: 10px;
    }
</style>

<body lang="en">
    <Titlebox title="Current Solutions"/>
    <Textbox description="Addressing locust infestations involves environmental and biodiversity considerations. Chemical pesticides, though effective against locusts, can harm other wildlife, degrade soil, and pollute water sources, affecting birds, humans, and other animals. During the 2019-2021 Desert Locust outbreak, treatments over 1.6 million hectares had significant impacts on both locusts and non-target species. Here's a rundown of the main pesticides used in Locust Swarms:"/>
    <Gap />
    <div class="wrapper">
        <Triplebox class1="org" header="Organophosphates" description="Organophosphates are groundwater pollutants and can act as a nerve agent for certain animals. This pesticide is also a possible carcinogen for humans."/>
        <Triplebox class1="pyr" header="Pyrethroids" description="Pyrethroids are an organic compound that are extremely toxic to bees, other invertebrates, and marine life."/>
        <Triplebox class1="fen" header="Fenitrothion" description="Fenitrothion is a cheap and widely used pesticide that in combination with other metals, can cause brain damage to humans."/>
    </div>
</body>

