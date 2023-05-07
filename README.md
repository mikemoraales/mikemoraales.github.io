<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="bonito.css">
    <title>Mi Blog Personal</title>
</head>

<body>
    <style>
        body {
            font-family: Arial, sans-serif;
            font-size: 16px;
            line-height: 1.5;
            color: #333333;
            background-color: #6c7070;
        }

        /* Encabezado */
        header {
            background-image: url('clark-street-mercantile-P3pI6xzovu0-unsplash.jpg');
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center center;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            color: #FFFFFF;
        }

        /* Menú de navegación */
        nav {
            margin-top: 10px;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        nav li {
            margin: 0 10px;
        }

        nav a {
            display: block;
            padding: 10px;
            color: burlywood;
            text-decoration: none;
            transition: color 0.2s;
        }

        nav a:hover {
            color: #707070;
        }

        /* Contenido principal */
        main {
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        /* Secciones */
        section {
            flex-basis: 48%;
            margin-bottom: 20px;
            background-color: #505050;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        section h2 {
            margin-top: 0;
            margin-bottom: 10px;
            font-size: 24px;
            color: #ffffff;
        }

        section p {
            margin-bottom: 10px;
            color: #707070;
        }

        /* Enlaces */
        a {
            color: #0077FF;
            text-decoration: none;
            transition: color 0.2s;
        }

        a:hover {
            color: #333333;
        }

        /* Pie de página */
        footer {
            background-color: #FFFFFF;
            padding: 20px;
            box-shadow: 0 -2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
            font-size: 14px;
            color: #666666;
        }
    </style>
    <header>
        <h1>Mi Blog Personal</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#sobre-mi">Sobre mí</a></li>
                <li><a href="#contacto">Contacto</a></li>
                <li><a href="#galeria">Galería</a></li>
                <li><a href="#recursos">Recursos</a></li>
                <li><a href="#preguntas-frecuentes">Preguntas frecuentes</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="inicio">
            <h2>Bienvenidos a mi blog personal</h2>
            <p>Aquí encontrarás contenido interesante sobre temas como [tema de tu blog], [tema 2], [tema 3], etc.</p>
            <img src="foto-principal.jpg" alt="Foto principal de mi blog personal">
        </section>
        <section id="blog">
            <h2>Blog</h2>
            <article>
                <h3>Título de mi primera publicación</h3>
                <p>Texto de mi primera publicación.</p>
            </article>
            <article>
                <h3>Título de mi segunda publicación</h3>
                <p>Texto de mi segunda publicación.</p>
            </article>
            <!-- Aquí irían el resto de las publicaciones -->
        </section>
        <section id="sobre-mi">
            <h2>Sobre mí</h2>
            <img src="mi-foto.jpg" alt="Foto de mi perfil">
            <p>Mi nombre es [tu nombre] y soy [tu profesión o actividad]. En este blog comparto mis conocimientos y
                experiencia en [tema de tu blog].</p>
            <p>Puedes seguirme en mis redes sociales:</p>
            <ul>
                <li><a href="https://www.facebook.com/tu-pagina-de-facebook">Facebook</a></li>
                <li><a href="https://twitter.com/tu-pagina-de-twitter">Twitter</a></li>
                <li><a href="https://www.instagram.com/tu-pagina-de-instagram">Instagram</a></li>
            </ul>
        </section>
        <section id="contacto">
            <h2>Contacto</h2>
            <p>Puedes contactarme a través de este formulario:</p>
            <form>
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre">
                <label for="email">Email:</label>
                <input type="email" id="email" name="email">
                <label for="mensaje">Mensaje:</label>
                <textarea id="mensaje" name="mensaje"></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
        <section id="galeria">
            <h2>Galería</h2>
            <p>Aquí puedes encontrar algunas fotos relacionadas con mi blog:</p>
            <img src="foto-1.jpg" alt="Foto 1">
            <img src="foto-2.jpg" alt="Foto 2">
            <img src="foto-3.jpg" alt="Foto 3">
        </section>
        <section id="recursos">
            <h2>Recursos</h2>
            <p>En esta sección podrás encontrar recursos útiles relacionados con mi blog, como libros recomendados,
                herramientas y aplicaciones, etc.</p>
            <ul>
                <li><a href="#">Libro 1</a></li>
                <li><a href="#">Libro 2</a></li>
                <li><a href="#">Herramienta 1</a></li>
                <li><a href="#">Herramienta 2</a></li>
                <li><a href="#">Aplicación 1</a></li>
                <li><a href="#">Aplicación 2</a></li>
            </ul>
        </section>
        <section id="preguntas-frecuentes">
            <h2>Preguntas frecuentes</h2>
            <p>En esta sección responderé a algunas de las preguntas más frecuentes que recibo de mis lectores:</p>
            <dl>
                <dt>¿Cómo puedo contactarte?</dt>
                <dd>Puedes utilizar el formulario de contacto que se encuentra en la sección correspondiente de este
                    sitio web.</dd>

                <dt>¿Puedo colaborar contigo en algún proyecto?</dt>
                <dd>Por supuesto, estoy siempre abierto a nuevas colaboraciones. Por favor, contáctame para más
                    información.</dd>

                <dt>¿Puedo utilizar el contenido de tu blog en mi sitio web?</dt>
                <dd>No está permitido utilizar el contenido de este sitio web sin mi autorización previa.</dd>
            </dl>
        </section>
    </main>
    <footer>
        <p>Derechos reservados © [año actual] [tu nombre o nombre de tu sitio web]</p>
    </footer>
</body>

</html>
