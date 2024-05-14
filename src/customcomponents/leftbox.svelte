<script lang="ts">
    export var imagesrc: string;
    export var title: string;
    export var description: string;
</script>

<style>
    body {
        padding-bottom: 5%;
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
        width: 50%;
        align-items: center;
        justify-content: end;
    }
    .right {
        display: flex;
        flex-direction: column;
        gap: 10px;
        width: 50%;
        align-items: center;
        justify-content: center;
        /* padding-left: 15%; */
    }
    .image {
        min-height: fit-content;
        width: 40%;

    }
    .title {
        text-align: left;
        font-size: 30px;
        align-self: center;
    }
    .description {
        text-align: left;
        font-size: 18px;
        align-self: center;
        width: 45%;
    }
</style>

<body>
    <div class="wrapper">
        <div class="left">
            <img class="image" src={imagesrc} alt="image"/>
        </div>
        <div class="right">
            <span class="title">{title}</span>
            <span class="description">{description}</span>
        </div>
    </div>
</body>