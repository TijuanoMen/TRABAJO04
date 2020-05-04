<html>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <tittle>Tarea 4</tittle>
    <link rel="stylesheet" href="./css/Tarea4.css">
</head>

<body>
    <header id="header" class="theme-green">
        <h3>Películas</h3>
    </header>
    <section id="pelis" class="after-fixed">
        <p id="pelis-y-mas"></p>
        <nav class="flex-colum-center">
            <button onclick="alert('Mira lo nuevo que traemos para ti')">Evento disparado como atributo del HTML</button>
            <button id="say-hi">Evento disparado con un manejador de eventos</button>
            <button id="cambio-de-color">Cabecera gris</button>
            <button id="cambio-de-tarjeta">Cambiar a figuras</button>
        </nav>
        <article id="images" class="container post cards">
            <figure class="tarjeta">
                <img src="images/Hunger-Games.jpg" alt="hunger-games">
                <p>Hunger Games</p>
            </figure>
            <figure class="tarjeta">
                <img src="images/Harry-Potter.jpg" alt="harry-potter">
                <p>Harry Potter</p>
            </figure>
            <figure class="tarjeta">
                <img src="images/Star-Wars.jpg" alt="star-wars">
                <p>Star Wars</p>
            </figure>
        </article>
        <article class="flex-colum-center">
            <h3 class="Clock-title">h3</h3>
            <h3 class="Clock">h3 clock</h3>
            <nav class="flex-colum-center">
                <button id="start-alarm">Iniciar Alarma</button>
                <button id="stop-alarm">Detener Alarma</button>
            </nav>
            <audio id="audioMarc">
                <source src="sound/Nihilore.mp3" type="audio/mpeg"> Your browser does not support the audio element.
            </audio>
        </article>
    </section>
    <script src="./JS/Tarea4.js"></script>
</body>

</html>
