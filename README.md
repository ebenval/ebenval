<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Perfil profesional de Evaristo Benitez - Desarrollador Web Junior" />
  <title>Evaristo Benitez | Desarrollador Web</title>

  <style>
    :root {
      --bg-color: #f8f9fa;
      --text-color: #333;
      --accent-color: #0078ff;
      --card-bg: #fff;
      --shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      --radius: 12px;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }

    body {
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
      padding: 2rem;
    }

    header {
      text-align: center;
      padding: 2rem 0;
    }

    .avatar {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      box-shadow: var(--shadow);
      margin-bottom: 1rem;
    }

    h1 {
      font-size: 2rem;
      margin-bottom: 0.5rem;
    }

    h2 {
      font-size: 1rem;
      color: #666;
    }

    section {
      background: var(--card-bg);
      border-radius: var(--radius);
      padding: 1.5rem;
      margin: 1.5rem 0;
      box-shadow: var(--shadow);
      animation: fadeInUp 0.6s ease forwards;
      opacity: 0;
      transform: translateY(20px);
    }

    h3 {
      color: var(--accent-color);
      margin-bottom: 1rem;
    }

    .badges {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
    }

    .badges span {
      background: var(--accent-color);
      color: #fff;
      padding: 0.4rem 0.8rem;
      border-radius: 20px;
      font-size: 0.9rem;
      box-shadow: var(--shadow);
    }

    .btn {
      display: inline-block;
      background: var(--accent-color);
      color: #fff;
      padding: 0.6rem 1rem;
      border-radius: var(--radius);
      text-decoration: none;
      transition: background 0.3s;
      margin-top: 1rem;
    }

    .btn:hover {
      background: #005edc;
    }

    ul {
      list-style-type: none;
      padding-left: 0;
    }

    ul li {
      margin-bottom: 0.5rem;
      padding-left: 1rem;
      position: relative;
    }

    ul li::before {
      content: "•";
      color: var(--accent-color);
      position: absolute;
      left: 0;
    }

    footer {
      text-align: center;
      margin-top: 2rem;
      color: #555;
    }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @media (max-width: 768px) {
      body {
        padding: 1rem;
      }

      h1 {
        font-size: 1.6rem;
      }

      section {
        padding: 1rem;
      }

      .avatar {
        width: 100px;
        height: 100px;
      }
    }
  </style>
</head>

<body>
  <header>
    <img src="https://avatars.githubusercontent.com/ebenval" alt="Foto de Evaristo Benitez" class="avatar">
    <h1>Evaristo Benitez</h1>
    <h2>💻 Desarrollador Web Junior | Python | Java | HTML | JavaScript | SQL</h2>
  </header>

  <main>
    <section>
      <h3>👋 Sobre mí</h3>
      <p>
        Soy un <strong>desarrollador web junior</strong> con formación en <strong>Python, SQL y desarrollo backend</strong>.
        Me apasiona la automatización, el diseño de bases de datos y la creación de aplicaciones web funcionales con un toque profesional.
      </p>
    </section>

    <section>
      <h3>🛠️ Habilidades</h3>
      <div class="badges">
        <span>Python</span>
        <span>Java</span>
        <span>HTML</span>
        <span>JavaScript</span>
        <span>SQL</span>
        <span>Git</span>
      </div>
    </section>

    <section>
      <h3>🚀 Proyecto Destacado</h3>
      <div>
        <h4>🧳 AgenciaViajes</h4>
        <p>
          Un proyecto en <strong>Python</strong> con <strong>SQLAlchemy</strong> y <strong>SQLite</strong> que simula una agencia de viajes.
          Permite gestionar destinos, clientes y reservas mediante un sistema de base de datos estructurado en tres archivos principales:
        </p>
        <ul>
          <li><code>main.py</code> — Control de la aplicación.</li>
          <li><code>models.py</code> — Clases y relaciones ORM.</li>
          <li><code>db.py</code> — Conexión y creación de la base de datos.</li>
        </ul>
        <a href="#" class="btn">Ver Proyecto</a>
      </div>
    </section>

    <section>
      <h3>🧠 Aprendiendo Actualmente</h3>
      <ul>
        <li>Python avanzado y frameworks backend (Flask / FastAPI).</li>
        <li>Optimización y manejo de bases de datos relacionales.</li>
        <li>Desarrollo web moderno con HTML, CSS y JavaScript.</li>
      </ul>
    </section>

    <section>
      <h3>🗓️ Próximos Proyectos</h3>
      <ul>
        <li>Aplicación de gestión de biblioteca.</li>
        <li>Juego de trivia interactivo en Python.</li>
        <li>Página de portafolio personal (próximamente).</li>
      </ul>
    </section>

    <section>
      <h3>📫 Conecta conmigo</h3>
      <div>
        <a href="https://www.linkedin.com/in/evaristo-benitez" target="_blank" class="btn">LinkedIn</a>
      </div>
    </section>
  </main>

  <footer>
    <p>💬 "El aprendizaje constante es la base del progreso."</p>
    <p>© 2025 Evaristo Benitez</p>
  </footer>

  <script>
    // Animación de aparición suave al cargar
    document.querySelectorAll('section').forEach((sec, i) => {
      setTimeout(() => sec.style.opacity = 1, i * 200);
    });
  </script>
</body>
</html>
