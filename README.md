<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Montewiki</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: #000;
            color: #fff;
            text-align: center;
        }

        /* Header Styles */
        header {
            background: #ff6f61;
            color: #fff;
            padding: 20px 0;
        }

        /* Button Styles */
        .button {
            background: #4b0082; /* Color espacial */
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            transition: background 0.3s, transform 0.3s;
            text-decoration: none; /* Para enlaces */
            display: inline-block; /* Para centrar el botón */
        }

        .button:hover {
            background: #7a1e8a; /* Color al pasar el ratón */
            transform: scale(1.05); /* Efecto de escala */
        }

        /* Footer Styles */
        footer {
            background: #333;
            color: #fff;
            padding: 10px 0;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Montewiki</h1>
    </header>
    <section>
        <h2>Bienvenue sur le site de Montewiki</h2>
        <p>Nous sommes ravis de vous accueillir. Explorez nos services et solutions innovantes.</p>
        <a href="#services" class="button">Découvrez nos services</a>
    </section>
    <footer>
        <p>&copy; 2025 Montewiki. Tous droits réservés.</p>
    </footer>
</body>
</html>
