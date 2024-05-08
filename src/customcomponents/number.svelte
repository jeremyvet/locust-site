<script lang="ts">
    export var number: string;
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
        width: 20%;
        align-items: center;
        justify-content: end;
    }
    .right {
        display: flex;
        flex-direction: column;
        gap: 10px;
        width: 80%;
        align-items: center;
        justify-content: center;
        /* padding-left: 15%; */
    }
    .number {
        text-align: center;
        font-size: 45px;
        font-weight: 600;
        padding-bottom: 0%
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
        width: 75%;
    }
</style>

<body>
    <div class="wrapper">
        <div class="left">
            <span class="number">{number}</span>
        </div>
        <div class="right">
            <span class="title">{title}</span>
            <span class="description">{description}</span>
        </div>
    </div>
</body>