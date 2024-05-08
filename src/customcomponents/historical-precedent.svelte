<script>
    import Titlebox from "./titlebox.svelte";
    import TextBox from "./textbox.svelte";
    import TitleAndDescription from "./titleanddescription.svelte";
</script>

<style>
    .TitleAndDescription {
        padding-bottom: 5%;
    }
    .TextBox {
        padding-bottom: 5%;
    }
    .spacer {
        padding-top: 5%;
    }
</style>

<body lang="en">
    <Titlebox title="Historical Precedent" />
    <TextBox description="Locust swarms have posed a significant threat to agricultural and food insecurity throughout history.  Locust swarms might seem like a distant problem, something out of an old story or something that only affects far-off lands. But in reality, the impact of locust swarms is immediate, vast, and can have global repercussions. When a swarm starts, it can last months, and in rare cases, years! A single locust swarm, one out of a few hundred to even a few thousand can eat the same amount of food as 5,000 people in one day. And in areas that already struggle with food insecurity, Locust swarms are devastating, and quickly escalate into a full-blown humanitarian crisis. But the locusts themselves are half of the battle. The pesticides used to kill the locusts are extremely toxic and in many cases, are ineffective. Chemicals like Organophosphates, Pyrethroids, and Fenitrothion have caused severe damage to non-target animals like honey bees and in combination with other chemicals, humans. While the swarm is devastating, the pesticides used alter the environment and hurt the ecosystem." />
    <div class="spacer"></div>
    <TitleAndDescription title="1874 Rocky Mountain Locust Swarm:" description="In 1874, a swarm of Rocky Mountain locusts wreaked havoc across the entire North American Great Plains. A rainy spring provided perfect conditions for Locust eggs to hatch, and a subsequent drought forced the swarm to leave the mountains. The swarm was one of, if not the largest locust swarm ever recorded, at an estimated 2,000,00 square miles in size, about the size of 10 Texas’. The damage was estimated at about 200 million dollars at the time, which is billions of dollars in today’s economy. The swarm eventually died out as a late spring killed off all of the locust eggs." />
    <TitleAndDescription title="January 2016 Argentina Locust Swarm:" description="In 2016, over 100 locust swarms broke out in a small time period, causing a total of over 700,000 hectares to be affected. Interestingly, the government was warned of early signs of these swarms as early as July of 2015, although they did nothing to prevent it." />
    <TitleAndDescription title="2019-2021 Desert Locust Swarm:" description="A rare event of two different cyclones impacting northern Africa in 2018 created perfect breeding conditions for locusts to build up and explode into a large-scale locust infestation in the Horn of Africa and Middle East. Due to the failure to detect these locusts breeding in the middle of uninhabited deserts, a plague of billions of locusts was unleashed on almost two dozen countries, plunging many already struggling countries into further despair through food insecurity." />
</body>