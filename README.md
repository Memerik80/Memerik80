- <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Asociación</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .section {
            margin-bottom: 20px;
        }
        .section h2 {
            color: #333;
        }
        .gallery img {
            width: 100%;
            height: auto;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Asociación</h1>
    </header>
    <nav>
        <a href="#servicios">Servicios</a>
        <a href="#proyectos">Proyectos</a>
        <a href="#contacto">Contacto</a>
        <a href="#galeria">Galería</a>
    </nav>
    <div class="container">
        <div id="servicios" class="section">
            <h2>Servicios</h2>
            <p>Ofrecemos actividades para personas en riesgo de exclusión y aquellas que están saliendo de centros de rehabilitación o penitenciarios.</p>
        </div>
        <div id="proyectos" class="section">
            <h2>Proyectos</h2>
            <p>Galería de proyectos realizados a lo largo de los años.</p>
        </div>
        <div id="contacto" class="section">
            <h2>Contacto</h2>
            <p>Información de contacto y ubicaciones en Girona y Salt.</p>
        </div>
        <div id="galeria" class="section gallery">
            <h2>Galería</h2>
            <img src="https://via.placeholder.com/800x400" alt="Imagen de ejemplo">
        </div>
    </div>
    <footer>
        <p>© 2024 Mi Asociación. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

