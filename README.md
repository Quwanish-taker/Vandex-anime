# Vandex-anime
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vandex - Anime Hub</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Vandex</h1>
        <p>Your gateway to the anime world</p>
    </header>

    <main>
        <section class="anime-links">
            <h2>Popular Anime</h2>
            <ul>
                <li><a href="https://www.crunchyroll.com/one-piece" target="_blank">One Piece</a></li>
                <li><a href="https://www.funimation.com/shows/naruto" target="_blank">Naruto</a></li>
                <li><a href="https://www.crunchyroll.com/attack-on-titan" target="_blank">Attack on Titan</a></li>
                <li><a href="https://www.funimation.com/shows/demon-slayer" target="_blank">Demon Slayer</a></li>
            </ul>
        </section>
    </main>

    <footer>
        <p>© 2025 Vandex. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    text-align: center;
    background: url('https://wallpaperaccess.com/full/1121326.jpg') no-repeat center center/cover;
    color: white;
}

header {
    background: rgba(0, 0, 0, 0.7);
    padding: 20px;
}

main {
    margin-top: 50px;
}

.anime-links ul {
    list-style: none;
    padding: 0;
}

.anime-links li {
    margin: 10px 0;
}

.anime-links a {
    color: #ffcc00;
    font-size: 18px;
    text-decoration: none;
    transition: 0.3s;
}

.anime-links a:hover {
    color: #ff6600;
}

footer {
    margin-top: 50px;
    padding: 10px;
    background: rgba(0, 0, 0, 0.7);
}
document.addEventListener("DOMContentLoaded", function() {
    console.log("Welcome to Vandex - Your Anime Hub!");
});
