<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Popup-Fenster</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .overlay {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(128, 128, 128, 0.5); /* Grau, durchsichtig */
            justify-content: center;
            align-items: center;
        }
        .popup {
            background-color: #fff; /* Weiß */
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5); /* Schwarzer Schatten */
            text-align: center;
        }
        .popup a {
            color: #1E90FF; /* Blau */
            text-decoration: underline;
            cursor: pointer;
        }
        .popup a:hover {
            color: #000; /* Schwarz */
        }
        .popup button {
            margin: 10px;
            padding: 8px 15px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        .popup #okButton {
            background-color: #000; /* Schwarz */
            color: #fff; /* Weiß */
        }
        .popup #cancelButton {
            background-color: #000; /* Schwarz */
            color: #fff; /* Weiß */
        }
    </style>
</head>
<body>

<div class="overlay" id="popupOverlay">
    <div class="popup">
        <p>Mit dem Klick auf "<a href="Fehler.html" target="_self">Nutzungsbedingungen</a>" und "<a href="Fehler.html" target="_self">Richtlinien</a>" akzeptieren Sie diese.</p>
        <button id="okButton" onclick="closePopup()">OK</button>
        <button id="cancelButton" onclick="redirectAndClose()">Abbrechen</button>
    </div>
</div>

<script>
    function openPopup() {
        document.getElementById("popupOverlay").style.display = "flex";
    }

    function closePopup() {
        document.getElementById("popupOverlay").style.display = "none";
    }

    function redirectAndClose() {
        window.location.href = 'DAann Nicht.html'; // Ersetze mit der URL deines GIFs
        setTimeout(function() {
            window.open('', '_self', ''); // Öffne ein leeres Fenster im aktuellen Tab
            window.close(); // Schließe das aktuelle Fenster
        }, 5); // Schließe die Seite nach 5 Sekunden (kann je nach GIF-Länge angepasst werden)
    }
</script>
<script>
    window.onload = openPopup;
</script>

</body>
<body>
    <h2>Inhalt:</h2>
    <nav>
        <a href="#Anfang">Militärisches Verfassungsschema</a> <br>
        <a href="#Pakistan">Was hatt das mit Pakistan zu tun?</a> <br>
        <a href="#Infos">Infos über Pakistan</a> <br>
        <a href="#...">...</a> <br>
        <a href="#quellen">Quellen</a>
    </nav>
    <main>
            <h2>Militärisches Verfassungsschema</h2>
        <section id="Pakistan">
            <h2>Was hatt das mit Pakistan zu tun?</h2>
        </section>
<section id="Infos">
    <h2>Infos über Pakistan</h2>
</section>
<section>
<section id="...">
    <h2>...</h2>
</section>
<section id="quellen">
    <h2>Quellen</h2>
</section>
    <footer>
        <a href="Rick Astley - Never Gonna Give You Up (Official Music Video).mp4">Quellen</a>
        <p>&copy; 2024 Millitärisches Verfassungsschema</p>
    </footer>
