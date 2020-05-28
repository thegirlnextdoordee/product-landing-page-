# product-landing-page-
<!DOCTYPE HTML>
<html>

<head>
    <title>Hello world</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        * {
            /*reset browser default padding and margin*/
            padding: 0;
            margin: 0;
            color: #333333;
            box-sizing: border-box;
        }

        header {}

        header::after {
            clear: both;
        }

        #logo {
            float: left;
            padding: 1%;
            font-size: 1.5em;
            color: rgb(47, 60, 73);
            font-family: Verdana, Geneva, Tahoma, sans-serif
        }

        .nav-bar {}

        /*Use for clearing the float after floating*/
        .nav-bar::after {
            content: '';
            display: block;
            clear: both;
        }

        .nav-bar ul::after {
            border: 1px solid red;
            clear: both;
        }

        .nav-bar li {
            float: right;
            list-style: none;
        }

        .nav-bar li a {
            padding: 4%;
            display: block;
            /* make the whole li element clickable as link*/
            width: 10em;
            height: 50px;
            text-decoration: none;
            text-align: center;
            line-height: 50px;
            color: #333333;
        }

        .nav-bar li a:hover {
            text-decoration: underline;
        }

        .landing {
            height: 60vh;
            background: #eeeeee;
            text-align: center;
            font-size: 2em;
        }

        .row {
            width: 70%;
            margin: auto;
            height: 50vh;
        }

        .col-6 {
            color: red;
            width: 50%;
            float: left;
            padding: 2%;
        }

        .text-center {
            text-align: center;
        }

        .bg-gray {
            background-color: #eeeeee;
        }

        .container {
            width: 80%;
            margin: auto;
        }
        .pt-5 {
            padding-top: 5%;
        }
        .pb-2 {
            padding-bottom: 2%;;
        }
        hr {
            border: 1px solid #eeeeee;
            margin:2% 0 2% 0;
        }
    
    </style>
</head>

<body>
    <header>
        <div id="logo">Logo</div>
        <nav class="nav-bar">
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">Blog</a></li>
                <li><a href="">Project</a></li>
                <li><a href="">About</a></li>
                <li><a href="">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <div class="landing">
            <h1>Hello HTML</h1>
        </div>
        <div class="container pt-5">

            <div class="row">
                <div class="col-6">
                    <h2>Why u should learn HTML</h2>
                </div>

                <div class="col-6 text-center">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius nulla rem non minus? Perferendis
                        dignissimos cupiditate eius aliquam, aspernatur repellendus quae error eveniet. Eum aliquam et
                        porro
                        ab sed itaque.</p>
                </div>
            </div>
        </div>
        <div class=" bg-gray pt-5">
            <div class="row">
                <div class="col-6 text-center">
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eius nulla rem non minus? Perferendis
                        dignissimos cupiditate eius aliquam, aspernatur repellendus quae error eveniet. Eum aliquam et
                        porro ab sed itaque.</p>
                </div>
                <div class="col-6">
                    <h2>Why u should learn HTML</h2>
                </div>

            </div>
        </div>
    </main>
    <footer class="text-center pt-5 pb-2">
        <hr>
        <p>&copy;HTML</p>
    </footer>

</body>

</html>
