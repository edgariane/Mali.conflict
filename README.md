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
    <style>
        #militaer-section .content {
            display: flex;
        }
        #militaer-section .text {
            flex: 1;
        }
        #militaer-section .image {
            flex: 1;
            margin-left: 20px; /* Abstand zwischen Text und Bild */
        }
        #militaer-section img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>
    <h1>Militärisches Verfassungsschema</h1>
    <div id="militaer-section">
        <div class="content">
            <div class="text">
                <p>Ein militärisches Verfassungsschema ist ein politisches System, in dem die Regierung und die politische Autorität von den Streitkräften ausgeübt werden. Typischerweise gibt es einen Militärführer oder ein Gremium von Militärs, das das Land regiert, und politische Entscheidungen werden oft von den militärischen Befehlshabern getroffen.</p>
                <h2>Merkmale eines militärischen Verfassungsschemas:</h2>
                <ul>
                    <li><strong>Militärdiktatur:</strong> Die Regierung wird von Militärs geführt, die oft durch einen Staatsstreich oder eine Revolution an die Macht gekommen sind.</li>
                    <li><strong>Zentralisierte Macht:</strong> Die politische Macht liegt in den Händen des Militärs oder eines einzelnen Militärführers, der weitreichende Befugnisse hat.</li>
                    <li><strong>Eingeschränkte politische Freiheiten:</strong> Unter einem militärischen Verfassungsschema können politische Rechte und Freiheiten stark eingeschränkt sein, da das Militär oft autoritär regiert und politische Opposition unterdrückt.</li>
                    <li><strong>Kontrolle über Institutionen:</strong> Das Militär hat oft die Kontrolle über wichtige staatliche Institutionen wie die Exekutive, die Legislative und die Justiz.</li>
                    <li><strong>Militärische Prioritäten:</strong> Unter einem militärischen Verfassungsschema werden politische Entscheidungen oft im Hinblick auf militärische Interessen und Sicherheitsprioritäten getroffen.</li>
                </ul>
                <p>In einem militärischen Verfassungsschema stehen die militärischen Führungskräfte über den zivilen Regierungsbeamten, und die politische Landschaft wird durch die Bedürfnisse und Prioritäten der Streitkräfte geprägt.</p>
            </div>
            <div class="image">
                <img src="bild.jpg" alt="Militärisches Verfassungsschema">
            </div>
        </div>
    </div>
</body>
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
