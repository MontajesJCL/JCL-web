<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Montajes Industriales JCL</title>
  <link rel="icon" href="/mnt/data/JCL.png" type="image/png">
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #333;
      background-color: #f8f9fa;
      scroll-behavior: smooth;
    }
    header {
      background-color: #0033A0;
      color: white;
      padding: 10px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    .logo {
      display: flex;
      align-items: center;
    }
    .logo img {
      max-height: 60px;
      margin-right: 10px;
    }
    .logo h1 {
      font-size: 20px;
      margin: 0;
      color: white;
    }
    nav {
      background-color: #002070;
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 10px 20px;
    }
    nav ul {
      list-style: none;
      display: flex;
      margin: 0;
      padding: 0;
    }
    nav ul li {
      margin: 0 15px;
    }
    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav ul li a:hover {
      text-decoration: underline;
    }
    .lang-select select {
      padding: 5px 10px;
      font-weight: bold;
      border-radius: 5px;
      border: none;
      cursor: pointer;
      background-color: #FFCC00;
      color: #0033A0;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
      text-align: justify;
      animation: fadeIn 1.5s ease;
    }
    h2 {
      color: #0033A0;
      margin-top: 0;
    }
    footer {
      background-color: #0033A0;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .to-top {
      position: fixed;
      bottom: 90px;
      right: 20px;
      background-color: #0033A0;
      color: white;
      border: none;
      border-radius: 50%;
      width: 50px;
      height: 50px;
      font-size: 24px;
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
      z-index: 999;
    }
    .to-top:hover {
      background-color: #002070;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
      font-size: 30px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
      z-index: 1000;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
    .fade-in-scroll {
    opacity: 0;
    transform: translateY(20px);
    transition: opacity 0.6s ease-out, transform 0.6s ease-out;
  }

  .fade-in-scroll.visible {
    opacity: 1;
    transform: none;
  }
</style>
</head>
<body>

<header>
  <div class="logo">
    <img src="/mnt/data/JCL.png" alt="Logo JCL">
    <h1>Montajes Industriales JCL</h1>
  </div>
</header>

<nav>
  <ul>
    <li><a href="index.html">Inicio</a></li>
    <li><a href="quienes-somos.html">Quiénes somos</a></li>
    <li><a href="servicios.html">Servicios</a></li>
    <li><a href="ubicacion.html">Ubicación</a></li>
    <li><a href="contacto.html">Contacto</a></li>
  </ul>
  <div class="lang-select">
    <select onchange="location = this.value">
      <option value="#">🇪🇸 Español</option>
      <option value="#">🇬🇧 English</option>
    </select>
  </div>
</nav>

<section>
  <h2>Bienvenida</h2>
  <p>Bienvenidos a Montajes Industriales JCL. Nuestra experiencia y compromiso en soluciones industriales nos permite colaborar con los principales fabricantes del sector automoción y ofrecer resultados a medida en cada proyecto.</p>
  <div style="margin-top: 30px; display: flex; flex-wrap: wrap; justify-content: space-around; gap: 20px;">
    <div style="flex: 1 1 100%; text-align: center;">
      <img src="https://images.unsplash.com/photo-1581091870621-1f17a94df1d2?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=60" alt="Montaje industrial JCL" style="max-width: 100%; border-radius: 8px;">
    </div>
    <div class="fade-in-scroll" style="flex: 1; min-width: 250px; background: #fff; border: 1px solid #ddd; padding: 20px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
      <h3 style="color: #0033A0;">¿Qué hacemos?</h3>
      <p>Diseñamos, fabricamos y montamos estructuras metálicas, además de encargarnos del mantenimiento y reparación de instalaciones industriales.</p>
    </div>
    <div style="flex: 1; min-width: 250px; background: #fff; border: 1px solid #ddd; padding: 20px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
      <h3 style="color: #0033A0;">Experiencia en automoción</h3>
      <p>Colaboramos con los principales fabricantes del sector, aportando soluciones técnicas eficientes y adaptadas a entornos de alta exigencia.</p>
    </div>
    <div style="flex: 1; min-width: 250px; background: #fff; border: 1px solid #ddd; padding: 20px; border-radius: 8px; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
      <h3 style="color: #0033A0;">Compromiso y calidad</h3>
      <p>Nuestro equipo técnico garantiza resultados fiables y personalizados, cuidando cada detalle en la ejecución de los proyectos.</p>
    </div>
  <div style="text-align: center; margin-top: 40px;">
    <a href="quienes-somos.html" style="background-color: #FFCC00; color: #0033A0; padding: 12px 20px; text-decoration: none; font-weight: bold; border-radius: 5px;">Conócenos más</a>
  </div>
$1

<footer>
  <p>&copy; 2025 Montajes Industriales JCL. Todos los derechos reservados.</p>
</footer>

<a href="#top" class="to-top" title="Volver arriba">↑</a>
<a class="whatsapp" href="https://wa.me/34670678619" target="_blank" title="Escríbenos por WhatsApp">💬</a>

<script>
  const faders = document.querySelectorAll('.fade-in-scroll');
  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.1 });

  faders.forEach(fader => observer.observe(fader));
</script>
</body>
</html>
