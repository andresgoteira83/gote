<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Andrés Goteira | Portfolio</title>
  <style>
    :root{
      --bg:#0d1117;
      --card:#161b22;
      --text:#e6edf3;
      --muted:#9da7b3;
      --accent:#58a6ff;
      --border:#30363d;
    }

    *{box-sizing:border-box;margin:0;padding:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,sans-serif;}

    body{
      background:var(--bg);
      color:var(--text);
      line-height:1.6;
    }

    header{
      padding:2rem;
      border-bottom:1px solid var(--border);
      display:flex;
      justify-content:space-between;
      align-items:center;
    }

    header h1{
      font-size:1.2rem;
      font-weight:600;
    }

    nav a{
      color:var(--muted);
      margin-left:1rem;
      text-decoration:none;
      font-size:0.9rem;
    }

    nav a:hover{color:var(--accent);}

    .hero{
      padding:4rem 2rem;
      max-width:900px;
      margin:auto;
    }

    .hero h2{
      font-size:2.2rem;
      margin-bottom:1rem;
    }

    .hero p{
      color:var(--muted);
      max-width:600px;
    }

    .btn{
      display:inline-block;
      margin-top:1.5rem;
      padding:0.6rem 1rem;
      border:1px solid var(--border);
      border-radius:6px;
      color:var(--text);
      text-decoration:none;
    }

    .btn:hover{
      border-color:var(--accent);
      color:var(--accent);
    }

    .section{
      max-width:900px;
      margin:3rem auto;
      padding:0 2rem;
    }

    .section h3{
      margin-bottom:1rem;
      border-left:3px solid var(--accent);
      padding-left:0.5rem;
    }

    .grid{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:1rem;
    }

    .card{
      background:var(--card);
      border:1px solid var(--border);
      border-radius:8px;
      padding:1rem;
    }

    .card h4{
      margin-bottom:0.5rem;
    }

    .card p{
      color:var(--muted);
      font-size:0.9rem;
    }

    footer{
      text-align:center;
      padding:2rem;
      border-top:1px solid var(--border);
      color:var(--muted);
      font-size:0.85rem;
    }

  </style>
</head>
<body>

  <header>
    <h1>Andrés Goteira</h1>
    <nav>
      <a href="#about">Sobre mí</a>
      <a href="#projects">Proyectos</a>
      <a href="#contact">Contacto</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Desarrollador & creador digital</h2>
    <p>
      Construyo experiencias web simples, limpias y enfocadas en el contenido.
      Especializado en diseño minimalista y desarrollo frontend.
    </p>
    <a class="btn" href="#projects">Ver proyectos</a>
  </section>

  <section id="about" class="section">
    <h3>Sobre mí</h3>
    <p class="card">
      Soy un desarrollador enfocado en crear interfaces modernas inspiradas en
      la estética de GitHub y el diseño minimalista. Me interesa la tecnología,
      el cine y los proyectos creativos digitales.
    </p>
  </section>

  <section id="projects" class="section">
    <h3>Proyectos</h3>
    <div class="grid">
      <div class="card">
        <h4>Proyecto 1</h4>
        <p>Web experimental con enfoque minimalista y tipografía fuerte.</p>
      </div>
      <div class="card">
        <h4>Proyecto 2</h4>
        <p>Portfolio interactivo con animaciones suaves y UI oscura.</p>
      </div>
      <div class="card">
        <h4>Proyecto 3</h4>
        <p>Landing page optimizada para artistas y creadores.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <h3>Contacto</h3>
    <div class="card">
      <p>Email: andres@example.com</p>
      <p>GitHub: github.com/andresgoteira</p>
      <p>Ubicación: Galicia, España</p>
    </div>
  </section>

  <footer>
    © 2026 Andrés Goteira - Diseño inspirado en estética GitHub
  </footer>

</body>
</html>
