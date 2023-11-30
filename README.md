# fundamentalsufv.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Sitio Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        header, nav, section, article, footer {
            margin: 10px;
            padding: 10px;
            border: 1px solid #ccc;
        }
    </style>
</head>
<body>

    <!-- Sección Principal -->
    <header>
        <h1>Bienvenido a Mi Sitio Web</h1>
        <p>¡Descubre todo sobre este increíble sitio!</p>
    </header>

    <!-- Sección de Contacto -->
    <section>
        <h2>Contacto</h2>
        <form action="/enviar-mensaje" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required><br>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required><br>

            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea><br>

            <input type="submit" value="Enviar Mensaje">
        </form>
    </section>

    <!-- Sección de Temas -->
    <section>
        <h2>Temas</h2>
        <p>Explora información interesante sobre un tema fascinante.</p>
    </section>

    <!-- Sección Sobre Mí -->
    <article>
        <h2>Sobre Mí</h2>
        <p>¡Hola! Soy [Tu Nombre], y este es mi sitio web. Aquí encontrarás información fascinante sobre diversos temas.</p>

        <h3>Currículum Vitae</h3>
        <!-- Agrega aquí tu currículum vitae -->

        <h3>Fotografías</h3>
        <!-- Agrega aquí las etiquetas de las imágenes -->

        <h3>Redes Sociales</h3>
        <!-- Agrega aquí enlaces a tus cuentas de redes sociales -->
    </article>

    <!-- Pie de Página -->
    <footer>
        <p>&copy; 2023 Mi Sitio Web. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
