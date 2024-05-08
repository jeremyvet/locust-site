<script lang="ts">
    export var title: string;
</script>

<style>
    .titlesection {
        min-height: min-content;
        height: 20%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .title {
        font-size: 35px;
    }
</style>

<body>
    <div class="titlesection">
        <h1 class="title">{title}</h1>
    </div>
</body>