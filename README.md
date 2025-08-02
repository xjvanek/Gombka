
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
      line-height: 1.6;
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
    }
    .nav-btn {
      background-color: #000;
      border: 2px solid #fff;
      border-radius: 30px;
      padding: 12px 30px;
      font-size: 1em;
      font-weight: bold;
      color: #fff;
      cursor: pointer;
      transition: all 0.3s ease;
    }
    .nav-btn:hover {
      background-color: #111;
      color: #0ff;
      border-color: #0ff;
    }
    section {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
      transition: opacity 0.5s ease;
    }
    .hover-wrapper {
      position: relative;
      overflow: hidden;
    }
    .hidden-section {
      opacity: 0;
      transition: opacity 0.4s ease;
    }
    .hover-wrapper:hover .hidden-section {
      opacity: 1;
    }
    .project {
      background: #111;
      padding: 25px;
      border-radius: 12px;
      margin-bottom: 30px;
      box-shadow: 0 0 15px rgba(0, 255, 255, 0.1);
    }
    iframe {
      width: 100%;
      height: 400px;
      border: none;
      border-radius: 10px;
      margin-top: 15px;
    }
    footer {
      text-align: center;
      padding: 30px;
      background: #000;
      color: #777;
      font-size: 0.9em;
      margin-top: 60px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Gombka</h1>
  </header>

  <nav>
    <button class="nav-btn" onclick="document.getElementById('o-mnie').scrollIntoView({behavior: 'smooth'})">O mnie</button>
    <button class="nav-btn" onclick="document.getElementById('prace').scrollIntoView({behavior: 'smooth'})">Moje prace</button>
  </nav>

  <section id="o-mnie" class="hover-wrapper">
    <div class="hidden-section">
      <h2>O mnie</h2>
      <p>
        Cześć! Nazywam się Gombka. Interesuję się programowaniem, tworzeniem GUI oraz
        eksperymentowaniem z różnymi technologiami. Lubię uczyć się nowych rzeczy i
        realizować kreatywne projekty. Skupiam się na praktycznym podejściu do nauki –
        budując, testując i publikując swoje pomysły.
      </p>
    </div>
  </section>

  <section id="prace" class="hover-wrapper">
    <div class="hidden-section">
      <h2>Moje prace:</h2>
      <div class="project">
        <h3>🎮 Projekt: Rzucanie pod GUI</h3>
        <p>Podpiąłem rzucanie pod GUI – efekt możesz zobaczyć na poniższym wideo:</p>
        <iframe src="https://www.youtube.com/embed/j-_v_xRv4Y4" allowfullscreen></iframe>
      </div>
    </div>
  </section>

  <footer>
    &copy; 2025 Gombka. Wszelkie prawa zastrzeżone.
  </footer>

</body>
</html>
