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
</style>

<body>
    <Titlebox title="Our Solution"/>

    <Textbox description="Our solution is a custom-designed pesticide-spraying device that will attach to the underside tail of a small airplane and spray pesticides from a controlling remote located in the cockpit. Our solution will use a biopesticide, Metarhizium Acridum, as our spray of choice, mixing the powdery fungal spores into a liquid substance for easier spraying with nozzles."/>
    <Textbox description="Because our pesticide spraying device attaches to an airplane, we can easily spray multiple large areas quickly and efficiently; being far more efficient than manual spraying or ground-based technology at the expense of how thorough the coverage may be."/>

    <Divider></Divider>

    <Subtitlebox title="We have five steps to ensure that our pesticide spraying operation functions properly:"/>

    <Gap />

    <Number number="1" title="Find Land" description="We will communicate with farmers that are located within areas surrounding a known active locust swarm and work with them to get permission to spray their farms."/>
    <Number number="2" title="Prep Sprayers" description="We will prepare a small plane (our own company purchase or one that the farmer owns) with our custom-made fungal pesticide spraying device. We will attach all of the necessary equipment to allow the plane to spray, which includes the reservoir, hose and nozzle system, and a control interface from which the pilot can dispense the product."/>
    <Number number="3" title="Takeoff" description="After this, our pilot will enter the plane and take off with a full tank of pesticide and instructions on where to spray the product."/>
    <Number number="4" title="Spraying" description="There will be a ground correspondent to provide the pilot with a second pair of eyes, and together they will coordinate when the device is activated and spray pesticides over the correct areas."/>
    <Number number="5" title="Return" description="Once the spraying has been completed, the plane can touch down safely and all the equipment can be removed and transferred to the next property."/>
</body>