# josephinehoundafoche.github.io
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Josephine HOUNDAFOCHE</title>
  <style>
    /* Couleurs et typographie */
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f8f6;
      color: #333;
    }
    a {
      color: #4a7c59;
      text-decoration: none;
      font-weight: bold;
    }
    a:hover {
      text-decoration: underline;
    }

    /* Header */
    header {
      background: url('https://images.unsplash.com/photo-1597309627194-1086bbf1b1f0?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w5NzE1NjZ8MHwxfHNlYXJjaHwxfHx3b21hbiUyMGZpZWxkJTIwY29tcHV0ZXJ8ZW58MHx8fHwxNjUwNzgyMTQ2&ixlib=rb-4.0.3&q=80&w=1400') no-repeat center center/cover;
      height: 60vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
      padding: 0 20px;
    }
    header h1 {
      font-size: 3em;
      margin: 0;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.5);
    }
    header p {
      font-size: 1.5em;
      margin-top: 10px;
      font-style: italic;
      text-shadow: 1px 1px 4px rgba(0,0,0,0.5);
    }

    /* Sections */
    section {
      max-width: 900px;
      margin: 40px auto;
      background: white;
      border-radius: 15px;
      padding: 30px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.1);
    }
    h2 {
      color: #2b4d2b;
      border-bottom: 2px solid #e3e3e3;
      padding-bottom: 5px;
      margin-bottom: 15px;
    }
    ul {
      list-style: none;
      padding-left: 0;
    }
    ul li::before {
      content: "🌿 ";
    }

    /* Footer */
    footer {
      text-align: center;
      background-color: #4a7c59;
      color: white;
      padding: 20px;
      margin-top: 40px;
    }

    /* Boutons de contact */
    .contact a {
      display: inline-block;
      margin-right: 20px;
      padding: 10px 20px;
      border: 2px solid #4a7c59;
      border-radius: 5px;
      transition: 0.3s;
    }
    .contact a:hover {
      background-color: #4a7c59;
      color: white;
    }

    /* Responsive */
    @media(max-width: 600px){
      header h1 { font-size: 2em; }
      header p { font-size: 1.2em; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Josephine HOUNDAFOCHE</h1>
    <p>🌾 Je valorise l'agriculture avec les mots justes et inspirants</p>
  </header>

  <section>
    <h2>À propos de moi</h2>
    <p>
      Diplômée en agronomie, je me consacre à la rédaction web et à la communication agricole.
      J’aide les acteurs du monde rural à valoriser leurs initiatives à travers des contenus clairs et vivants.
    </p>
  </section>

  <section>
    <h2>Mes services</h2>
    <ul>
      <li>✍️ Rédaction web</li>
      <li>🌿 Storytelling agricole</li>
      <li>💻 Communication digitale</li>
      <li>📰 Gestion de blog</li>
      <li>🛍️ Création de fiches produits</li>
      <li>📝 Description de produits</li>
    </ul>
  </section>

  <section>
    <h2>Mes réalisations</h2>
    <ul>
      <li>📄 Articles sur l’agriculture et l’agroécologie</li>
      <li>💬 Posts LinkedIn à forte valeur ajoutée</li>
      <li>🎯 Campagnes de sensibilisation</li>
      <li>📘 Fiches techniques et informatives</li>
    </ul>
  </section>

  <section class="contact">
    <h2>Contact</h2>
    <a href="mailto:houndafochejosephine@gmail.com">📧 Envoyer un email</a>
    <a href="https://www.linkedin.com/in/basilia-josephine-sedekon-houndafo" target="_blank">🔗 LinkedIn</a>
  </section>

  <footer>
    © 2025 Josephine HOUNDAFOCHE — Rédactrice web & communication agricole 🌾
  </footer>

</body>
</html>
