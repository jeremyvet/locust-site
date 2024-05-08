<script lang="ts">
    export var class1: string;
    export var header: string;
    export var description: string;
</script>

<style>
    body{
        margin: 0;
    }
    div{
        min-width: 400px;
        width: min-content;
        min-height: 300px;
        height: min-content;
        padding: 5% 5% 5% 5%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        background-color: #59515E;
        border-radius: 10px;
        align-items: center;
    }
    .header {
        font-size: 30px;
        font-family: Arial, Helvetica, sans-serif;
        font-weight: 600;
        margin-top: 5%;
        margin-bottom: 10%;
    }
    #description {
        font-size:20px;
        font-family: Arial, Helvetica, sans-serif;
    }
</style>

<body>
    <div class="aboutmewrapper">
        <span class="header">{header}</span>
        <span class={class1} id="description">{description}</span>
    </div>
</body>