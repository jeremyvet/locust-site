<script lang="ts">
    export var imagesrc: string;
    export var title: string;
    export var description: string;
</script>

<style>
    body {
        padding-top: 2%;
        padding-bottom: 2%;
    }
    .wrapper {
        display: flex;
        flex-direction: row;
        /* border-color: #0492C2;
        border-width: 3px;
        border-radius: 5px; */
    }
    .left {
        display: flex;
        flex-direction: column;
        width: 50%;
        align-items: center;
        justify-content: center;
    }
    .right {
        display: flex;
        flex-direction: column;
        gap: 10px;
        width: 50%;
        align-items: center;
        justify-content: end;
        /* padding-left: 15%; */
    }
    .image {
        min-height: fit-content;
        width: 90%;
        align-self: center;
        border-radius: 10px;
    }
    .title {
        text-align: left;
        font-size: 45px;
        align-self: left;
        padding-bottom: 2%;
    }
    .description {
        text-align: left;
        font-size: 18px;
        align-self: center;
        width: 60%;
    }
</style>

<body>
    <div class="wrapper">
        <div class="left">
            <span class="title">{title}</span>
            <span class="description">{description}</span>
        </div>
        <div class="right">
            <!-- svelte-ignore a11y-img-redundant-alt -->
            <img class="image" src={imagesrc} alt="image"/>
        </div>
    </div>
</body>