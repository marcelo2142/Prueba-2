# Prueba-2
Hello
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Página Web Moderna</title>
  <style>
    /* 🔹 Estilos globales */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f9fafb;
      color: #333;
      line-height: 1.6;
    }

    /* 🔹 Encabezado */
    header {
      background: linear-gradient(135deg, #4CAF50, #2e7d32);
      color: white;
      text-align: center;
      padding: 40px 20px;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }

    /* 🔹 Navegación */
    nav {
      background: #222;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      padding: 10px;
    }

    nav a {
      color: white;
      margin: 8px 15px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #4CAF50;
    }

    /* 🔹 Contenido principal */
    section {
      max-width: 1100px;
      margin: auto;
      padding: 30px 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h2 {
      margin-bottom: 10px;
      color: #4CAF50;
    }

    /* 🔹 Footer */
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }

    footer p {
      font-size: 0.9rem;
    }

    /* 🔹 Responsivo */
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
      header p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>

  <!-- Encabezado -->
  <header>
    <h1>🌐 Mi Página Web Moderna</h1>
    <p>Diseñada con HTML, CSS, Flexbox y Grid</p>
  </header>

  <!-- Menú de navegación -->
  <nav>
    <a href="#">Inicio</a>
    <a href="#">Sobre mí</a>
    <a href="#">Proyectos</a>
    <a href="#">Contacto</a>
  </nav>

  <!-- Contenido principal -->
  <section>
    <div class="card">
      <h2>Sobre mí</h2>
      <p>Hola, soy [Tu Nombre]. Me apasiona el desarrollo web y estoy creando mi primera página responsiva.</p>
    </div>

    <div class="card">
      <h2>Mis Proyectos</h2>
      <ul>
        <li>Portafolio personal</li>
        <li>Blog con artículos</li>
        <li>Tienda online</li>
      </ul>
    </div>

    <div class="card">
      <h2>Contacto</h2>
      <p>Puedes escribirme a:</p>
      <p><strong>📧 correo@ejemplo.com</strong></p>
    </div>
  </section>

  <!-- Pie de página -->
  <footer>
    <p>© 2025 Mi Página Web - Todos los derechos reservados</p>
  </footer>

</body>
</html>
