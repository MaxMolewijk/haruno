<script>
    let menuCollapsed = true;

    function openCloseMenu() {
        menuCollapsed = !menuCollapsed;
    }
</script>

<div class="container">
    <div class="row align-items-center justify-content-between">
        <div class="col-auto ">
            <p>
                <img
                    src="assets/haruno_logo.png"
                    class="logo"
                    alt="HARUNO logo"
                /> HARUNO
            </p>
        </div>
        <div class="col-auto row menuOptions">
            <p class="col"><a href="#works">Works</a></p>
            <p class="col"><a href="#about">About</a></p>
            <p class="col"><a href="#media">Media</a></p>
            <p class="col"><a href="#contact">Contact</a></p>
        </div>
        <i class="fas fa-bars icon hamburger" on:click={openCloseMenu}/>
    </div>
    <div class="row align-items-center justify-content-between menu" class:menuCollapsed={menuCollapsed}>
        <p class="row"><a href="#works">Works</a></p>
        <p class="row"><a href="#about">About</a></p>
        <p class="row"><a href="#media">Media</a></p>
        <p class="row"><a href="#contact">Contact</a></p>
    </div>
</div>

<style>
    .container > .row {
        margin-top: 50px;
        overflow: hidden;
    }

    p {
        margin: 0;
        padding: 30px;
        color: #2c2851;
        font-size: 20px;
        font-weight: 900;
    }

    a {
        color: #2c2851;
    }
    a:hover {
        text-decoration: underline;
    }

    .logo {
        width: 50px;
        margin-right: 15px;
        margin-left: -30px;
    }

    .icon {
        width: 40px;
    }

    .hamburger {
        font-size: 40px;
        display: none;
        animation-duration: 1s;
    }

    .hamburger:hover {
        cursor: pointer;
    }

    @media only screen and (max-width: 770px) {
        .menuOptions {
            display: none;
        }
        .hamburger {
            display: inline;
        }
    }

    @media only screen and (min-width: 770px) {
        .menu {
            display: none;
        }
    }

    .menu {
        background-color: rgb(250, 216, 223);
        transition: 0.4s;
        height: 400px;
    }

    .menuCollapsed {
        height: 0;
    }
</style>
