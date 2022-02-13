<div class="container" id="contact">
    <div class="row justify-content-center">
        <h1>Let's connect</h1>
        <p>Got a project feel free to get touch</p>
        <p>
            <a href="mailto:someone@yoursite.com"
                >sukura@haruno.com
                <i class="col-auto fa-solid fa-arrow-right arrow" />
            </a>
        </p>
    </div>
    <div class="row justify-content-center">
        <div id="name" class="col-12 col-md-5 col-xl-5">
            <input class="input" placeholder="Your sweet name">
        </div>
        <div id="email" class="col-12 col-md-6 col-xl-5">
            <input class="input" placeholder="Your mail adress">
        </div>
    </div>
    <div class="row justify-content-center">
        <div id="message" class="col-12 col-md-8">
            <textarea class="input" placeholder="About your message "></textarea>
        </div>
        <div id="send" class="col-12 col-md-2 row align-items-center justify-content-center">
            <p>SEND <br><i class="col-auto fa-solid fa-arrow-right"/></p>
        </div>
    </div>
</div>

<style>
    .container {
        margin-bottom: 200px;
    }
    h1 {
        text-align: center;
        margin-bottom: 30px;
    }

    p {
        font-size: 26px;
        color: #797696;
        font-weight: bold;
        margin-bottom: 40px;
        text-align: center;
    }

    a {
        font-size: 3.5vmax;
    }
    a:hover {
        color: #6518ff;
    }
    .arrow {
        margin-left: 15px;
        font-size: 40px;
        transition: 0.5s;

        -webkit-transform: rotate(-45deg);
        -moz-transform: rotate(-45deg);
        -ms-transform: rotate(-45deg);
        -o-transform: rotate(-45deg);
        transform: rotate(-45deg);
    }
    a:hover > .arrow {
        padding-left: 20px;
        font-size: 50px;

        -webkit-transform: rotate(0deg);
        -moz-transform: rotate(0deg);
        -ms-transform: rotate(0deg);
        -o-transform: rotate(0deg);
        transform: rotate(0deg);
    }

    .input {
        width: 100%;
        height: 100%;
        padding: 40px;
        font-size: 20px;
        border: none;
        resize: none;
    }

    #name, #email, #message, #send {
        padding: 0;
    }

    #name {
         margin-bottom: 20px;
        margin-right: 20px;
    }

    #email {
        margin-bottom: 20px;
    }

    #message {
        height: 250px;
        margin-right: 20px;
    }

    #send {
        background-color: #62BA55;
        height: 25  0px;
        padding: 20px;
    }

    #send > p {
        color: white;
        margin: 0;
    }
    #send > p > i {
        color: white;
        font-size: 30px;
        margin-top: 20px;
        transition: 0.5s;
    }
    #send:hover > p > i {
        margin-left: 20px;
    }
    #send:hover {
        cursor: pointer;
    }
</style>
