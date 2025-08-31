<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ALL - Moda Sostenible</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #f5f5f5;
      color: #222;
    }
    header {
      background: url('https://source.unsplash.com/1600x700/?fashion,eco') no-repeat center/cover;
      color: white;
      text-align: center;
      padding: 120px 20px;
      position: relative;
    }
    header::after {
      content: "";
      position: absolute;
      top:0; left:0; right:0; bottom:0;
      background: rgba(0,0,0,0.5);
    }
    header h1 {
      position: relative;
      font-size: 3.2rem;
      margin: 0;
      z-index: 1;
    }
    header p {
      position: relative;
      z-index: 1;
      font-size: 1.2rem;
      margin-top: 10px;
    }
    nav {
      background: #111;
      padding: 10px 20px;
      text-align: center;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 600;
    }
    nav a:hover {
      color: #27ae60;
    }
    section {
      padding: 60px 20px;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 30px;
      font-size: 2.2rem;
      color: #111;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }
    .card {
      background: white;
      border-radius: 16px;
      box-shadow: 0 6px 16px rgba(0,0,0,0.12);
      overflow: hidden;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 10px 22px rgba(0,0,0,0.2);
    }
    .card img {
      width: 100%;
      height: 280px;
      object-fit: cover;
    }
    .card-content {
      padding: 20px;
    }
    .card-content h3 {
      margin: 0 0 12px;
      font-size: 1.3rem;
      color: #333;
    }
    .price {
      color: #27ae60;
      font-weight: 600;
      margin: 8px 0 15px;
    }
    .details {
      font-size: 0.9rem;
      color: #555;
      line-height: 1.4;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #111;
      color: #fff;
      margin-top: 40px;
    }
    .social-icons a {
      margin: 0 10px;
      color: white;
      text-decoration: none;
      font-size: 1.4rem;
    }
    .social-icons a:hover {
      color: #27ae60;
    }
  </style>
</head>
<body>
  <nav>
    <a href="#basicas">Básicas</a>
    <a href="#diseno">Diseño</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <header>
    <h1>ALL - Moda Sostenible</h1>
    <p>Ropa ecológica hecha en Colombia 🌱</p>
  </header>

  <!-- Catálogo Camisetas Básicas -->
  <section id="basicas">
    <h2>Camisetas Básicas</h2>
    <div class="grid">
      <div class="card">
        <img src="https://source.unsplash.com/400x400/?tshirt,black" alt="Camiseta Burda Brasil">
        <div class="card-content">
          <h3>Básica - Burda Brasil</h3>
          <p class="price">$50.000 COP</p>
          <p class="details">
            Material: 50% algodón recuperado + 50% PET reciclado<br>
            Peso: 230 g/m² (más pesada)<br>
            Tallas: XS (44x63x20), S (47x65x21), M (50x67x22), L (54x70x23), XL (57x71x24)
          </p>
        </div>
      </div>
      <div class="card">
        <img src="https://source.unsplash.com/400x400/?tshirt,grey" alt="Camiseta Necoclí">
        <div class="card-content">
          <h3>Básica - Necoclí</h3>
          <p class="price">$50.000 COP</p>
          <p class="details">
            Material: 50% algodón recuperado + 50% PET reciclado<br>
            Peso: 160 g/m² (más ligera)<br>
            Tallas: XS (44x63x20), S (47x65x21), M (50x67x22), L (54x70x23), XL (57x71x24)
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Catálogo Camisetas con Diseño -->
  <section id="diseno">
    <h2>Camisetas con Diseño</h2>
    <div class="grid">
      <div class="card">
        <img src="https://source.unsplash.com/400x400/?streetwear,design" alt="Camiseta Solus">
        <div class="card-content">
          <h3>"Solus"</h3>
          <p class="price">$60.000 COP</p>
          <p class="details">
            Estilo único con impresión ecológica.<br>
            Material: Burda Brasil (230 g/m²).<br>
            Tallas: XS a XL.<br>
            Diseño minimalista y sostenible.
          </p>
        </div>
      </div>
      <!-- Aquí puedes añadir más diseños -->
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto">
    <h2>Contacto</h2>
    <p style="text-align:center">Escríbenos para pedidos o más información.</p>
    <div class="social-icons" style="text-align:center; margin-top:15px;">
      <a href="https://instagram.com" target="_blank">📸</a>
      <a href="https://tiktok.com" target="_blank">🎵</a>
      <a href="https://wa.me/573001112233" target="_blank">💬</a>
    </div>
  </section>

  <footer>
    <p>© 2025 ALL - Moda Sostenible</p>
  </footer>
</body>
</html>