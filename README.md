<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venta de Repuestos Automotrices</title>
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
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .product {
            background: white;
            padding: 15px;
            margin: 15px 0;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
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
    </style>
</head>
<body>
    <header>
        <h1>Venta de Repuestos Automotrices</h1>
    </header>
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
</body>
</html>
