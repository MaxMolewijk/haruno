<script>
</script>

<div class="container">
    <div class="row align-items-center justify-content-between">
        <div class="col-auto">LOGO + + HARUNO</div>
        <div class="col-auto row menu-options">
            <p class="col">Works</p>
            <p class="col">About</p>
            <p class="col">Media</p>
            <p class="col">Contact</p>
        </div>
        <div class="col-auto hamburger">

        </div>
    </div>
</div>

<style>
    .container > .row {
        height: 100px;
    }
    
    p {
        margin: 0;
        padding: 20px;
    }

    .hamburger {
        height: 50px;
        width: 50px;
        background-color: red;
        display: none;
        animation-duration: 1s;
    }

    .hamburger:hover {
        background-color: lightpink;
    }

    @media only screen and (max-width: 600px) {
        .menu-options {
            display: none;
        }
        .hamburger {
            display: block;
        }
    }

</style>
