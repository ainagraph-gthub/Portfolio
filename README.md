# Portfolio
Présentation de mon service
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>AinaGraph | Portfolio Vidéo</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
</head>
<body>

<header>
    <h1>AinaGraph</h1>
    <p>Monteur vidéo & Motion Designer</p>
</header>

<section id="portfolio">
    <h2>Mes vidéos</h2>

    <div class="video-grid">

        <!-- 🔽 VIDÉO 1 -->
        <div class="video-card">
            <video controls>
                <source src="videos/video1.mp4" type="video/mp4">
                Ton navigateur ne supporte pas la vidéo.
            </video>
            <h3>Vidéo publicitaire</h3>
            <p>Montage dynamique pour réseaux sociaux</p>
        </div>

        <!-- 🔽 VIDÉO 2 -->
        <div class="video-card">
            <video controls>
                <source src="videos/video2.mp4" type="video/mp4">
            </video>
            <h3>Motion Design</h3>
            <p>Animation texte & logo</p>
        </div>


    </div>
</section>

<footer>
    <p>© 2026 AinaGraph | Portfolio vidéo</p>
</footer>

</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #0f172a;
    color: #fff;
}

header {
    text-align: center;
    padding: 40px 20px;
}

header h1 {
    font-size: 2.5rem;
}

header p {
    color: #94a3b8;
}

#portfolio {
    padding: 40px 20px;
    max-width: 1100px;
    margin: auto;
}

#portfolio h2 {
    text-align: center;
    margin-bottom: 30px;
}

.video-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
}

.video-card {
    background: #020617;
    padding: 15px;
    border-radius: 12px;
}

.video-card video {
    width: 100%;
    border-radius: 10px;
}

.video-card h3 {
    margin-top: 10px;
}

.video-card p {
    color: #94a3b8;
    font-size: 0.9rem;
}

footer {
    text-align: center;
    padding: 20px;
    color: #64748b;
}
PORTEFOLIO
 ├── index.html
 ├── styles.css
 └── videos/
     ├── video1.mp4
     ├── video2.mp4
