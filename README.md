
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Gombka – Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #0d0d0d;
      color: #ffffff;
    }
    header {
      background: linear-gradient(135deg, #5e0066, #a000b0);
      padding: 100px 20px 60px;
      text-align: center;
    }
    header h1 {
      font-size: 4em;
      margin-bottom: 20px;
      font-weight: bold;
      letter-spacing: 2px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
   .nav-btn {
  background-color: #000;
  border: 2px solid #fff;
  border-radius: 30px;
  padding: 15px 30px;
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
    }
    .hover-reveal {
      position: relative;
      background-color: #1a1a1a;
      padding: 30px;
      border-radius: 12px;
      overflow: hidden;
      transition: background 0.3s;
      cursor: pointer;
    }
    .hover-reveal .content {
      opacity: 0;
      transition: opacity 0.4s ease;
    }
    .hover-reveal:hover .content {
      opacity: 1;
    }
    .project {
      background: #1e1e1e;
      padding: 25px;
      border-radius: 12px;
      margin-top: 30px;
      box-shadow: 0 0 10px rgba(0, 255, 255, 0.1);
      transition: background 0.3s;
    }
    .project .project-content {
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
    h2, h3 {
      color: #fff;
      margin-bottom: 15px;
    }
    p {
      color: #ccc;
      line-height: 1.6;
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

<section id="o-mnie" class="hover-reveal">
  <div class="content">
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
