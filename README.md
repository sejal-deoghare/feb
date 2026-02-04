<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Happy Month Anniversary</title>

    <style>
        body {
            margin: 0;
            font-family: Verdana, Geneva, Tahoma, sans-serif, sans-serif;
            background: #ff5c8a;

            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .page {
            width: 100%;
            max-width: 650px;
            padding: 25px;

            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 20px;
        }

        .hidden {
            display: none;
        }

        .box {
            background: rgb(251, 237, 237);

            padding: 25px;
            border-radius: 20px;

            text-align: center;

            width: 100%;
            box-shadow: 0 10px 25px rgba(0, 0, 0, 0.1);

        }


        button {
            margin-top: 15px;
            padding: 10px 22px;

            border: none;
            border-radius: 22px;

            background: #ff5c8a;

            color: white;

            font-size: 15px;

            cursor: pointer;
        }
    </style>
</head>

<body>

    <div class="page" id="one">


        <div class="box">
            <p>
                31 months with you feels like a beautiful story still being written.<br>
                Every day with you adds more love to my heart.<br>

                You’re my comfort, my smile, my safe place.<br>
                Here’s to us❤️
            </p>

            <h2>Happy Month Anniversary 💕</h2>
            <p><strong>Piyush Bubaaa</strong></p>

            <p>5 July 2023 → 5 February 2026</p>
            <p>Still choosing each other ✨</p>

            <button onclick="next('one','two')">Next</button>
        </div>
    </div>



    <div class="page hidden" id="two">

        <div class="box">
            <h3>Our Journey 🕰️</h3>
            <p>

                The day we started 💫<br>
                The laughs we shared 😂<br>

                The fights we survived 🤍<br>
                Every month we chose
                love 💕

            </p>

            <button onclick="next('two','three')">Next</button>
        </div>
    </div>



    <div class="page hidden" id="three">
       
        <div class="box">


            <h2>31 Months 💖</h2>

            <p>Still choosing you.


            </p>
            <p>With you, I feel protected and safe.
                You never dim my light you guard it.
                Thank you for being my home❤️</p>

            <button onclick="next('three','four')">Next</button>
        </div>
    </div>




    <div class="page hidden" id="four">
        
        <div class="box">
            <p>
                Loving you hasn’t always been easy,<br>
                but it’s always been worth it🤍

            </p>
            <button onclick="next('four','five')">Next

            </button>

        </div>
    </div>



    <div class="page hidden" id="five">
       
        <div class="box">

            <h2>I Choose You ❤️</h2>
            <p>Every month. Every year.</p>

            <p>Happy 31 Monts to US💕</p>
        </div>
    </div>


    <script>
        function next(current, nextPage) {
            document.getElementById(current).classList.add("hidden");
            document.getElementById(nextPage).classList.remove("hidden");
        }
    </script>

</body>

</html>
