<script lang="ts">
export var imagesource: string;
export var header: string;
export var description: string;
</script>

<style>
    html{
        margin: 0;
    }
    div{
        min-width: 200px;
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
        margin-top: 25%;
        margin-bottom: 10%;
    }
    .description {
        font-size:20px;
        font-family: Arial, Helvetica, sans-serif;
    }
</style>

<body>
    <div class="aboutmewrapper">
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img src={imagesource} alt="About me Image"/>
        <span class="header">{header}</span>
        <span class="description">{description}</span>
    </div>
</body>