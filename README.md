<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venta de Repuestos Automotrices</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #333;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #444;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
        }
        nav a:hover {
            background: #555;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }
        .product {
            background: white;
            padding: 15px;
            margin: 15px 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 45%;
        }
        .product img {
            max-width: 100%;
            border-radius: 5px;
        }
        .product h2 {
            margin: 0;
        }
        .product p {
            color: #555;
        }
        .buy-btn {
            display: inline-block;
            padding: 10px 20px;
            background: #28a745;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }
        .buy-btn:hover {
            background: #218838;
        }
        .testimonials {
            background: #fff;
            padding: 20px;
            margin: 20px auto;
            width: 80%;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .testimonials h2 {
            text-align: center;
        }
        .testimonial {
            margin: 10px 0;
            padding: 10px;
            border-left: 5px solid #28a745;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Venta de Repuestos Automotrices</h1>
    </header>
    <nav>
        <a href="#">Inicio</a>
        <a href="#">Productos</a>
        <a href="#">Contacto</a>
    </nav>
    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Filtro de aceite">
            <h2>Filtro de Aceite</h2>
            <p>Filtro de alta calidad para motores de gasolina y diésel.</p>
            <a href="#" class="buy-btn">Comprar</a>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/300" alt="Pastillas de freno">
            <h2>Pastillas de Freno</h2>
            <p>Pastillas de freno premium para mayor seguridad y rendimiento.</p>
            <a href="#" class="buy-btn">Comprar</a>
        </div>
    </div>
    <div class="testimonials">
        <h2>Testimonios de Clientes</h2>
        <div class="testimonial">
            <p><strong>Juan Pérez:</strong> "Excelente servicio y productos de calidad. Muy recomendados!"</p>
        </div>
        <div class="testimonial">
            <p><strong>María Gómez:</strong> "Los repuestos llegaron rápido y en perfecto estado. Volveré a comprar!"</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2025 Venta de Repuestos Automotrices. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
