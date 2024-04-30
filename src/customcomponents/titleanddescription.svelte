<script lang="ts">
    export var title: string;
    export var description: string;
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
    .titlesection {
        min-height: min-content;
        height: 20%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .title {
        font-size: 30px;
    }
    .row {
        display: flex;
    }
    
    .column {
        float: left;
        flex: 50%;
    }
</style>

<body>
    <div class="row">
       <div class="column">

       </div> 
       <div class="column">
        <div class="titlesection">
            <h1 class="title">{title}</h1>
        </div>
        <div class="textwrapper">
            <p class="text">{description}</p>
        </div>
       </div> 
    </div>
    
</body>