<script>
    import Titlebox from "./titlebox.svelte";
    import Textbox from "./textbox.svelte";
    import Number from "./number.svelte";
    import Divider from "./divider.svelte";
    import Subtitlebox from "./subtitlebox.svelte";
    import Gap from "./gap.svelte";
</script>

<style>
    body {
        padding-bottom: 5%;
    }

    .stuff {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    img{
        width: 80%;
    }
</style>

<body>
    <Titlebox title="Our Solution"/>

    <Gap />

    <div class="stuff">
        <img src="./render1.png" alt="Solution on Plane"/>
    </div>

    <Textbox description="The solution we came up with is a custom-designed pesticide-spraying device that will attach to the underside of a small airplane and spray pesticides using a cockpit-controlled remote. This device will use Metarhizium Acridum as its pesticide of choice, mixing the powdery fungal spores into a liquid substance for easier spraying.
    We’ve made our design very simple in the hopes it can be easily integrated into existing aircraft- allowing us to cut costs by using our company aircraft minimally. The design consists of a container, a series of tubes, nozzles, and pumps to spray pesticides. The pesticide container is securely implemented into the plane's fuselage. The tank has a cap for filling the container with pesticide and a hole in the back from which it connects to the system of tubes. An automated pump will take this pesticide and distribute it through the tubes equally, where they can be widely sprayed onto the crops, which are then protected from the threat that a locust swarm can cause. This design can be installed on a plane in just a few hours, which is crucial for how fast these swarms can progress from farm to farm as they grow exponentially. 
    "/>
   
    <Gap />

    <div class="stuff">
        <img src="./render2.png" alt="Closeup of Solution"/>
    </div>
   
    <Textbox description="By dispersing the fungus using airplanes, we can easily cover multiple large farms and fields in a single trip. However, this method sacrifices the maximum coverage of these farms in exchange for being able to cover more distance. Other application methods, such as tractors or manual human spraying, could spray pesticides with more thorough coverage. Still, these methods cannot cover enough land fast enough to keep up with fast-moving locust swarms that can be in and out of acres of land in a mere day."/>

    <Gap />

    <div class="stuff">
        <img src="./render4.png" alt="Closeup of Solution 2"/>
    </div>

    <Gap />

    <Divider></Divider>

    <Subtitlebox title="We have five steps to ensure that our pesticide spraying operation functions properly:"/>

    <Gap />

    <Number number="1" title="Find Land" description="We will communicate with farmers that are located within areas surrounding a known active locust swarm and work with them to get permission to spray their farms."/>
    <Number number="2" title="Prep Sprayers" description="We will prepare a small plane (our own company purchase or one that the farmer owns) with our custom-made fungal pesticide spraying device. We will attach all of the necessary equipment to allow the plane to spray, which includes the reservoir, hose and nozzle system, and a control interface from which the pilot can dispense the product."/>
    <Number number="3" title="Takeoff" description="After this, our pilot will enter the plane and take off with a full tank of pesticide and instructions on where to spray the product."/>
    <Number number="4" title="Spraying" description="A ground correspondent will provide the pilot with a second pair of eyes. Together, they will coordinate when the device is activated and spray pesticides over the correct areas using a line of communication like a walkie-talkie."/>
    <Number number="5" title="Return" description="Once the spraying has been completed, the plane can touch down safely, and all the equipment can be removed and transferred to the next property."/>

    <Gap />

    <Textbox description=" We will repeat this process with any landowners we can get in contact with surrounding a locust swarm to ensure that these pests are properly managed before they spiral out of control and billions of dollars in damages occur. "/>

</body>