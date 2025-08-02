<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gombka – Portfolio</title>
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
    iframe {
      width: 100%;
      height: 400px;
      border: none;
      border-radius: 10px;
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
  <h1>Gombka</h1>
  <p>Moje portfolio</p>
</header>

<nav>
  <a href="#o-mnie">O mnie</a>
  <a href="#prace">Moje prace</a>
</nav>

<section id="o-mnie">
  <h2>O mnie</h2>
  <p>Cześć! Nazywam się Gombka. Interesuję się programowaniem, tworzeniem GUI oraz eksperymentowaniem z różnymi technologiami. Lubię uczyć się nowych rzeczy i realizować kreatywne projekty. Skupiam się na praktycznym podejściu do nauki – budując, testując i publikując swoje pomysły.</p>
</section>

<section id="prace">
  <h2>Moje prace:</h2>

  <div class="project">
    <h3>🎮 Projekt: Rzucanie pod GUI</h3>
    <p>Podpiąłem rzucanie pod GUI – efekt możesz zobaczyć na poniższym wideo:</p>
    <iframe src="https://www.youtube.com/embed/j-_v_xRv4Y4" allowfullscreen></iframe>
  </div>
</section>

<footer>
  &copy; 2025 Gombka. Wszelkie prawa zastrzeżone.
</footer>

</body>
</html>
