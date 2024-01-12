<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loading Screen</title>
    <style>
        body {
            margin: 0;
            display: flex;
            align-items: center;
            justify-content: center;
            height: 100vh;
            background-color: #f0f0f0;
        }

  #loading-screen {
            display: none;
            text-align: center;
        }
    </style>
</head>
<body>
    <div id="loading-screen">
        <h1>Loading...</h1>
    </div>
  
  <script>
        document.addEventListener("DOMContentLoaded", function () {
            var loadingScreen = document.getElementById("loading-screen");

            // Anzeige des Ladebildschirms
            loadingScreen.style.display = "block";

            // Setze einen Timeout von 5 Sekunden
            setTimeout(function () {
                // Verberge den Ladebildschirm nach 5 Sekunden
                loadingScreen.style.display = "none";
            }, 5000); // 5000 Millisekunden = 5 Sekunden
        });
    </script>
</body>
</html>

  </body>
</html>
