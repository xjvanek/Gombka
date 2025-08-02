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
      background-color: #0d0d0d;
      color: #fff;
      overflow-x: hidden;
    }
    header {
      background: linear-gradient(135deg, #5e0066, #a000b0);
      padding: 100px 20px 60px;
      text-align: center;
      position: relative;
    }
    header h1 {
      font-size: 4em;
      margin: 0;
      font-weight: bold;
      color: #fff;
      letter-spacing: 2px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }
    .nav-btn {
      background: linear-gradient(to right, #800080, #e100ff);
      border: none;
      border-radius: 30px;
      padding: 15px 30px;
      font-size: 1em;
      font-weight: bold;
      color: #fff;
      cursor: pointer;
      transition: transform 0.2s, box-shadow 0.3s;
    }
    .nav-btn:hover {
      transform: translateY(-3px);
      box-shadow: 0 5px 20px rgba(255, 0, 255, 0.4);
    }
    section {
      max-width: 900px;
      margin: auto;
      padding: 40px 20px;
    }
    .hidden-section {
      background: #1a1a1a;
      border-radius: 12px;
      padding: 30px;
      opacity: 0;
      transition: opacity 0.4s ease;
      box-shadow: 0 0 10px rgba(255, 0, 255, 0.1);
    }
    .hover-wrapper {
      cursor: pointer;
    }
    .hover-wrapper:hover .hidden-section {
      opacity: 1;
    }
    .project {
      background: #1e1e1e;
      padding: 25px;
      border-radius: 12px;
      margin-top: 30px;
      box-shadow: 0 0 10px rgba(0, 255, 255, 0.1);
      cursor: pointer;
    }
    .project-content {
      opacity: 0;
      transition: opacity 0.4s ease;
    }
    .project:hover .project-content {
      opacity: 1;
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
    }
  </style>
</head>
<body>

<header>
  <h1>Gombka</h1>
  <nav>
    <button class="nav-btn" onclick="document.getElementById('o-mnie').scrollIntoView({behavior:'smooth'})">ABOUT ME</button>
    <button class="nav-btn" onclick="document.getElementById('prace').scrollIntoView({behavior:'smooth'})">PROJECT</button>
  </nav>
</header>

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

<section id="prace">
  <h2 style="text-align:center; margin-bottom: 20px;">Moje prace:</h2>

  <div class="project">
    <div class="project-content">
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
