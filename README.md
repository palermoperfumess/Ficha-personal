
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Ficha — Gagik Margaryan</title>
  <style>
    :root{
      --bg:#f5f7fb; --card:#ffffff; --text:#0f172a; --muted:#6b7280; --accent:#2563eb;
    }
    .dark{
      --bg:#0b1220; --card:#0f172a; --text:#e6eef8; --muted:#9aa6bf; --accent:#60a5fa;
    }
    *{box-sizing:border-box}
    body{margin:0;font-family:system-ui,Arial;line-height:1.4;background:var(--bg);color:var(--text);padding:24px}
    .wrap{max-width:880px;margin:0 auto}
    .top{display:flex;gap:16px;align-items:center}
    .avatar{width:96px;height:96px;border-radius:10px;overflow:hidden;background:linear-gradient(135deg,#e6eefc,#fff);display:flex;align-items:center;justify-content:center;border:1px solid rgba(0,0,0,0.06)}
    .avatar img{width:100%;height:100%;object-fit:cover;display:block}
    h1{margin:0;font-size:1.25rem}
    .meta{font-size:0.95rem;color:var(--muted);margin-top:6px}
    .card{background:var(--card);padding:12px;border-radius:10px;margin-top:18px;border:1px solid rgba(0,0,0,0.04)}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(200px,1fr));gap:12px;margin-top:12px}
    .proj{padding:8px;border-radius:8px;background:linear-gradient(180deg,rgba(0,0,0,0.02),transparent)}
    .proj img{width:100%;height:110px;object-fit:cover;border-radius:6px;background:#eef2ff;display:block}
    .proj a{color:var(--accent);text-decoration:none;font-weight:600}
    .small{font-size:0.9rem;color:var(--muted)}
    /* dark toggle (checkbox hack) */
    .toggle{position:fixed;right:16px;top:16px}
    .toggle input{display:none}
    .toggle label{background:var(--card);color:var(--text);padding:8px 10px;border-radius:999px;border:1px solid rgba(0,0,0,0.06);cursor:pointer}
    /* apply dark when checkbox checked */
    #dark:checked ~ .site {background:var(--bg)}
    /* small responsive */
    @media (max-width:560px){.top{flex-direction:row;gap:12px}.avatar{width:80px;height:80px}}
  </style>
</head>
<body>
  <!-- checkbox to toggle dark mode (no JS) -->
  <div class="toggle">
    <input id="dark" type="checkbox">
    <label for="dark" onclick="document.documentElement.classList.toggle('dark')">Modo oscuro</label>
  </div>

  <div class="wrap site">
    <header class="top">
      <div class="avatar">
        <!-- replace avatar-placeholder.svg with your photo -->
        <img src="https://media.licdn.com/dms/image/v2/D4D03AQGwMc82RcgNDw/profile-displayphoto-scale_400_400/B4DZk130rLJUAk-/0/1757545452619?e=1764201600&v=beta&t=D1Hc0HtG-p-ZkT4GxesPd-nG8GR135Lp1gFLgb-sLcA" alt="Foto personal">
      </div>
      <div>
        <h1>Gagik Margaryan</h1>
        <div class="meta">Legajo: <strong>1221317</strong></div>
        <div class="meta">Materia: <strong>Diseño y desarrollo web</strong> — Curso: <strong>536117</strong></div>
      </div>
    </header>

    <section class="card">
      <div class="small">Ficha</div>
      <div style="margin-top:8px">
        <div><strong>Nombre:</strong> Gagik Margaryan</div>
        <div class="small" style="margin-top:6px"><strong>Legajo:</strong> 1221317</div>
        <div class="small" style="margin-top:6px"><strong>Materia:</strong> Diseño y desarrollo web</div>
        <div class="small" style="margin-top:6px"><strong>Curso:</strong> 536117</div>
      </div>
    </section>

    <section class="card">
      <div class="small">Proyectos </div>
      <div class="grid">
        <article class="proj">
          <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSfTJjg0PboAT3IasKUfSFPllpSvJFBzMYPNw&s" alt="Proyecto 1">
          <div style="margin-top:8px"><a href="https://palermoperfumess.github.io/Dexter/">Dexter</a></div>
        </article>
        <article class="proj">
          <img src="https://img2.storyblok.com/filters:grayscale()/f/63300/200x200/d75ca2f4ba/media-11031-palermo.jpg" alt="Proyecto 2"> 
          <div style="margin-top:8px"><a href="https://palermoperfumess.github.io/Palermoperfumes/index.html">Palermo Store</a></div>
        </article>
        <article class="proj">
          <img src="https://juanfragrasso.github.io/TrabajaIntegradorDise-oWeb/images/logo_nuevo.png" alt="Proyecto 3">
          <a href= "https://juanfragrasso.github.io/TrabajaIntegradorDise-oWeb/index.html">Pagina grupal</a>
          <div style="margin-top:8px">Trabajo practico grupal</div>
        </article>
      </div>
    </section>

    <footer style="margin-top:18px;color:var(--muted);font-size:0.95rem">
      &copy; 2025 Gagik Margaryan
    </footer>
  </div>
</body>
</html>
