<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Centro de Ayuda - Estafas y Robos</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      color: #333;
      line-height: 1.6;
      scroll-behavior: smooth;
    }
    header {
      background-color: #006699;
      color: #fff;
      padding: 1.5rem;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1rem;
      background-color: #004466;
      padding: 0.5rem;
    }
    nav a {
      color: #fff;
      text-decoration: none;
    }
    section {
      padding: 2rem;
    }
    .contactos, .formulario {
      background: #fff;
      padding: 1.5rem;
      border-radius: 8px;
      margin-bottom: 2rem;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      animation: fadeInUp 1s ease;
    }
    .icono {
      margin-right: 0.5rem;
      color: #006699;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: none;
      border-radius: 8px;
      margin-top: 1rem;
    }
    form label {
      display: block;
      margin-top: 1rem;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.5rem;
      margin-top: 0.3rem;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      margin-top: 1rem;
      background-color: #006699;
      color: #fff;
      border: none;
      padding: 0.7rem 1.5rem;
      border-radius: 5px;
      cursor: pointer;
    }
    @keyframes fadeInUp {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <header>
    <h1>Centro de Ayuda contra Estafas y Robos</h1>
    <p>Tu seguridad es nuestra prioridad</p>
  </header>

  <nav>
    <a href="#contacto">Contactos</a>
    <a href="#formulario">Formulario</a>
    <a href="#ubicacion">Ubicación</a>
  </nav>

  <section id="contacto" class="contactos">
    <h2><i class="fas fa-phone icono"></i>Teléfonos de ayuda</h2>
    <ul>
      <li><i class="fas fa-phone icono"></i>Policía: 911</li>
      <li><i class="fas fa-user-shield icono"></i>Denuncia Anónima: 089</li>
      <li><i class="fas fa-building icono"></i>Fiscalía: 800-702-8770</li>
    </ul>
  </section>

  <section id="formulario" class="formulario">
    <h2><i class="fas fa-envelope icono"></i>Formulario de contacto</h2>
    <form>
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" required>

      <label for="correo">Correo electrónico:</label>
      <input type="email" id="correo" name="correo" required>

      <label for="mensaje">Mensaje:</label>
      <textarea id="mensaje" name="mensaje" rows="4" required></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>

  <section id="ubicacion" class="contactos">
    <h2><i class="fas fa-map-marker-alt icono"></i>Ubicación</h2>
    <p>Consulta la oficina más cercana a ti:</p>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3763.1712159721745!2d-99.13320838511324!3d19.43260798688316!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85d1f92ce410b54f%3A0xfdf74d5f9977e530!2sCDMX!5e0!3m2!1ses!2smx!4v1692222222222!5m2!1ses!2smx" allowfullscreen=""></iframe>
  </section>
</body>
</html>
