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
        <img src="assets/psychology.png" alt="From thhe basic" class="topic"/>
        <div class="read row align-items-center">
            <p class="col-auto">Read</p>
            <i class="col-auto fa-solid fa-arrow-right arrow" />
        </div>
    </div>
    <div class="card">
        <img src="assets/nerd.png" alt="Make simple and elegant " class="topic"/>
        <div class="read row align-items-center">
            <p class="col-auto">Read</p>
            <i class="col-auto fa-solid fa-arrow-right arrow" />
        </div>
    </div>
    <div class="card">
        <img src="assets/inspirational.png" alt="create art" class="topic"/>
        <div class="read row align-items-center">
            <p class="col-auto">Read</p>
            <i class="col-auto fa-solid fa-arrow-right arrow" />
        </div>
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
