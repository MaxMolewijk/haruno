<div class="container">
    <div class="row align-items-center justify-content-between heading">
        <div class="col-auto">
            <h1>Design newsletter</h1>
        </div>
        <div class="col-auto explore">
            Explore all blogs <i
                class="col-auto fa-solid fa-arrow-right arrow"
            />
        </div>
    </div>
</div>

<div class="scrolling-wrapper">
    <div class="card">
        <div class="imageContainer">
            <img
                src="assets/psychology.png"
                alt="From thhe basic"
                class="topic"
            />
            <div class="read row align-items-center">
                <p class="col-auto">Read</p>
                <i class="col-auto fa-solid fa-arrow-right arrow" />
            </div>
        </div>
        <h2>User psychology</h2>
        <p class="description">
            The ultimate guide to proper understanding <br />
            user perspective and it's impact on <br /> day to day life
        </p>
    </div>
    <div class="card">
        <div class="imageContainer">
            <img
                src="assets/nerd.png"
                alt="Make simple and elegant "
                class="topic"
            />
            <div class="read row align-items-center">
                <p class="col-auto">Read</p>
                <i class="col-auto fa-solid fa-arrow-right arrow" />
            </div>
        </div>
        <h2>Illustration nuance</h2>
        <p class="description">
            A brief explanation on how to apply colors <br />
            and how to create simple, elegeant <br />
            illustration
        </p>
    </div>
    <div class="card">
        <div class="imageContainer">
            <img
                src="assets/inspirational.png"
                alt="create art"
                class="topic"
            />
            <div class="read row align-items-center">
                <p class="col-auto">Read</p>
                <i class="col-auto fa-solid fa-arrow-right arrow" /> 
            </div>
        </div>
        <h2>User research</h2>
        <p class="description">
            Step down the stairs of humility to completely<br>
            come up with a description of your own <br>
            becase the image was cut off
        </p>
    </div>
</div>

<style>
    .heading {
        margin-bottom: 100px;
    }
    .explore {
        font-size: 20px;
        color: #2c2851;
        font-weight: bold;
    }

    .explore:hover {
        cursor: pointer;
    }

    .explore:hover > .arrow {
        margin-left: 40px;
        margin-right: -10px;
    }

    .arrow {
        font-size: 20px;
        margin-left: 30px;
        transition: 0.5s;
    }

    .scrolling-wrapper {
        overflow-x: scroll;
        overflow-y: hidden;
        white-space: nowrap;
        padding-left: calc((100% - 1300px) / 2);
        scrollbar-width: none;
        margin-bottom: 150px;
    }

    /* Code to hide the scrollbar, while still being able to scroll */
    ::-webkit-scrollbar {
        width: 0;
        background: transparent;
    }

    .card {
        display: inline-block;
        margin-right: 80px;
        position: relative;
        border: none;
        background-color: transparent;
        width: 700px;
    }

    .topic {
        width: 700px;
    }

    .read {
        position: absolute;
        bottom: 0;
        right: 0;
        background-color: white;
        padding: 50px;
    }

    .read > p {
        color: #2c2851;
        font-size: 25px;
        font-weight: bold;
    }

    .read:hover {
        cursor: pointer;
    }

    .read:hover > .arrow {
        margin-left: 40px;
        margin-right: -10px;
    }

    .read > .arrow {
        margin-left: 60px;
    }

    .read {
        font-size: 20px;
        margin-left: 30px;
        transition: 0.5s;
    }

    .imageContainer {
        position: relative;
    }

    h2 {
        color: #2c2851;
        font-family: "Poppins", sans-serif;
        font-size: 40px;
        margin-top: 60px;
        margin-bottom: 30px;
    }

    .description {
        font-size: 24px;
        color: #797696;
        font-weight: bold;
        margin-bottom: 90px;
    }

    /* Media queries to enable align the scrolling cards with the H1 title */
    @media only screen and (max-width: 1400px) {
        .scrolling-wrapper {
            padding-left: calc((100% - 1120px) / 2);
        }
    }
    @media only screen and (max-width: 1200px) {
        .scrolling-wrapper {
            padding-left: calc((100% - 940px) / 2);
        }
    }

    @media only screen and (max-width: 992px) {
        .scrolling-wrapper {
            padding-left: calc((100% - 700px) / 2);
        }
    }

    @media only screen and (max-width: 769px) {
        .scrolling-wrapper {
            padding-left: calc((100% - 520px) / 2);
        }
    }
</style>
