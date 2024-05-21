git clone https://github.com/aiimxr/aiimxr.github.io
cd aiimxr.github.io
git add .
git commit -m "Update webpage with new sections"
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
            margin: 40px 0;
        }
        .content-section h2 {
            color: #e60000;
        }
        .content-section img {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 10px 0;
        }
        .content-section video {
            max-width: 100%;
            height: auto;
            display: block;
            margin: 10px 0;
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
        <a href="#videos">Videos</a>
        <a href="#photos">Fotos</a>
        <a href="#contact">Contacto</a>
    </nav>
    <main>
        <section id="about" class="content-section">
            <h2>Sobre Mi</h2>
            <p>Hola, soy Aimar, también conocido como Aiimxr. Soy un apasionado de los videojuegos y dedico mi tiempo a explorar, analizar y compartir contenido sobre ellos. ¡Únete a mí en este viaje a través de mundos virtuales fascinantes!</p>
            <p>He jugado y analizado una amplia variedad de juegos a lo largo de los años. Me encanta compartir mis experiencias y ayudar a otros jugadores a mejorar sus habilidades y disfrutar más de sus juegos favoritos.</p>
        </section>
        <section id="projects" class="content-section">
            <h2>Proyectos</h2>
            <p>Aquí puedes encontrar una colección de mis proyectos más recientes relacionados con videojuegos. Desde análisis detallados hasta guías completas, todo está aquí para ayudarte a mejorar tu experiencia de juego.</p>
            <p>Algunos de mis proyectos incluyen:</p>
            <ul>
                <li>Análisis en profundidad de juegos como <em>The Legend of Zelda</em> y <em>Dark Souls</em>.</li>
                <li>Guías paso a paso para completar desafíos y misiones complicadas.</li>
                <li>Tutoriales sobre técnicas avanzadas de juego.</li>
            </ul>
        </section>
        <section id="blog" class="content-section">
            <h2>Blog</h2>
            <p>En mi blog, comparto mis pensamientos y opiniones sobre los últimos lanzamientos de videojuegos, así como consejos y trucos para sacar el máximo provecho de tus juegos favoritos.</p>
            <p>Algunos temas recientes en mi blog incluyen:</p>
            <ul>
                <li>Reseñas de nuevos lanzamientos.</li>
                <li>Comparaciones entre diferentes títulos y géneros.</li>
                <li>Reflexiones sobre la evolución de los videojuegos a lo largo del tiempo.</li>
            </ul>
        </section>
        <section id="videos" class="content-section">
            <h2>Videos</h2>
            <p>Aquí puedes ver algunos de mis videos más recientes sobre videojuegos:</p>
            <video controls>
                <source src="ruta/a/tu/video.mp4" type="video/mp4">
                Tu navegador no soporta la etiqueta de video.
            </video>
            <p>También puedes ver mis videos en mi canal de YouTube:</p>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/ID_DE_VIDEO" frameborder="0" allowfullscreen></iframe>
        </section>
        <section id="photos" class="content-section">
            <h2>Fotos</h2>
            <p>Aquí tienes algunas fotos relacionadas con mis experiencias en el mundo de los videojuegos:</p>
            <img src="ruta/a/tu/foto1.jpg" alt="Descripción de la foto 1">
            <img src="ruta/a/tu/foto2.jpg" alt="Descripción de la foto 2">
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
