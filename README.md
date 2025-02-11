
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="author" content="Lucía">
    <title>Mi Página en GitHub</title>

    <style>
        /* Reseteo de márgenes y padding */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            color: #fff;
            line-height: 1.6;
            min-height: 100vh;
        }

        header {
            text-align: center;
            padding: 50px 20px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 8px;
            margin: 40px auto;
            max-width: 900px;
        }

        header h1 {
            font-size: 3.5em;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #fff;
            margin-bottom: 20px;
        }

        header p {
            font-size: 1.2em;
            color: #ddd;
        }

        .content {
            max-width: 1000px;
            margin: 0 auto;
            padding: 30px;
            background: #ffffff;
            color: #333;
            border-radius: 10px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }

        .content h2 {
            font-size: 2.5em;
            color: #3498db;
            margin-bottom: 20px;
            text-transform: uppercase;
        }

        .content p {
            font-size: 1.1em;
            color: #555;
            line-height: 1.8;
            margin-bottom: 30px;
        }

        .btn {
            display: inline-block;
            padding: 12px 25px;
            background-color: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.2em;
            text-transform: uppercase;
            letter-spacing: 1px;
            transition: all 0.3s ease;
        }

        .btn:hover {
            background-color: #2980b9;
            transform: translateY(-5px);
        }

        footer {
            background-color: #34495e;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 40px;
            border-radius: 8px;
        }

        footer a {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Animaciones y efectos */
        .fadeIn {
            animation: fadeIn 2s ease-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Estilo del botón de contacto */
        .contact-btn {
            display: inline-block;
            padding: 12px 25px;
            background-color: #e74c3c;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.2em;
            text-transform: uppercase;
            margin-top: 20px;
            transition: all 0.3s ease;
        }

        .contact-btn:hover {
            background-color: #c0392b;
            transform: translateY(-5px);
        }
    </style>
</head>
<body>

    <header class="fadeIn">
        <h1>Bienvenido a mi Página en GitHub</h1>
        <p>Explora mis proyectos, descubre mis contribuciones y aprende más sobre mi trabajo.</p>
    </header>

    <div class="content fadeIn">
        <h2>Sobre Mí</h2>
        <p>
            ¡Hola! Soy <strong>Tu Nombre</strong>, un desarrollador web apasionado por la tecnología y el diseño. Trabajo con HTML, CSS, JavaScript, React, y otras tecnologías de desarrollo web. Mi misión es crear soluciones innovadoras que resuelvan problemas reales y que sean fáciles de usar.
        </p>

        <h2>Mis Proyectos</h2>
        <p>
            En mi perfil de GitHub podrás encontrar una variedad de proyectos que van desde aplicaciones web hasta herramientas útiles para desarrolladores. Si te interesa colaborar, no dudes en contactarme.
        </p>

        <a href="https://github.com/TuUsuario" class="btn" target="_blank">Visita mi GitHub</a>

        <br>
        <a href="mailto:luciahdkf@gmail.com" class="contact-btn">Contáctame por correo</a>
    </div>

    <footer>
        <p>Creado con 💻 por <strong>Lucía</strong></p>
        <p><a href="https://github.com/TuUsuario" target="_blank">Mi GitHub</a></p>
    </footer>

</body>
