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
<section id="contact">
  <h2>Contactez-nous</h2>
  <p>Téléphone : <a href="tel:+2250747664344">0747664344</a></p>
  <p>Adresse : Yopougon Gon Maroc, Abidjan, Côte d'Ivoire</p>
</section>
< html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Catégories d'articles</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f9f9f9;
    }
    h1 {
      color: #2c3e50;
    }
    .categories {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .categorie {
      background-color: white;
      padding: 15px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      flex: 1 1 200px;
      max-width: 300px;
      text-align: center;
    }
    .categorie h2 {
      color: #2980b9;
      font-size: 1.2rem;
      margin-bottom: 10px;
    }
    .categorie p {
      color: #555;
    }
    .categorie a {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 12px;
      background-color: #2980b9;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    .categorie a:hover {
      background-color: #1c5d85;
    }
  </style>
</head>
<body>
  <h1>Nos catégories d'articles</h1>
  <div class="categories">
    <div class="categorie">
      <h2>Électronique</h2>
      <p>Découvrez une sélection d'appareils et accessoires électroniques de qualité.</p>
      <a href="categorie-electronique.html">Voir la catégorie</a>
    </div>
    <div class="categorie">
      <h2>Vêtements</h2>
      <p>Mode pour homme, femme et enfants, avec les dernières tendances.</p>
      <a href="categorie-vetements.html">Voir la catégorie</a>
    </div>
    <div class="categorie">
      <h2>Maison & Décoration</h2>
      <p>Articles pour embellir votre intérieur et votre quotidien.</p>
      <a href="categorie-maison.html">Voir la catégorie</a>
    </div>
    <div class="categorie">
      <h2>Beauté & Santé</h2>
      <p>Produits de soins, maquillage et bien-être pour toute la famille.</p>
      <a href="categorie-beaute.html">Voir la catégorie</a>
    </div>
    <!-- Ajoutez ici d'autres catégories selon vos besoins -->
  </div>
</body>
</html>
