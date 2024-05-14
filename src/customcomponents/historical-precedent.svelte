<script>
    import Titlebox from "./titlebox.svelte";
    import Textbox from "./textbox.svelte";
    import TitleAndDescription from "./titleanddescription.svelte";
    import Triplebox from "./triplebox.svelte";
    import Gap from "./gap.svelte";
    import Number from "./number.svelte";
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
    .wrapper {
        width: 100%;
        height: 100%;
        padding-bottom: 1%;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: center !important;
        gap: 10px;
    }
</style>

<body lang="en">
    <Titlebox title="Historical Precedent" />
    <Textbox description="Locust swarms have posed a significant threat to agricultural and food insecurity throughout history.  Locust swarms might seem like a distant problem, something out of an old story or something that only affects far-off lands. But in reality, the impact of locust swarms is immediate, vast, and can have global repercussions. When a swarm starts, it can last months, and in rare cases, years! A single locust swarm, one out of a few hundred to even a few thousand can eat the same amount of food as 5,000 people in one day. And in areas that already struggle with food insecurity, Locust swarms are devastating, and quickly escalate into a full-blown humanitarian crisis. But the locusts themselves are half of the battle. The pesticides used to kill the locusts are extremely toxic and in many cases, are ineffective. Chemicals like Organophosphates, Pyrethroids, and Fenitrothion have caused severe damage to non-target animals like honey bees and in combination with other chemicals, humans. While the swarm is devastating, the pesticides used alter the environment and hurt the ecosystem." />
    <div class="spacer"></div>
    <Number number="1" title="1874 Rocky Mountain Locust Swarm:" description="In 1874, a swarm of Rocky Mountain locusts wreaked havoc across the entire North American Great Plains. A rainy spring provided perfect conditions for locust eggs to hatch, and a subsequent drought forced the swarm to leave the mountains. The swarm was one of, if not the largest locust swarm ever recorded, at an estimated 2,000,000 square miles in size, about the size of 10 Texas’. The damage was estimated at about 200 million dollars at the time, which is billions of dollars in today’s economy. The swarm eventually died out as a late spring killed off all of the locust eggs. At the time, modern pesticides were not available, so farmers relied on primitive and largely ineffective methods such as crushing the locusts or using smoke to drive them away. This lack of effective pest control measures resulted in immense crop losses and economic hardship."/>
    <Number number="2" title="January 2016 Argentina Locust Swarm:" description="In 2016, over 100 locust swarms broke out in a short period, causing a total of over 700,000 hectares to be affected. Interestingly, the government was warned of early signs of these swarms as early as July of 2015, although they did nothing to prevent it. In response to the outbreak, chemical pesticides, particularly Organophosphates and Pyrethroids, were used extensively. These chemicals helped to reduce the locust populations but also led to significant environmental damage. Non-target species, including beneficial insects and pollinators, suffered substantial losses, and local water sources were contaminated with pesticide residues, posing health risks to local communities and wildlife."/>
    <Number number="3" title="2019-2021 Desert Locust Swarm:" description="A rare event of two different cyclones impacting northern Africa in 2018 created perfect breeding conditions for locusts to build up and explode into a large-scale locust infestation in the Horn of Africa and Middle East. Due to the failure to detect these locusts breeding in the middle of uninhabited deserts, a plague of billions of locusts was unleashed on almost two dozen countries, plunging many already struggling countries into further despair through food insecurity. The response to this outbreak saw the massive application of chemical pesticides across affected regions. Organophosphates and Fenitrothion were among the primary chemicals used. While these pesticides managed to curb the spread of locusts to some extent, they also caused severe ecological harm. Soil and water contamination, along with the decimation of non-target insect populations, exacerbated the environmental crisis. The widespread use of these toxic chemicals highlighted the urgent need for safer and more sustainable pest control methods."/>
    
    <!-- <TitleAndDescription title="1874 Rocky Mountain Locust Swarm:" description="In 1874, a swarm of Rocky Mountain locusts wreaked havoc across the entire North American Great Plains. A rainy spring provided perfect conditions for Locust eggs to hatch, and a subsequent drought forced the swarm to leave the mountains. The swarm was one of, if not the largest locust swarm ever recorded, at an estimated 2,000,00 square miles in size, about the size of 10 Texas’. The damage was estimated at about 200 million dollars at the time, which is billions of dollars in today’s economy. The swarm eventually died out as a late spring killed off all of the locust eggs." />
    <TitleAndDescription title="January 2016 Argentina Locust Swarm:" description="In 2016, over 100 locust swarms broke out in a small time period, causing a total of over 700,000 hectares to be affected. Interestingly, the government was warned of early signs of these swarms as early as July of 2015, although they did nothing to prevent it." />
    <TitleAndDescription title="2019-2021 Desert Locust Swarm:" description="A rare event of two different cyclones impacting northern Africa in 2018 created perfect breeding conditions for locusts to build up and explode into a large-scale locust infestation in the Horn of Africa and Middle East. Due to the failure to detect these locusts breeding in the middle of uninhabited deserts, a plague of billions of locusts was unleashed on almost two dozen countries, plunging many already struggling countries into further despair through food insecurity." />
     -->
    
    <Titlebox title="Current Solutions"/>
    <Textbox description="Addressing locust infestations involves environmental and biodiversity considerations. Chemical pesticides, though effective against locusts, can harm other wildlife, degrade soil, and pollute water sources, affecting birds, humans, and other animals. During the 2019-2021 Desert Locust outbreak, treatments over 1.6 million hectares had significant impacts on both locusts and non-target species. Here's a rundown of the main pesticides used in Locust Swarms:"/>
    <Gap />
    <div class="wrapper">
        <Triplebox class1="org" header="Organophosphates" description="Organophosphates are groundwater pollutants and can act as a nerve agent for certain animals. This pesticide is also a possible carcinogen for humans."/>
        <Triplebox class1="pyr" header="Pyrethroids" description="Pyrethroids are an organic compound that are extremely toxic to bees, other invertebrates, and marine life."/>
        <Triplebox class1="fen" header="Fenitrothion" description="Fenitrothion is a cheap and widely used pesticide that in combination with other metals, can cause brain damage to humans."/>
    </div>
    <Textbox description="The extensive use of pesticides like Organophosphates, Pyrethroids, and Fenitrothion has inflicted severe damage on both the environment and human health. Organophosphates, potent nerve agents, have polluted groundwater, leading to acute toxicity in wildlife and chronic health issues in humans, including potential carcinogenic effects and neurological disorders. Pyrethroids have decimated bee populations, which are crucial for pollination, causing a cascade of negative effects on agricultural yields and biodiversity. This pesticide also poses significant threats to aquatic life, leading to the decline of fish populations and the disruption of aquatic ecosystems. Fenitrothion, widely used due to its cost-effectiveness, has caused alarming levels of neurotoxicity, particularly when it interacts with other environmental contaminants, resulting in brain damage and other severe health impacts in humans. These pesticides have not only failed to provide a sustainable solution to locust swarms but have also exacerbated environmental degradation and public health crises, undermining the resilience of ecosystems and communities."/>
    <Textbox description="These three pesticides each have nasty side effects, but not all pesticides have to be harmful. For our solution, we want to implement a bio-pesticide known as Metarhizium Acridum. This pesticide has the locust-killing effects seen in other pesticides but without the catch of the harmful effects of the aforementioned pesticides. "/>
    <Textbox description="One of the only downsides to Metarhizium Acridum is its price. A single gallon of Metarhizium Acridum can cost as much as $300, which starts to add up when we need to spray it across thousands of acres. This significant expense is a major barrier to its widespread use, especially in regions that are already economically strained and facing severe food insecurity. Consequently, its use has been largely confined to lab tests and small-scale locust swarms, where the cost is more manageable. The high price of Metarhizium Acridum is also why other, more dangerous pesticides continue to be favored. These chemical pesticides, despite their detrimental environmental and health impacts, are considerably cheaper and thus more accessible for large-scale agricultural applications. Governments and organizations often opt for these more affordable options in their urgent attempts to control locust outbreaks, inadvertently causing long-term ecological harm and health risks. Additionally, the lack of infrastructure and funding for the development and distribution of biopesticides like Metarhizium Acridum further limits their implementation. This situation underscores the need for increased investment in sustainable pest control solutions and the development of cost-effective methods for producing and deploying biopesticides on a larger scale."/>
    <Textbox description=""/>
</body>