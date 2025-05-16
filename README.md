<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    <title>Cooperando Con Amor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
            color: black;
        }
        header {
            background-color: #b2e2b2;
            padding: 1em;
            display: flex;
            align-items: center;
        }
        header img {
            height: 70px;
            margin-right: 15px;
        }
        header h1 {
            margin: 0;
            font-size: 1.8em;
        }
        header p {
            margin: 0;
            font-style: italic;
        }
        main {
            padding: 2em;
        }
        .descripcion {
            margin-bottom: 2em;
        }
        form {
            background-color: #e2f5e2;
            padding: 2em;
            border-radius: 8px;
            max-width: 500px;
            margin: auto;
        }
        label {
            display: block;
            margin-top: 1em;
            margin-bottom: 0.5em;
        }
        input, textarea {
            width: 100%;
            padding: 0.5em;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1em;
        }
        button {
            margin-top: 1.5em;
            background-color: #7ec97e;
            color: white;
            border: none;
            padding: 0.7em 1.5em;
            font-size: 1em;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #66b366;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.jpg" alt="Logo de Cooperando Con Amor">
        <div>
            <h1>Cooperando Con Amor</h1>
            <p>"Unidos por el amor, transformamos el mundo"</p>
        </div>
    </header>
    <main>
        <section class="descripcion">
            <p>Somos una organización dedicada a promover la solidaridad y cooperación para mejorar el bienestar de nuestra comunidad, generando un impacto positivo, justo e inclusivo.</p>
        </section>
        <section class="formulario">
            <p><strong>¿Tienes alguna pregunta o mensaje? Déjanos saber mediante este formulario y te responderemos por correo electrónico:</strong></p>
            <form action="https://formspree.io/f/xeognznp" method="POST">
                <label for="nombre">Nombre</label>
                <input type="text" id="nombre" name="nombre" required>

                <label for="email">Correo electrónico</label>
                <input type="email" id="email" name="email" required>

                <label for="mensaje">Pregunta o mensaje</label>
                <textarea id="mensaje" name="mensaje" rows="5" required></textarea>

                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>
</body>
</html>
