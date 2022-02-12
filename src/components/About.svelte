<div class="container">
    <div class="row justify-content-between align-items-center">
        <div class="col">
            <div class="row" id="name">Sakura Haruno</div>
            <div class="row">
                <p
                    id="role"
                    style="background-image: url(assets/text_bg.jpg);"
                >
                    Designer &<br /> Illustrator
                </p>
            </div>
            <div class="row" id="description">
                Norway based designer who specialised <br> in product design and
                illustration
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
        padding-left: 50px;
        padding-right: 50px;
    }

    .coverImage {
        height: 600px;
        position: relative;
    }

    #name {
        font-size: 40px;
        color: #2c2851;
        font-family: 'Satisfy', cursive;
        font-weight: 900;
    }

    #role {
        font-size: 80px;
        line-height: 110%;
        background-repeat: repeat;
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
        -webkit-font-smoothing: antialiased;
        margin-left: -15px;
        font-family: 'Poppins', sans-serif;
    }

    #description {
        font-size: 20px;
        color: #797696;
        margin-top: 40px;
        font-weight: bold ;
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
</style>
