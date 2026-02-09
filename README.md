# Emmanuel E. Montiel Z.
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Portafolio | Java Developer Jr.</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --bg:#0f172a;
      --card:#111827;
      --accent:#22c55e;
      --text:#e5e7eb;
      --muted:#9ca3af;
    }
    *{box-sizing:border-box;
      margin:0;
      padding:0;
      font-family:'Inter',sans-serif}
    body{background:linear-gradient(180deg,#020617, #0b1024);
         color:var(--text)}
    header{padding:60px 20px;
           text-align:center}
    h1{font-size:2.5rem;
       font-weight:700}
    h2{font-size:1.6rem;
       margin-bottom:15px}
    p{color:var(--muted);
      line-height:1.6}
    .container{max-width:1100px;
               margin:auto;
               padding:20px}
    .card{background:rgba(17,24,39,.7);
          backdrop-filter:blur(8px);
          border-radius:18px;
          padding:25px;
          margin-bottom:25px;
          box-shadow:0 10px 30px rgba(0,0,0,.3)}
    .links a{display:inline-block;
             margin:8px 10px;
             padding:10px 16px;
             border-radius:10px;
             text-decoration:none;
             color:white;
             background:#1f2937;
             transition:.2s}
    .links a:hover{background:var(--accent);
                   color:#022c22}
    .grid{display:grid;
          grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
          gap:20px}
    .project img{width:100%;
                 border-radius:10px;
                 margin-bottom:10px}
    footer{text-align:center;
           padding:30px;
           color:var(--muted)}
    input, textarea{width:100%;
                    padding:10px;
                    margin-top:8px;
                    border-radius:8px;
                    border:1px solid #374151;
                    background:#020617;
                    color:white}
    .btn{margin-top:10px;padding:10px 14px;border:none;border-radius:8px;background:var(--accent);cursor:pointer}
  </style>
</head>
<body>
  <header>
    <h1>Tu Nombre</h1>
    <p>Java Developer Jr. | Backend | Spring Boot</p>
  </header>

  <div class="container">
    <section class="card">
      <h2>Sobre mí</h2>
      <p id="bio">Escribe aquí tu biografía profesional. Puedes hablar de tu experiencia con Java, tus objetivos, lo que te apasiona del desarrollo de software y el tipo de proyectos en los que te gustaría participar.</p>
    </section>
    <section class="card">
      <h2>Enlaces Profesionales</h2>
      <div class="links">
        <a href="#" target="_blank">GitHub</a>
        <a href="#" target="_blank">LinkedIn</a>
        <a href="#" target="_blank">CV</a>
      </div>
    </section>
    <section class="card">
      <h2>Proyectos</h2>
      <div class="grid">
        <div class="project">
          <img src="https://via.placeholder.com/600x350" alt="Proyecto 1">
          <h3>Nombre del Proyecto</h3>
          <p>Descripción breve del proyecto, tecnologías utilizadas (Java, Spring, MySQL, etc.).</p>
          <div class="links">
            <a href="#" target="_blank">Repositorio</a>
            <a href="#" target="_blank">Demo</a>
          </div>
        </div>
        <div class="project">
          <img src="https://via.placeholder.com/600x350" alt="Proyecto 2">
          <h3>Nombre del Proyecto</h3>
          <p>Descripción breve del proyecto, funcionalidades principales y tu rol.</p>
          <div class="links">
            <a href="#" target="_blank">Repositorio</a>
            <a href="#" target="_blank">Demo</a>
          </div>
        </div>
      </div>
    </section>
    <section class="card">
      <h2>Capturas / Evidencias</h2>
      <div class="grid">
        <img src="https://via.placeholder.com/500x300" alt="Captura 1">
        <img src="https://via.placeholder.com/500x300" alt="Captura 2">
        <img src="https://via.placeholder.com/500x300" alt="Captura 3">
      </div>
    </section>
    <section class="card">
      <h2>Contacto</h2>
      <form>
        <label>Nombre</label>
        <input type="text" placeholder="Tu nombre">
        <label>Email</label>
        <input type="email" placeholder="tu@email.com">
        <label>Mensaje</label>
        <textarea rows="4" placeholder="Escribe tu mensaje"></textarea>
        <button class="btn" type="button">Enviar</button>
      </form>
    </section>

  </div>

  <footer>
    <p>© 2026 - Portafolio Profesional</p>
  </footer>
</body>
</html>
