<!-- TODO refactor to make prettier -->
<div class="container">
    <div class="row align-items-center justify-content-between">
        <div class="col-auto ">
            <p><img src="assets/haruno_logo.png" class="logo" alt="HARUNO logo"/> HARUNO</p>
        </div>
        <div class="col-auto row menuOptions">
            <p class="col">Works</p>
            <p class="col">About</p>
            <p class="col">Media</p>
            <p class="col">Contact</p>
        </div>
        <div class="col-auto hamburger" />
    </div>
</div>

<style>
    .container > .row {
        height: 100px;
        margin-top: 50px;
    }

    p {
        margin: 0;
        padding: 30px;
        color: #2c2851;
        font-size: 20px;
        font-weight: 900;
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
        .menuOptions {
            display: none;
        }
        .hamburger {
            display: block;
        }
    }

    .logo {
        width: 50px;
        margin-right: 15px;
        margin-left: -30px;
    }
</style>
