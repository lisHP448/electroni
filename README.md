<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Fondo animado */
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            overflow-x: hidden;
            background: linear-gradient(45deg, #ff9a9e, #fad0c4, #fad0c4);
            background-size: 300% 300%;
            animation: gradientBackground 10s ease infinite;
        }
        @keyframes gradientBackground {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        /* Encabezado */
        header {
            background-color: rgba(0, 0, 0, 0.7);
            color: #fff;
            padding: 2rem;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        header p {
            font-size: 1.2rem;
        }

        /* Secciones */
        .section {
            padding: 2rem;
            max-width: 900px;
            margin: auto;
            color: #333;
            text-align: center;
        }

        /* Tarjetas de proyectos */
        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
            justify-content: center;
        }
        .project {
            background-color: #fff;
            border-radius: 8px;
            padding: 1.5rem;
            width: 300px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        .project:hover {
            transform: translateY(-10px);
            box-shadow: 0 8px 16px rgba(0,0,0,0.3);
        }
        .project h3 {
            margin-top: 0;
            font-size: 1.4rem;
            color: #333;
        }
        .project p {
            color: #666;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hola y Bienvenidos</h1>
        <p>Desarrollador Web | Ingeniero Electrónico | Apasionado de la Tecnología</p>
    </header>
    <section class="section">
        <h2>Proyectos</h2>
        <div class="projects">
            <div class="project">
                <h3>Calculadora Web</h3>
                <p>Una calculadora Web interactiva construida con html, css y javaScript, permite realizar operaciones basicas y tiene un diseño atractivo.</p>
                href="https://github.com/tu-usuario/proyecto1" target="_blank" style="color: #007bff; text-decoration: none;">Ver Proyecto en GitHub</a>
            </div>
            <div class="project">
                <h3>Pagina de Portafolio</h3>
                <p>Un portafolio personal hecho con html, css y bootstrap para mostrar nuestras habilidades y proyectos, Incluye una seccion de contacto.</p>
              href="https://tu-usuario.github.io/proyecto2" target="_blank" style="color: #007bff; text-decoration: none;">Ver Proyecto en Vivo</a>
            </div>
            <div class="project">
                <h3>Aplicación de Notas</h3>
                <p>Aplicación de notas sencilla con almacenamiento local. Permite agregar, editar y eliminar notas. Desarrollada con JavaScript y CSS.</p>
                href="https://github.com/tu-usuario/proyecto3" target="_blank" style="color: #007bff; text-decoration: none;">Ver Código en GitHub</a>
            </div>
        </div>
    </section>
</body>
</html>


