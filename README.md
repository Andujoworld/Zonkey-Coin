<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zonkey Coin - La criptomoneda de Tijuana</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <img src="zonkey-logo.png" alt="Zonkey Coin Logo" class="logo">
            <nav>
                <ul>
                    <li><a href="#about">Acerca</a></li>
                    <li><a href="#features">Características</a></li>
                    <li><a href="#roadmap">Roadmap</a></li>
                    <li><a href="#contact">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="hero">
        <h1>Zonkey Coin</h1>
        <p>La criptomoneda que representa el espíritu de Tijuana.</p>
        <a href="#about" class="btn">Aprende Más</a>
    </section>

    <section id="about">
        <h2>¿Qué es Zonkey Coin?</h2>
        <p>Zonkey Coin es una <em>meme coin</em> basada en la blockchain de Cronos, diseñada para unir a la comunidad tijuanense y celebrar nuestras raíces con un toque de humor y tecnología.</p>
    </section>

    <section id="features">
        <h2>Características</h2>
        <div class="feature">
            <h3>Transacciones rápidas</h3>
            <p>Gracias a Cronos, Zonkey Coin permite transacciones rápidas y económicas.</p>
        </div>
        <div class="feature">
            <h3>Comunidad fuerte</h3>
            <p>Únete a una comunidad que celebra el orgullo tijuanense.</p>
        </div>
        <div class="feature">
            <h3>Sostenibilidad</h3>
            <p>Zonkey Coin apuesta por un futuro sostenible para Tijuana y el mundo.</p>
        </div>
    </section>

    <section id="roadmap">
        <h2>Roadmap</h2>
        <ol>
            <li>Lanzamiento inicial</li>
            <li>Distribución y airdrops</li>
            <li>Listado en exchanges</li>
            <li>Expansión de la comunidad</li>
        </ol>
    </section>

    <section id="contact">
        <h2>Contacto</h2>
        <p>¿Tienes preguntas? ¡Escríbenos!</p>
        <form>
            <input type="email" placeholder="Tu correo" required>
            <textarea placeholder="Tu mensaje" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>© 2024 Zonkey Coin. Todos los derechos reservados.</p>
    </footer>

    <script src="script.js"></script>
</body>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background: #222;
    color: #fff;
    padding: 20px 0;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 90%;
    margin: auto;
}

header ul {
    list-style: none;
    display: flex;
}

header ul li {
    margin-left: 20px;
}

header ul li a {
    color: white;
    text-decoration: none;
}

.hero {
    text-align: center;
    padding: 100px 20px;
    background: #f9f9f9;
}

.hero .btn {
    padding: 10px 20px;
    background: #007bff;
    color: white;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 50px 20px;
    width: 80%;
    margin: auto;
}

footer {
    text-align: center;
    padding: 20px;
    background: #222;
    color: #fff;
}
// Simple script for form submission
document.querySelector('form').addEventListener('submit', function(event) {
    event.preventDefault();
    alert('Gracias por tu mensaje. Te responderemos pronto.');
});
</html>
