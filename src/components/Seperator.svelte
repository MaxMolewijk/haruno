<script>
    export let text = "";
</script>


<div class="container">
    <div class="row align-items-center">
        <div class="col-auto line" />
        <div class="col-auto">
            <p>{text}</p>
        </div>
    </div>
</div>

<style>
    .container {
        margin-top: 100px;
        margin-bottom: 50px;
    }

    p {
        color: #2c2851;
        font-weight: bold;
        font-size: 20px;
        margin: 0;
    }

    .line {
        height: 3px;
        width: 30px;
        margin-right: 30px;
        background-color: #2c2851;
    }
</style>
