
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
            background-color: #0d0d0d;
            color: #fff;
            overflow-x: hidden;
            position: relative;
        }
        /* Dekoracyjne tło */
        .bg-shape {
            position: absolute;
            border-radius: 50%;
            background: white;
            opacity: 0.05;
            filter: blur(80px);
            z-index: 0;
        }
        .shape1 {
            width: 400px;
            height: 400px;
            top: 100px;
            left: -150px;
        }
        .shape2 {
            width: 300px;
            height: 300px;
            bottom: 100px;
            right: -100px;
        }
        .shape3 {
            width: 250px;
            height: 250px;
            top: 450px;
            right: 50px;
        }
        .shape4 {
            width: 350px;
            height: 350px;
            bottom: 50px;
            left: 50px;
            background: rgba(255, 255, 255, 0.08);
            filter: blur(100px);
        }
        .shape5 {
            width: 200px;
            height: 200px;
            top: 50px;
            right: -20px;
            background: rgba(255, 255, 255, 0.06);
            filter: blur(70px);
        }
        header {
            padding: 80px 20px 40px;
            text-align: center;
            position: relative;
            z-index: 1;
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
            position: relative;
            z-index: 1;
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
            position: relative;
            z-index: 1;
        }
        .hover-wrapper {
            background-color: #111;
            border-radius: 20px;
            margin-bottom: 40px;
            overflow: hidden;
            transition: background-color 0.3s ease;
        }
        .hidden-section {
            opacity: 0;
            transition: opacity 0.6s ease;
            padding: 20px;
        }
        .hover-wrapper:hover .hidden-section {
            opacity: 1;
        }
        h2,
        h3 {
            margin-bottom: 10px;
        }
        .video-container {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }
        .video-container iframe {
            flex: 1 1 45%;
            width: 100%;
            height: 315px;
            border: none;
            border-radius: 10px;
            margin-top: 20px;
        }
        .project-item {
            text-align: center;
            margin-top: 20px;
        }
        .project-item img {
            max-width: 200px;
            height: auto;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        footer {
            text-align: center;
            padding: 40px 0;
            font-size: 0.9em;
            color: #666;
            position: relative;
            z-index: 1;
        }
    </style>
</head>
<body>
    <div class="bg-shape shape1"></div>
    <div class="bg-shape shape2"></div>
    <div class="bg-shape shape3"></div>
    <div class="bg-shape shape4"></div>
    <div class="bg-shape shape5"></div>
    <header>
        <h1>Gombka - Młody Programista</h1>
        <p>Moje portfolio</p>
    </header>
    <nav>
        <button class="nav-btn" onclick="scrollToSection('o-mnie')">O mnie</button>
        <button class="nav-btn" onclick="scrollToSection('prace')">Moje prace</button>
        <button class="nav-btn" onclick="scrollToSection('projekty')">Moje projekty</button>
    </nav>
    <section id="o-mnie" class="hover-wrapper">
        <div class="hidden-section">
            <h2>O mnie</h2>
            <p>Cześć! Nazywam się Gombka. Interesuję się programowaniem, tworzeniem GUI oraz eksperymentowaniem z różnymi technologiami. Lubię uczyć się nowych rzeczy i realizować kreatywne projekty. Skupiam się na praktycznym podejściu do nauki – budując, testując i publikując swoje pomysły. Skryptuje od 2 lat (: </p>
        </div>
    </section>
    <section id="prace" class="hover-wrapper">
        <div class="hidden-section">
            <h2>Moje prace:</h2>
            <div class="video-container">
                <div>
                    <h3>🎮 Projekt: Rzucanie pod GUI</h3>
                    <iframe src="https://www.youtube.com/embed/j-_v_xRv4Y4" allowfullscreen></iframe>
                </div>
            </div>
        </div>
    </section>
    <section id="projekty" class="hover-wrapper">
        <div class="hidden-section">
            <h2>Moje projekty</h2>
            <div class="project-item">
                <img src="16166d0542bcc11ef9ff59d0d396adac.webp" alt="Logo gry WLPN" />
                <h3>WLPN</h3>
                <p>Pracowałem przy tym projekcie jako deweloper i własciciel, jednak obecnie nie jestem już z nim związany.</p>
            </div>
        </div>
    </section>
    <footer>
        © 2025 Gombka. Wszelkie prawa zastrzeżone.
    </footer>
    <script>
        function scrollToSection(id) {
            document.getElementById(id).scrollIntoView({
                behavior: 'smooth'
            });
        }
    </script>
</body>
