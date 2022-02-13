<div class="container" id="about">
    <div class="row justify-content-between align-items-center">
        <div class="col" >
            <div class="row" id="name"><p>Sakura Haruno</p></div>
            <div class="row">
                <p id="role" style="background-image: url(assets/text_bg.jpg);">
                    Designer &<br /> Illustrator
                </p>
            </div>
            <div class="row" id="description">
                <p>Norway based designer who specialised <br /> in product design and
                illustration</p>
            </div>
        </div>
        <div class="col imageContainer">
            <img
                src="assets/sakura_haruno.jpg"
                class="coverImage"
                alt="Sakura Haruno"
            />
            <div class="about row align-items-center">
                <p class="col-auto">About Myself</p>
                <i class="col-auto fa-solid fa-arrow-right arrow" />
            </div>
        </div>
    </div>
</div>

<style>
    p {
        margin: 0;
    }
    .container {
        margin-top: 50px;
    }

    #name {
        font-size: 50px;
        color: #2c2851;
        font-family: "Satisfy", cursive;
        font-weight: 900;
        margin-bottom: 20px;
    }

    #role {
        font-size: 5.5vmax;
        line-height: 110%;
        background-repeat: repeat;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        -webkit-font-smoothing: antialiased;
        margin-left: -15px;
        font-family: "Poppins", sans-serif;
    }

    #description {
        font-size: 25px;
        color: #797696;
        margin-top: 40px;
        font-weight: bold;
    }

    .imageContainer {
        position: relative;
        margin-left: -20px;
    }

    .about {
        position: absolute;
        bottom: 0;
        right: 0;
        background-color: white;
        padding: 25px;
    }

    .about > p {
        color: #2c2851;
        font-size: 18px;
        font-weight: bold;
    }

    .about:hover {
        cursor: pointer;
    }

    .about:hover > .arrow {
        margin-left: 40px;
        margin-right: -10px;
    }

    .arrow {
        font-size: 20px;
        margin-left: 30px;
        transition: 0.5s;
    }

    .coverImage {
        width: 640px;
    }

    @media only screen and (max-width: 1400px) {
        .coverImage {
            width: 600px;
        }
    }
    @media only screen and (max-width: 1200px) {
        .coverImage {
            width: 500px;
        }
    }
    @media only screen and (max-width: 1000px) {
        .coverImage {
            width: 450px;
        }

        #name, #role, #description {
            text-align: center;
        }
    }

    @media only screen and (max-width: 440px) {
        .coverImage {
            width: 100vw;
        }
    }
</style>
