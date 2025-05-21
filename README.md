<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>TecnoRuta | Productos Electrónicos</title>
  <style>
    html {
      scroll-behavior: smooth;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f0f4f8;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #005599;
      padding: 0.5rem;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      padding: 2rem;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
    }
    .product {
      background: white;
      padding: 1rem;
      border-radius: 8px;
      width: 220px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .product img {
      width: 100%;
      height: 150px;
      object-fit: contain;
    }
    .product h3 {
      margin: 0.5rem 0;
    }
    .product p {
      color: #555;
      font-size: 0.9rem;
    }
    .btn {
      display: block;
      margin-top: 1rem;
      background: #0077cc;
      color: white;
      padding: 0.5rem;
      text-align: center;
      border: none;
      border-radius: 5px;
      text-decoration: none;
    }
    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>


    
  <header>
    <h1>TecnoRuta</h1>
    <p>Tu ruta directa a la mejor tecnología</p>
  </header>

  <nav>
    <a href="#">Inicio</a>
    <a href="productos.html">Productos</a>
    <a href="Contactos.html">Contacto</a>
  </nav>

  <div class="container" id="productos">
    <div class="product">
      <img src="" alt="Celular">
      <h3>Telefono para belen</h3>
      <p>Pantalla 6.5", 64GB, Cámara 48MP</p>
      <a href="#" class="btn">Ver más</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x150" alt="Auriculares">
      <h3>Auriculares Pro</h3>
      <p>Bluetooth, Micrófono, Cancelación de ruido</p>
      <a href="#" class="btn">Ver más</a>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x150" alt="Notebook">
      <h3>Video Juegos</h3>
      <p>Intel i5, 8GB RAM, SSD 256GB</p>
      <a href="#" class="btn">Ver más</a>
    </div>
    
  </div>

  <footer>
    © 2025 TecnoRuta - Todos los derechos reservados
  </footer>

</body>
</html>
