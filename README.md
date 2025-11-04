<html>
‎<html lang="fr">
‎<head>
<meta charset="UTF-8">
‎    <meta name="viewport" content="width=device-width, initial-scale=1.0">
‎    <title>Tchakoumbier Service - Accueil</title>
‎    <style>
‎        body {
‎            font-family: 'Segoe UI', Arial, sans-serif;
‎            margin: 0;
‎            background: #fffefa;
‎            color: #292929;
‎        }
header {
‎            background: linear-gradient(90deg, #ffd891 0%, #ffb400 80%);
‎            padding: 24px 10px 12px 10px;
‎            text-align: center;
‎        }
‎        .logo-container {
‎            width: 120px;
‎            margin: 0 auto 20px auto;
‎        }
‎        .logo-container img {
‎            width: 110px;
‎            height: auto;
}
‎        h1 {
‎            font-size: 2.2em;
‎            letter-spacing: 1px;
‎            margin: 7px 0 3px 0;
‎        }
‎        .slogan {
‎            font-size: 1.2em;
‎            font-style: italic;
‎            color: #b46b00;
‎            margin-bottom: 18px;
‎        }
‎        nav ul {
‎            list-style:none;
‎            margin:0;
‎            padding:0;
‎            display:flex;
‎            gap:24px;
‎            justify-content:center;
‎            flex-wrap:wrap;
‎        }
‎        nav ul li a {
‎            text-decoration: none;
‎            color: #b46b00;
‎            font-weight: bold;
‎            font-size: 1em;
‎        }
‎        nav ul li a:hover {
‎            color: #4b3407;
‎        }
‎        .hero {
‎            margin: 28px auto 0 auto;
‎            text-align: center;
 }
‎        .hero-img {
‎            width: 100%;
‎            max-width: 430px;
‎            border-radius: 10px;
‎            box-shadow: 0 7px 30px #ffe7ca;
‎            margin: 0 auto 22px;
‎        }
‎        .cta-btn {
‎            background: #ffb400;
‎            color: #fff;
‎            padding: 13px 34px;
‎            border: none;
‎            border-radius: 7px;
‎            font-size:1.13em;
‎            font-weight:bold;
‎            cursor: pointer;
‎            margin-top:16px;
‎            box-shadow: 0 2px 11px #ffd89194;
‎            transition: background .2s;
‎        }
‎        .cta-btn:hover {
‎            background: #b46b00;
‎        }
‎        @media (max-width:640px) {
‎            h1 { font-size: 1.25em; }
‎            .hero-img { max-width: 98vw; }
‎            nav ul { gap: 9px; font-size:.98em;}
‎        }
‎    </style>
‎</head>
‎<body>
‎    <header>
‎        <div class="logo-container">
‎            <!-- Remplace l’URL ci-dessous par celle de ton logo généré -->
‎            <img src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/3b93e499-e9c6-4ecc-977c-1bd80fd94218.png" alt="Logo Tchakoumbier Service">
‎        </div>
‎        <h1>Tchakoumbier Service</h1>
‎        <div class="slogan">
‎            La qualité à portée de main
‎        </div>
‎        <nav>
‎            <ul>
‎                <li><a href="#accueil">Accueil</a></li>
‎                <li><a href="#categories">Catégories</a></li>
‎                <li><a href="#apropos">À propos</a></li>
‎                <li><a href="#contact">Contact</a></li>
</ul>
‎        </nav>
‎    </header>
‎    <main>
‎        <section class="hero" id="accueil">
‎            <img class="hero-img"
‎                src="https://user-gen-media-assets.s3.amazonaws.com/seedream_images/d6569ab1-025a-4756-986f-9685bf7db43d.png"
‎                alt="Visuel d'accueil du site Tchakoumbier Service">
‎            <h2>Bienvenue !</h2>
‎            <p>Découvrez notre sélection d’articles variés (vêtements, accessoires, électronique, maison…) dans une ambiance chaleureuse et résolument locale.</p>
‎            <button class="cta-btn" onclick="window.location='#categories'">Voir nos produits</button>
‎        </section>
‎    </main>
‎</body>
‎</html>
