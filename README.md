<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gombka – Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #000;
      color: #fff;
    }
    header {
      padding: 80px 20px 40px;
      text-align: center;
      border-bottom: 1px solid #333;
    }
    h1 {
      font-size: 3.5em;
      letter-spacing: 2px;
      color: #fff;
      margin-bottom: 10px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 30px 0;
      background-color: #000;
    }
    .nav-btn {
      background: linear-gradient(to right, #ffffff, #aaaaaa);
      border: none;
      border-radius: 30px;
      padding: 12px 30px;
      font-size: 1em;
      font-weight: bold;
      color: #000;
      cursor: pointer;
      transition: all 0.3s ease;
    }
    .nav-btn:hover {
      opacity: 0.8;
      transform: scale(1.05);
    }
    section {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
    }
    .hover-wrapper {
      position: relative;
      overflow: hidden;
      background-color: #111; /* jaśniejszy czarny */
      border-radius: 20px;
      margin-bottom: 40px;
    }
    .hidden-section {
      opacity: 0;
      transition: opacity 0.6s ease;
      padding: 20px;
    }
    .hover-wrapper:hover .hidden-section {
      opacity: 1;
    }
    iframe {
      max-width: 100%;
      border: none;
      margin-top: 20px;
      border-radius: 10px;
    }
    footer {
      text-align: center;
      padding: 40px 0;
      font-size: 0.9em;
      color: #666;
    }
  </style>
</head>
<body>

  <header>
    <h1>Gombka</h1>
    <p>Moje portfolio</p>
  </header>

  <nav>
    <button class="nav-btn" onclick="scrollToSection('o-mnie')">O mnie</button>
    <button class="nav-btn" onclick="scrollToSection('prace')">Moje prace</button>
  </nav>

  <section id="o-mnie" class="hover-wrapper">
    <div class="hidden-section">
      <h2>O mnie</h2>
      <p>Cześć! Nazywam się Gombka. Interesuję się programowaniem, tworzeniem GUI oraz eksperymentowaniem z różnymi technologiami. Lubię uczyć się nowych rzeczy i realizować kreatywne projekty. Skupiam się na praktycznym podejściu do nauki – budując, testując i publikując swoje pomysły.</p>
    </div>
  </section>

  <section id="prace" class="hover-wrapper">
    <div class="hidden-section">
      <h2>Moje prace:</h2>
      <h3>🎮 Projekt: Rzucanie pod GUI</h3>
      <p>Podpiąłem rzucanie pod GUI – efekt możesz zobaczyć na poniższym wideo:</p>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/j-_v_xRv4Y4" allowfullscreen></iframe>
    </div>
  </section>

  <footer>
    &copy; 2025 Gombka. Wszelkie prawa zastrzeżone.
  </footer>

  <script>
    function scrollToSection(id) {
      document.getElementById(id).scrollIntoView({ behavior: 'smooth' });
    }
  </script>
</body>
</html>
