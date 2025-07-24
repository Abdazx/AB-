<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AB & | Productos Elegantes</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }
    body {
      font-family: 'Inter', sans-serif;
      background-color: #ffffff;
      color: #222;
      line-height: 1.6;
    }
    header {
      background-color: #000000;
      color: white;
      padding: 20px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 28px;
      letter-spacing: 2px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin-left: 30px;
      font-weight: 600;
    }
    .hero {
      background-image: url('https://source.unsplash.com/1600x700/?elegant,store');
      background-size: cover;
      background-position: center;
      height: 500px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
    }
    .hero h2 {
      font-size: 48px;
      background-color: rgba(0, 0, 0, 0.5);
      padding: 20px 40px;
      border-radius: 8px;
    }
    .productos {
      padding: 60px 40px;
    }
    .productos h3 {
      font-size: 28px;
      margin-bottom: 20px;
      font-family: 'Playfair Display', serif;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }
    .producto {
      border: 1px solid #eee;
      padding: 20px;
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .producto:hover {
      transform: scale(1.03);
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    }
    .producto img {
      max-width: 100%;
      border-radius: 6px;
    }
    .producto h4 {
      margin: 15px 0 10px;
      font-size: 18px;
    }
    .producto a {
      display: inline-block;
      margin-top: 10px;
      text-decoration: none;
      background-color: #000;
      color: #fff;
      padding: 10px 20px;
      border-radius: 5px;
      font-weight: 500;
    }
    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 30px 20px;
      margin-top: 60px;
    }
  </style>
</head>
<body>
  <header>
    <h1>AB &</h1>
    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#productos">Catálogo</a>
      <a href="#nosotros">Nosotros</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>  <section class="hero" id="inicio">
    <h2>Productos elegantes para gente con estilo</h2>
  </section>  <section class="productos" id="productos">
    <h3>Catálogo destacado</h3>
    <div class="grid">
      <div class="producto">
        <img src="https://source.unsplash.com/400x300/?tech,gadget" alt="Producto 1">
        <h4>Auriculares inalámbricos</h4>
        <a href="#">Ver en Amazon</a>
      </div>
      <div class="producto">
        <img src="https://source.unsplash.com/400x300/?kitchen,tools" alt="Producto 2">
        <h4>Set de cocina elegante</h4>
        <a href="#">Ver en Amazon</a>
      </div>
      <div class="producto">
        <img src="https://source.unsplash.com/400x300/?fashion,watch" alt="Producto 3">
        <h4>Reloj de lujo</h4>
        <a href="#">Ver en Amazon</a>
      </div>
    </div>
  </section>  <footer>
    <p>&copy; 2025 AB & – Todos los derechos reservados.</p>
  </footer>
</body>
</html>
