# gombkawportfolio
porfolio luau scripter
<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Twoje Imię – Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #f8f9fa;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #4b6cb7;
      background: linear-gradient(to right, #182848, #4b6cb7);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
      font-size: 2.5em;
    }
    nav {
      text-align: center;
      margin: 20px 0;
    }
    nav a {
      margin: 0 10px;
      text-decoration: none;
      color: #4b6cb7;
      font-weight: bold;
    }
    section {
      max-width: 900px;
      margin: auto;
      padding: 20px;
    }
    .project {
      background: white;
      margin: 20px 0;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }
    footer {
      text-align: center;
      padding: 30px;
      font-size: 0.9em;
      color: #777;
    }
  </style>
</head>
<body>

<header>
  <h1>Twoje Imię i Nazwisko</h1>
  <p>Front-End Developer | Designer | Kreatywny Umysł</p>
</header>

<nav>
  <a href="#o-mnie">O mnie</a>
  <a href="#projekty">Projekty</a>
  <a href="#kontakt">Kontakt</a>
</nav>

<section id="o-mnie">
  <h2>O mnie</h2>
  <p>Cześć! Nazywam się [Twoje imię]. Zajmuję się projektowaniem i tworzeniem nowoczesnych, responsywnych stron internetowych. Kocham łączyć estetykę z funkcjonalnością. Pracuję z HTML, CSS, JavaScript oraz narzędziami jak Figma, React czy WordPress.</p>
</section>

<section id="projekty">
  <h2>Wybrane projekty</h2>

  <div class="project">
    <h3>🌤️ Aplikacja pogodowa</h3>
    <p>Stworzona w React + API OpenWeather. Umożliwia szybkie sprawdzenie pogody w dowolnym mieście.</p>
    <a href="#" target="_blank">Zobacz projekt</a>
  </div>

  <div class="project">
    <h3>🛍️ Sklep online z modą</h3>
    <p>Prosty e-commerce z HTML/CSS i JavaScript. W pełni responsywny, gotowy do wdrożenia.</p>
    <a href="#" target="_blank">Zobacz projekt</a>
  </div>

</section>

<section id="kontakt">
  <h2>Kontakt</h2>
  <p>Masz pytanie lub chcesz współpracować?</p>
  <p><strong>Email:</strong> <a href="mailto:twojemail@example.com">twojemail@example.com</a></p>
  <p><strong>LinkedIn:</strong> <a href="https://linkedin.com/in/twojprofil" target="_blank">linkedin.com/in/twojprofil</a></p>
</section>

<footer>
  &copy; 2025 Twoje Imię. Wszelkie prawa zastrzeżone.
</footer>

</body>
</html>

