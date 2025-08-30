<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ALL Clothing - Moda Eco-Friendly</title>

  <!-- Fuente moderna -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">

  <!-- Iconos -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

  <style>
    body { margin: 0; font-family: 'Poppins', sans-serif; background: #f8f8f8; color: #333; }
    header { background: linear-gradient(135deg, #000, #333); color: white; padding: 60px 20px; text-align: center; }
    header h1 { margin: 0; font-size: 3em; }
    header p { margin: 15px 0 0; font-size: 1.3em; }

    nav { background: #222; padding: 15px; text-align: center; position: sticky; top: 0; z-index: 100; }
    nav a { color: white; margin: 0 20px; text-decoration: none; font-weight: 600; transition: color 0.3s; }
    nav a:hover { color: #4CAF50; }

    section { padding: 60px 20px; max-width: 1100px; margin: auto; }
    section h2 { font-size: 2.2em; margin-bottom: 25px; text-align: center; }
    section p { font-size: 1.1em; line-height: 1.7; text-align: center; }

    .collection { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 25px; margin-top: 30px; }
    .item { background: white; border-radius: 15px; box-shadow: 0 6px 12px rgba(0,0,0,0.1); padding: 20px; text-align: center; transition: transform 0.3s ease, box-shadow 0.3s ease; }
    .item img { max-width: 100%; border-radius: 10px; }
    .item:hover { transform: translateY(-8px); box-shadow: 0 10px 20px rgba(0,0,0,0.15); }

    .btn { display: inline-block; margin-top: 15px; background: black; color: white; padding: 12px 25px; border-radius: 8px; text-decoration: none; font-weight: 600; transition: background 0.3s; }
    .btn:hover { background: #4CAF50; }

    .socials { margin-top: 20px; text-align: center; }
    .socials a { margin: 0 10px; font-size: 1.5em; color: #333; transition: color 0.3s; }
    .socials a:hover { color: #4CAF50; }

    footer { background: #111; color: white; text-align: center; padding: 25px; margin-top: 50px; }
    footer a { color: #4CAF50; text-decoration: none; }

    @media (max-width: 600px) {
      header h1 { font-size: 2em; }
      section { padding: 30px 15px; }
    }
  </style>
</head>
<body>
  <header>
    <h1>ALL Clothing</h1>
    <p>Moda sostenible y con estilo 🌱</p>
  </header>

  <nav>
    <a href="#about">Nosotros</a>
    <a href="#collection">Colección</a>
    <a href="#contact">Contacto</a>
  </nav>

  <section id="about">
    <h2>Nuestra filosofía</h2>
    <p>Creemos en la moda responsable. Todas nuestras prendas se producen con procesos de estampado 0% agua y empaques reciclados. Apostamos por la sostenibilidad sin sacrificar estilo.</p>
  </section>

  <section id="collection">
    <h2>Colección</h2>
    <div class="collection">
      <div class="item">
        <img src="https://via.placeholder.com/300x300.png?text=Camiseta+Eco" alt="Camiseta Eco">
        <h3>Camiseta Eco</h3>
        <p>100% algodón orgánico</p>
        <a href="#" class="btn">Próximamente</a>
      </div>
      <div class="item">
        <img src="https://via.placeholder.com/300x300.png?text=Sudadera+ALL" alt="Sudadera ALL">
        <h3>Sudadera ALL</h3>
        <p>Material reciclado</p>
        <a href="#" class="btn">Próximamente</a>
      </div>
      <div class="item">
        <img src="https://via.placeholder.com/300x300.png?text=Tote+Bag" alt="Tote Bag">
        <h3>Tote Bag</h3>
        <p>Bolsa reutilizable</p>
        <a href="#" class="btn">Próximamente</a>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contáctanos</h2>
    <p>Síguenos en nuestras redes sociales para conocer más:</p>
    <div class="socials">
      <a href="https://instagram.com/" target="_blank"><i class="fab fa-instagram"></i></a>
      <a href="https://tiktok.com/" target="_blank"><i class="fab fa-tiktok"></i></a>
      <a href="https://wa.me/573001112233" target="_blank"><i class="fab fa-whatsapp"></i></a>
    </div>
    <p><a href="mailto:contacto@allclothing.com" class="btn">Escríbenos</a></p>
  </section>

  <footer>
    <p>&copy; 2025 ALL Clothing | Diseñado con ❤ en Colombia</p>
  </footer>
</body>
</html>

