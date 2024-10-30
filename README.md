<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #333;
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
        .section {
            padding: 2rem;
            max-width: 900px;
            margin: auto;
        }
        .projects {
            display: grid;
            gap: 1rem;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
        }
        .project {
            background-color: #fff;
            border: 1px solid #ddd;
            padding: 1rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.3s;
        }
        .project:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <header>
        <h1>Hola, soy [Tu Nombre]</h1>
        <p>Desarrollador Web | Ingeniero Electrónico | Apasionado de la Tecnología</p>
    </header>
    <section class="section">
        <h2>Sobre mí</h2>
        <p>Aquí puedes hablar sobre tu experiencia, formación y habilidades.</p>
    </section>
    <section class="section projects">
        <h2>Proyectos</h2>
        <div class="project">
            <h3>Proyecto 1</h3>
            <p>Descripción breve del proyecto.</p>
        </div>
        <div class="project">
            <h3>Proyecto 2</h3>
            <p>Descripción breve del proyecto.</p>
        </div>
    </section>
</body>
</html>



