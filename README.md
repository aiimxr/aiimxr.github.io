# aiimxr.github.io
git clone https://github.com/aiimxr/aiimxr.github.io
cd aiimxr.github.io
git add .
git commit -m "Initial commit"
git push origin main
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aiimxr - Página Personal de Videojuegos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #ffffff;
            color: #333333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff4c4c;
            color: #ffffff;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #e60000;
            padding: 10px;
        }
        nav a {
            color: #ffffff;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        main {
            padding: 20px;
        }
        footer {
            background-color: #ff4c4c;
            color: #ffffff;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .content-section {
            margin: 20px 0;
        }
        .content-section h2 {
            color: #e60000;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a la Página de Aiimxr</h1>
        <p>Explora el emocionante mundo de los videojuegos</p>
    </header>
    <nav>
        <a href="#about">Sobre Mi</a>
        <a href="#projects">Proyectos</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contacto</a>
    </nav>
    <main>
        <section id="about" class="content-section">
            <h2>Sobre Mi</h2>
            <p>Hola, soy Aimar, también conocido como Aiimxr. Soy un apasionado de los videojuegos y dedico mi tiempo a explorar, analizar y compartir contenido sobre ellos. ¡Únete a mí en este viaje a través de mundos virtuales fascinantes!</p>
        </section>
        <section id="projects" class="content-section">
            <h2>Proyectos</h2>
            <p>Aquí puedes encontrar una colección de mis proyectos más recientes relacionados con videojuegos. Desde análisis detallados hasta guías completas, todo está aquí para ayudarte a mejorar tu experiencia de juego.</p>
        </section>
        <section id="blog" class="content-section">
            <h2>Blog</h2>
            <p>En mi blog, comparto mis pensamientos y opiniones sobre los últimos lanzamientos de videojuegos, así como consejos y trucos para sacar el máximo provecho de tus juegos favoritos.</p>
        </section>
        <section id="contact" class="content-section">
            <h2>Contacto</h2>
            <p>¿Tienes alguna pregunta o quieres colaborar? No dudes en <a href="mailto:aiimxr@example.com">contactarme por correo electrónico</a>.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Aiimxr. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
