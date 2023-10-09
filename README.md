<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE-edge">
    <meta name="viewport" content="width=device-width,initial-sale=1.0">
    <title>
        Shruti - Developer Portfolio
    </title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(3, 8, 36);
            color: white;
            font-family: 'popping', sans-serif;
        }

        nav {
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(67, 66, 170)
        }

        nav ul {
            display: flex;
            justify-content: center;
        }

        nav ul li {
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a {
            text-decoration: none;
            color: aliceblue;
        }

        nav ul li a:hover {
            color: rgb(153, 153, 226);
            font-size: 1.2rem;
        }

        main hr {
            border: 0;
            background: #9c97f1;
            height: 1.2px;
            margin: 40px 84px;
        }

        .left {
            font-size: 2rem;
        }

        .firstSection {
            display: flex;
            justify-content: space-around;
            margin: 80px 0;
            align-items: center;
        }

        .firstSection>div {
            width: 30%;

        }

        .leftSection {
            font-size: 3rem;
        }

        .leftSection .a {
            margin: 0;
            padding: 0;
        }


        .leftSection .btn {
            padding: 12px;
            background: #1e2167;
            color: white;
            border: 3px soild white;
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;

        }



        .rightSection img {
            width: 80%;
        }

        .purple {
            color: rgb(117, 43, 185);
        }

        .text-gray {
            color: gray;
        }

        #element {
            color: rgb(117, 43, 185);

        }

        .secondsection {
            max-width: 80vmax;
            margin: auto;
            height: 80vh;

        }

        .secondsection h1 {
            font-size: 1.9rem;
        }

        .secondsection .Box {
            background: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondsection .vertical {
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 100px;
        }

        .image-top {
            width: 26px;
            position: relative;
            top: -30px;
            left: -9px;
        }

        .vertical-title {
            position: relative;
            top: 75px;
            width: 150px;
        }

        .vertical-desc {
            position: relative;
            top: 86px;
            color: gray;
            width: 150px;
            font-size: 10px;
        }

        footer {
            background-color: #0e0e1a;

        }

        .footer {
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;

        }

        .footer ul {
            list-style: none;
        }

        .footer>div {
            width: 222px;
        }

        footer .footer-rights {
            text-align: center;
            color: gray;
            padding: 12px 0;
        }
    </style>
</head>

<body>
    <header>
        <nav>
            <div class="left">Shruti's Portfolio</div>
            <div class="right">
                <ul>
                    <li><a href="/">Home</a></li>
                    <li><a href="/">About</a></li>
                    <li><a href="/">Service</a></li>
                    <li><a href="/">Projects</a></li>
                    <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>

    <main>
        <section class="firstSection">
            <div class="leftSection">
                Hi, My name is <span class="purple">Shruti</span>

                <div> and I am a </div>
                <span id="element"></span>
                <div class="a">
                    <a class="btn" href="SHRUTI_SABLE_RESUME.pdf">Download Resume</a>
                    <a class="btn" href="https://github.com/shrutisable57">Github</a>
                </div>
            </div>
            <div class="rightSection">
                <img src="bg.png" alt="">

            </div>

        </section>
        <hr>
        <section class="secondsection">
            <span class="text-gray">What I have done so far</span>
            <h1>Work Experience</h1>

            <div class="Box">
                <div class="vertical">
                    <img class="image-top" src="market-research.png" alt="">
                    <div class="vertical-title">
                        Marketing Researcher (2022-2023)
                    </div>
                    <div class="vertical-desc">
                        Market research in Electronics, EV batteries, and Appliances entails understanding consumer
                        demands,
                        technological advancements, and sustainability factors to drive product innovation and market
                        success.

                    </div>
                </div>


            </div>


            </div>

        </section>


    </main>

    <footer>
        <div class="footer">
            <div class="footer-first">
                <h3>Shruti's Developer Portfolio</h3>
            </div>
            <div class="footer-second">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Service</li>
                    <li>Contact me</li>
                </ul>

            </div>
            <div class="footer-third">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Service</li>
                    <li>Contact me</li>
                </ul>

            </div>
            <div class="footer-fourth">
                <ul>
                    <li>Home</li>
                    <li>About</li>
                    <li>Service</li>
                    <li>Contact me</li>
                </ul>

            </div>
        </div>
        <div class="footer-rights">
            Copyright &#169; Shrutisportfolio.com | All right reserver
        </div>

    </footer>

    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    <!-- Load library from the CDN -->
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

    <!-- Setup and start animation! -->
    <script>
        var typed = new Typed('#element', {
            strings: ['Web Developer', 'Graphics Desginer'],
            typeSpeed: 50,
        });
    </script>
</body>

</html>
