<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ALL - Catálogo de Ropa</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: #f5f5f5;
      color: #222;
    }
    header {
      background: url('https://source.unsplash.com/1600x600/?fashion,clothes') no-repeat center/cover;
      color: white;
      text-align: center;
      padding: 80px 20px;
    }
    header h1 {
      font-size: 3rem;
      margin: 0;
      background: rgba(0,0,0,0.5);
      display: inline-block;
      padding: 10px 20px;
      border-radius: 12px;
    }
    section {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    h2 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 2rem;
      color: #111;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: transform 0.2s ease;
    }
    .card:hover {
      transform: translateY(-5px);
    }
    .card img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }
    .card-content {
      padding: 20px;
    }
    .card-content h3 {
      margin: 0 0 10px;
      font-size: 1.3rem;
      color: #333;
    }
    .price {
      color: #27ae60;
      font-weight: 600;
      margin: 5px 0 15px;
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
  </style>
</head>
<body>
  <header>
    <h1>ALL - Catálogo</h1>
  </header>

  <section>
    <h2>Camisetas Básicas</h2>
    <div class="grid">
      <!-- Burda Brasil -->
      <div class="card">
        <img src="https://source.unsplash.com/400x400/?tshirt,black" alt="Camiseta Burda Brasil">
        <div class="card-content">
          <h3>Camiseta Básica - Burda Brasil</h3>
          <p class="price">$50.000 COP</p>
          <p class="details">
            Material: 50% algodón recuperado + 50% PET reciclado<br>
            Peso: 230 g/m² (más pesada)<br>
            Tallas: XS (44x63x20), S (47x65x21), M (50x67x22), L (54x70x23), XL (57x71x24)
          </p>
        </div>
      </div>
      <!-- Necoclí -->
      <div class="card">
        <img src="https://source.unsplash.com/400x400/?tshirt,grey" alt="Camiseta Necoclí">
        <div class="card-content">
          <h3>Camiseta Básica - Necoclí</h3>
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

  <section>
    <h2>Camisetas con Diseño</h2>
    <div class="grid">
      <div class="card">
        <img src="https://source.unsplash.com/400x400/?streetwear,design" alt="Camiseta Solus">
        <div class="card-content">
          <h3>Camiseta "Solus"</h3>
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

  <footer>
    <p>© 2025 ALL - Moda Sostenible</p>
  </footer>
</body>
</html>