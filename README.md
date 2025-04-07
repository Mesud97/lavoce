<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>LA VOCE</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f4f4f4;
      color: #222;
    }

    header {
      background: #000;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h1 {
      margin: 0;
      font-size: 2rem;
      letter-spacing: 2px;
    }

    nav a {
      margin-left: 1.5rem;
      color: white;
      text-decoration: none;
      font-weight: 500;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffcc00;
    }

    .hero {
      background: #eaeaea;
      padding: 3rem 2rem;
      text-align: center;
    }

    .hero h2 {
      font-size: 2.2rem;
      margin-bottom: 0.5rem;
    }

    .hero p {
      font-size: 1.1rem;
      color: #555;
    }

    .articles {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
      padding: 2rem;
    }

    .article {
      background: white;
      padding: 1.5rem;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }

    .article:hover {
      transform: translateY(-5px);
    }

    .article h3 {
      margin-top: 0;
    }

    .article p {
      color: #555;
    }

    footer {
      background: #000;
      color: #ccc;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>LA VOCE</h1>
    <nav>
      <a href="#">Ultim'ora</a>
      <a href="#">Politica</a>
      <a href="#">Cultura</a>
      <a href="#">Tecnologia</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Benvenuto su LA VOCE</h2>
    <p>Notizie indipendenti, rapide e vere. Sempre aggiornati su ciò che conta.</p>
  </section>

  <section class="articles">
    <div class="article">
      <h3>[Ultim’ora] Titolo dell’articolo</h3>
      <p>Riassunto della notizia più recente. Aggiornamenti in tempo reale...</p>
    </div>
    <div class="article">
      <h3>[Politica] Governo e nuove riforme</h3>
      <p>Analisi sulle ultime decisioni politiche e i loro impatti.</p>
    </div>
    <div class="article">
      <h3>[Cultura] Mostra d’arte a Milano</h3>
      <p>La nuova esposizione racconta la bellezza della tradizione italiana.</p>
    </div>
  </section>

  <footer>
    © 2025 LA VOCE – Tutti i diritti riservati | Contatti: redazione@lavoce.it
  </footer>

</body>
</html>
