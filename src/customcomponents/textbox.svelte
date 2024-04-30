<script lang="ts">
export var description: String;
</script>

<style>
    .textwrapper {
        display: flex;
        flex-direction: column;
        width: 100%;
        height: min-content;
        padding-top: 2%;
        padding-bottom: 5%;
        align-items: center;
    }
    .text {
        font-size: 18px;
        width: 90%;
        text-align: center;
    }
</style>

<body>
    <div class="textwrapper">
        <p class="text">{description}</p>
    </div>
</body>