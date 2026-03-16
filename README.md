# bernardifils.github.io
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Bernardi & Fils Artisanats SASU – Vente et pose de marbre, carrelage, parquet et rénovation complète." />
  <title>Bernardi & Fils Artisanats SASU</title>
  <style>
    :root {
      --couleur-principale: #c2a676; /* doré élégant */
      --fond-clair: #ffffff;
      --texte: #333;
    }
    body {
      font-family: "Georgia", serif;
      margin: 0;
      background: var(--fond-clair);
      color: var(--texte);
      line-height: 1.6;
    }
    header {
      background: white;
      border-bottom: 1px solid #ddd;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 40px;
      flex-wrap: wrap;
    }
    header img {
      height: 60px;
    }
    nav a {
      text-decoration: none;
      color: #555;
      margin: 0 12px;
      font-weight: 500;
    }
    nav a:hover {
      color: var(--couleur-principale);
    }
    .hero {
      background: url('[images.unsplash.com](https://images.unsplash.com/photo-1576847445919-44d1c0ec2c6c?auto=format&fit=crop&w=1600&q=80)') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 120px 20px;
    }
    .hero h2 {
      font-size: 2.3em;
      margin-bottom: 10px;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.7);
    }
    .hero p {
      font-size: 1.2em;
      margin-bottom: 25px;
      text-shadow: 1px 1px 2px rgba(0,0,0,0.6);
    }
    .hero a {
      text-decoration: none;
      background: var(--couleur-principale);
      color: white;
      padding: 12px 25px;
      border-radius: 4px;
      font-weight: bold;
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h3 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 1.7em;
      color: #444;
    }
    .services {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      text-align: center;
    }
    .service {
      flex: 1 1 220px;
      padding: 15px;
      margin: 10px;
      border: 1px solid #eee;
      border-radius: 8px;
      transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out;
    }
    .service:hover {
      transform: translateY(-4px);
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    }
    .service h4 {
      color: var(--couleur-principale);
    }
    .about {
      text-align: center;
      font-size: 1.1em;
      color: #555;
    }
    .realisations img {
      width: 100%;
      border-radius: 6px;
      margin-bottom: 15px;
    }
    .contact {
      text-align: center;
    }
    form {
      max-width: 400px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }
    input, textarea {
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background: var(--couleur-principale);
      color: white;
      border: none;
      padding: 12px;
      border-radius: 4px;
      font-size: 1em;
      cursor: pointer;
    }
    button:hover {
      background: #a78e5a;
    }
    footer {
      background: #f2f2f2;
      text-align: center;
      padding: 25px;
      font-size: 0.9em;
      color: #666;
    }
    @media (max-width: 700px) {
      header {
        flex-direction: column;
      }
      nav {
        margin-top: 10px;
      }
      .services {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Logo Bernardi & Fils Artisanats" />
    <nav>
      <a href="#accueil">Accueil</a>
      <a href="#services">Services</a>
      <a href="#realisations">Réalisations</a>
      <a href="#apropos">À propos</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <section class="hero" id="accueil">
    <h2>L’élégance du marbre, la précision de l’artisanat</h2>
    <p>Vente et pose de marbre, carrelage, parquet, rénovation et finitions de qualité.</p>
    <a href="#contact">Demander un devis</a>
  </section>
  <section id="services">
    <h3>Nos Services</h3>
    <div class="services">
      <div class="service">
        <h4>Marbre & Pierre naturelle</h4>
        <p>Vente, pose, ponçage et cristallisation pour un rendu d’exception.</p>
      </div>
      <div class="service">
        <h4>Revêtements de sols</h4>
        <p>Carrelage, mosaïque moquette de marbre et parquet — élégance et durabilité au quotidien.</p>
      </div>
      <div class="service">
        <h4>Rénovation complète</h4>
        <p>Peinture, plaquiste, plomberie et électricité, clé en main.</p>
      </div>
      <div class="service">
        <h4>Finitions & Nettoyage</h4>
        <p>Nettoyage de fin de chantier et remise à neuf parfaite.</p>
      </div>
    </div>
  </section>
  <section id="apropos">
    <h3>À propos</h3>
    <div class="about">
      <p><strong>Bernardi & Fils Artisanats SASU</strong> est une entreprise familiale reconnue pour son sérieux et la qualité de ses réalisations.  
      De la pierre naturelle au parquet, chaque projet est mené avec la précision d’un artisan passionné.</p>
    </div>
  </section>
  <section id="realisations">
    <h3>Nos Réalisations</h3>
    <div class="realisations">
      <img src="[images.unsplash.com](https://images.unsplash.com/photo-1615561048562-a2cde3f5aa0e?auto=format&fit=crop&w=900&q=80)" alt="Sol en marbre" />
      <img src="[images.unsplash.com](https://images.unsplash.com/photo-1599204854871-4090eea212cd?auto=format&fit=crop&w=900&q=80)" alt="Parquet et finitions" />
    </div>
  </section>
section id="contact">
    <h3>Contact</h3>
    <div class="contact">
      <p>📞 <a href="tel:+33659948495">06 59 94 84 95</a><br />
         📧 <a href="mailto:bernardilionel69@gmail.com">bernardilionel69@gmail.com</a></p>
      <p>Nous répondrons rapidement à toutes vos demandes de devis ou de renseignements.</p>
    </div>
  </section>
  <footer>
    © 2024 Bernardi & Fils Artisanats SASU – Tous droits réservés
  </footer>
</body>
</html> 
</html>
