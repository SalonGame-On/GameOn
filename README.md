# GameOn
SALÓN DE ARCADE GAME-ON        
<!DOCTYPE html><html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Game-On Arcade</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #111;
            color: white;
        }
        header {
            background-color: #222;
            padding: 20px;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #ffcc00;
            text-decoration: none;
            font-size: 18px;
        }
        section {
            padding: 20px;
            margin: 20px auto;
            width: 80%;
            background-color: #222;
            border-radius: 10px;
        }
        .game-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }
        .game-gallery img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            margin-top: 20px;
            padding: 10px;
            background-color: #222;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenidos a Game-On Arcade</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#juegos">Juegos</a></li>
                <li><a href="#eventos">Eventos</a></li>
                <li><a href="#tienda">Tienda</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header><section id="inicio">
    <h2>Experiencia Arcade Única</h2>
    <p>Disfruta de los mejores juegos clásicos y modernos en un ambiente inmersivo.</p>
</section>

<section id="juegos">
    <h2>Catálogo de Juegos</h2>
    <p>Explora nuestra colección de juegos arcade y simuladores.</p>
    <div class="game-gallery">
        <img src="images/street_fighter.jpg" alt="Street Fighter">
        <img src="images/pacman.jpg" alt="Pac-Man">
        <img src="images/mortal_kombat.jpg" alt="Mortal Kombat">
        <img src="images/galaga.jpg" alt="Galaga">
        <img src="images/donkey_kong.jpg" alt="Donkey Kong">
        <img src="images/mario_kart.jpg" alt="Mario Kart">
        <img src="images/tekken.jpg" alt="Tekken">
        <img src="images/time_crisis.jpg" alt="Time Crisis">
    </div>
</section>

<section id="eventos">
    <h2>Eventos y Torneos</h2>
    <p>Consulta nuestro calendario de eventos y participa en torneos emocionantes.</p>
</section>

<section id="tienda">
    <h2>Tienda Online</h2>
    <p>Compra fichas, membresías y productos exclusivos de Game-On.</p>
</section>

<section id="contacto">
    <h2>Ubicación y Contacto</h2>
    <p>Encuéntranos en: C. 19-A Sur, Galaxia Castillotla, 72498 Heroica Puebla de Zaragoza, Pue.</p>
    <p>Teléfono: 222 598 3313</p>
</section>

<footer>
    <p>&copy; 2025 Game-On Arcade. Todos los derechos reservados.</p>
</footer>

</body>
</html>
