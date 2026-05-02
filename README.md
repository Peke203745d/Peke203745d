## Hi there 👋

<!--
**Peke203745d/Peke203745d** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curso Git y GitHub</title>

    <!-- Buenas prácticas: SEO básico -->
    <meta name="description" content="Aprende Git y GitHub desde cero con buenas prácticas profesionales">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            line-height: 1.6;
        }

        header {
            background: #24292e;
            color: white;
            padding: 2rem;
            text-align: center;
        }

        nav {
            background: #0366d6;
            padding: 1rem;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 10px;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 2rem;
        }

        .hero {
            background: #f4f4f4;
            text-align: center;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            background: #0366d6;
            color: white;
            text-decoration: none;
            margin-top: 10px;
            border-radius: 5px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }

        footer {
            background: #24292e;
            color: white;
            text-align: center;
            padding: 1rem;
        }
    </style>
</head>

<body>

<header>
    <h1>Curso de Git y GitHub</h1>
    <p>Aprende control de versiones y trabajo colaborativo como un profesional</p>
</header>

<nav>
    <a href="#git">Git</a>
    <a href="#flujo">Flujo</a>
    <a href="#practicas">Buenas prácticas</a>
    <a href="#contacto">Contacto</a>
</nav>

<section class="hero">
    <h2>Domina Git desde cero</h2>
    <p>Aprende a gestionar versiones, colaborar en equipo y usar GitHub correctamente</p>
    <a href="#" class="btn">Empezar ahora</a>
</section>

<section id="git">
    <h2>¿Qué es Git?</h2>
    <p>
        Git es un sistema de control de versiones distribuido que permite guardar archivos
        y sus cambios a lo largo del tiempo de forma segura.
    </p>

    <div class="grid">
        <div>
            <h3>Control de versiones</h3>
            <p>Guarda el historial completo de tu proyecto.</p>
        </div>

        <div>
            <h3>Trabajo local</h3>
            <p>No necesitas conexión para trabajar.</p>
        </div>

        <div>
            <h3>Historial</h3>
            <p>Cada cambio queda registrado con un commit.</p>
        </div>
    </div>
</section>

<section id="flujo">
    <h2>Flujo de trabajo</h2>

    <ol>
        <li>Clonar repositorio (git clone)</li>
        <li>Crear rama (git checkout -b rama)</li>
        <li>Realizar cambios</li>
        <li>Agregar cambios (git add .)</li>
        <li>Crear commit (git commit)</li>
        <li>Subir cambios (git push)</li>
        <li>Crear Pull Request</li>
    </ol>

    <p>
        Nunca trabajes directamente en la rama principal. Usa ramas para mantener el orden.
    </p>
</section>

<section id="practicas">
    <h2>Buenas prácticas</h2>

    <div class="grid">

        <div>
            <h3>Commits atómicos</h3>
            <p>Haz cambios pequeños y significativos.</p>
        </div>

        <div>
            <h3>Mensajes claros</h3>
            <p>Usa verbos como: Add, Fix, Change, Remove.</p>
        </div>

        <div>
            <h3>Prefijos</h3>
            <p>feat, fix, docs, style, refactor, test.</p>
        </div>

        <div>
            <h3>Máximo 50 caracteres</h3>
            <p>Sé breve y directo en tus commits.</p>
        </div>

    </div>
</section>

<section>
    <h2>Trabajo en equipo</h2>

    <p>
        Los Pull Requests permiten revisar cambios antes de integrarlos al proyecto.
        Esto mejora la calidad del código y evita errores.
    </p>
</section>

<section id="contacto">
    <h2>Empieza hoy</h2>
    <p>Aprende Git y mejora tu perfil como desarrollador</p>
    <a href="#" class="btn">Unirme al curso</a>
</section>

<footer>
    <p>© 2026 Curso Git - SCESI</p>
</footer>

</body>
</html>
