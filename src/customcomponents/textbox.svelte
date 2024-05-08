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
        align-items: center;
    }
    .text {
        font-size: 20px;
        width: 70%;
        text-align: left;
    }
</style>

<body>
    <div class="textwrapper">
        <p class="text">{description}</p>
    </div>
</body>