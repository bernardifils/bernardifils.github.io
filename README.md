# bernardifils.fr
html/
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Bernardi & Fils Artisanats — Marbre & Finitions Haut de Gamme</title>
  <meta name="description" content="Bernardi & Fils Artisanats SASU — Expert du marbre, de la pierre naturelle, du parquet, de la moquette de pierre et des finitions haut de gamme." />
  <link href="[fonts.googleapis.com](https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Open+Sans:wght@400;500&display=swap)" rel="stylesheet">
  <style>
    :root {
      --doré: #c2a676;
      --gris: #444;
      --texte: #333;
      --fond: #ffffff;
    }
    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      color: var(--texte);
      background: var(--fond);
      scroll-behavior: smooth;
      line-height: 1.6;
    }
    header {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(255,255,255,0.95);
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 40px;
      z-index: 1000;
    }
    header img {
      height: 60px;
    }
    nav a {
      margin: 0 12px;
      text-decoration: none;
      color: var(--gris);
      font-weight: 500;
    }
    nav a:hover {
      color: var(--doré);
    }
    section {
      padding: 90px 20px;
      max-width: 1100px;
      margin: auto;
    }
    .hero {
      background: url('[images.unsplash.com](https://images.unsplash.com/photo-1576847445919-44d1c0ec2c6c?auto=format&fit=crop&w=1600&q=80)') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 200px 20px 150px;
      position: relative;
    }
    .hero::after {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0,0,0,0.45);
    }
    .hero-content {
      position: relative;
      z-index: 2;
    }
    .hero img {
      width: 180px;
      margin-bottom: 15px;
    }
    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.5em;
      margin-bottom: 15px;
    }
    .hero p {
      font-size: 1.2em;
      margin-bottom: 30px;
    }
    .cta {
      text-decoration: none;
      background: var(--doré);
      color: white;
      padding: 14px 30px;
      border-radius: 5px;
      font-weight: 600;
      transition: 0.3s;
    }
    .cta:hover { background: #a78e5a; }
    h2 {
      text-align: center;
      font-family: 'Playfair Display', serif;
      font-size: 1.9em;
      color: var(--gris);
      margin-bottom: 40px;
    }
    .galerie {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 15px;
    }
    .galerie img {
      width: 320px;
      height: 220px;
      object-fit: cover;
      border-radius: 6px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }
    .galerie img:hover {
      transform: scale(1.03);
    }
    .services-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }
    .service {
      border: 1px solid #eee;
      border-radius: 8px;
      padding: 20px;
      background: #fafafa;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    .service h3 {
      color: var(--doré);
      margin-top: 0;
    }
    #apropos {
      background: #fdfdfd;
      border-left: 4px solid var(--doré);
      padding: 60px 20px;
    }
    #contact {
      text-align: center;
    }
    #contact a {
      color: var(--doré);
      font-weight: 600;
      text-decoration: none;
    }
    footer {
      text-align: center;
      background: #f4f4f4;
      padding: 25px;
      font-size: 0.9em;
      color: #555;
    }
    @media (max-width: 768px) {
      header {
        flex-direction: column;
        padding: 6px 0;
      }
      .hero {
        padding: 150px 20px 100px;
      }
      .hero h1 { font-size: 1.8em; }
      .hero p { font-size: 1em; }
      .galerie img { width: 100%; height: auto; }
    }
  </style>
</head>
<body>
<header>
  <img src="[i.imgur.com](<a href="https://imgur.com/PIrKJqz"><img src="https://i.imgur.com/PIrKJqz.png" title="source: imgur.com" /></a>)" alt="Logo Bernardi & Fils Artisanats">
  <nav>
    <a href="#accueil">Accueil</a>
    <a href="#realisations">Réalisations</a>
    <a href="#services">Services</a>
    <a href="#apropos">À propos</a>
    <a href="#contact">Contact</a>
  </nav>
</header>
<section class="hero" id="accueil">
  <div class="hero-content">
    <img src="[i.imgur.com](https://i.imgur.com/sIXQNsf.png)" alt="Logo Bernardi & Fils Artisanats">
    <h1>L’excellence du marbre et des finitions sur‑mesure,<br> pour des intérieurs d’exception.</h1>
    <p>Expert en marbre, pierre naturelle, moquette de pierre, carrelage, parquet et finitions haut de gamme.</p>
    <a href="#contact" class="cta">Demander un devis</a>
  </div>
</section>
<section id="realisations">
  <h2>Nos Réalisations</h2>
  <div class="galerie">
    <img src="[i.imgur.com](https://i.imgur.com/FQK0rsA.jpg)" alt="Marbre réalisation 1" />
    <img src="[i.imgur.com](https://i.imgur.com/2xwSRo1.jpg)" alt="Marbre réalisation 2" />
    <img src="[i.imgur.com](https://i.imgur.com/nVr8XVj.jpg)" alt="Marbre réalisation 3" />
    <img src="[i.imgur.com](https://i.imgur.com/RR4olR8.jpg)" alt="Marbre réalisation 4" />
    <img src="[i.imgur.com](https://i.imgur.com/3W313yJ.jpg)" alt="Marbre réalisation 5" />
    <img src="[i.imgur.com](https://i.imgur.com/40SsHvL.jpg)" alt="Marbre réalisation 6" />
    <img src="[i.imgur.com](https://i.imgur.com/y35ydC0.jpg)" alt="Marbre réalisation 7" />
  </div>
</section>
<section id="services">
  <h2>Nos Services</h2>
  <div class="services-grid">
    <div class="service">
      <h3>Marbre & Pierre naturelle</h3>
      <p>Vente, pose, ponçage et cristallisation de marbres rares et pierres nobles pour des finitions d’exception.</p>
    </div>
    <div class="service">
      <h3>Moquette de pierre</h3>
      <p>Pose intérieure et extérieure — terrasses, escaliers, piscines. Esthétique et résistance garanties.</p>
    </div>
    <div class="service">
      <h3>Carrelage & Mosaïque</h3>
      <p>Pose de carrelages et mosaïques haut de gamme, grands formats, finitions précises et alignements parfaits.</p>
    </div>
    <div class="service">
      <h3>Parquet</h3>
      <p>Vente, pose et ponçage de parquet massif ou contrecollé. Finitions huilées ou vernies.</p>
    </div>
    <div class="service">
      <h3>Rénovation complète</h3>
      <p>Peinture, plaquisterie, plomberie, électricité. Gestion de chantier clé en main.</p>
    </div>
    <div class="service">
      <h3>Nettoyage & Finitions</h3>
      <p>Nettoyage post‑chantier, polissage final et contrôle qualité avant livraison.</p>
    </div>
  </div>
</section>
<section id="apropos">
  <h2>À propos</h2>
  <p><strong>Bernardi & Fils Artisanats SASU</strong> est une entreprise familiale spécialisée dans les matériaux nobles et les finitions haut de gamme.  
    Chaque projet est réalisé avec une exigence absolue, une rigueur artisanale et une précision millimétrée.  
    Du marbre à la moquette de pierre, nous créons des intérieurs raffinés, durables et élégants.</p>
</section>
<section id="contact">
  <h2>Contact</h2>
  <p>📞 <a href="tel:+33659948495">06 59 94 84 95</a><br>
     📧 <a href="mailto:Bernardilionel69@gmail.com">Bernardilionel69@gmail.com</a></p>
  <p>Contactez‑nous pour un devis ou une visite de chantier — réponse rapide garantie.</p>
  <a href="tel:+33659948495" class="cta">Appeler maintenant</a>
</section>
<footer>
  © 2024 Bernardi & Fils Artisanats – Spécialistes du marbre, pierre, moquette de pierre, carrelage et parquet.  
</footer>
</body>
</html>
