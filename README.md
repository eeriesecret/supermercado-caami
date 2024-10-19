<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Supermercado Caami</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background: #007BFF;
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            margin: 15px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: white;
            font-weight: bold;
        }
        .linea-separadora {
            height: 2px;
            background-color: white;
            margin: 10px 0;
        }
        .contacto, .informacion {
            margin: 20px;
            padding: 20px;
            background: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .productos {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }
        .producto {
            background: white;
            border: 1px solid #ddd;
            border-radius: 5px;
            margin: 10px;
            padding: 15px;
            width: 220px;
            text-align: center;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }
        .producto:hover {
            transform: scale(1.05);
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background: #007BFF;
            color: white;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .contacto input, .contacto textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .contacto button {
            background: #007BFF;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .contacto button:hover {
            background: #0056b3;
        }
    </style>
</head>
<body>

<header>
    <h1>Supermercado Caami</h1>
    <nav>
        <a href="#productos">Productos</a>
        <a href="#contacto">Contacto</a>
        <a href="#informacion">Información</a>
    </nav>
    <div class="linea-separadora"></div>
</header>

<main>
    <h2 id="productos">Productos Disponibles</h2>
    <div class="productos">
        <div class="producto">
            <h3>Leche (1 litro)</h3>
            <p>Precio: $1,200 CLP</p>
        </div>
        <div class="producto">
            <h3>Pan de molde (500g)</h3>
            <p>Precio: $1,600 CLP</p>
        </div>
        <div class="producto">
            <h3>Huevos (12 unidades)</h3>
            <p>Precio: $3,500 CLP</p>
        </div>
        <div class="producto">
            <h3>Carne molida (500g)</h3>
            <p>Precio: $5,200 CLP</p>
        </div>
        <div class="producto">
            <h3>Arroz (1 kg)</h3>
            <p>Precio: $1,300 CLP</p>
        </div>
        <div class="producto">
            <h3>Manzanas (1 kg)</h3>
            <p>Precio: $1,000 CLP</p>
        </div>
        <div class="producto">
            <h3>Pollo entero (1 kg)</h3>
            <p>Precio: $4,300 CLP</p>
        </div>
        <div class="producto">
            <h3>Azúcar (1 kg)</h3>
            <p>Precio: $1,400 CLP</p>
        </div>
        <div class="producto">
            <h3>Queso laminado (250g)</h3>
            <p>Precio: $2,500 CLP</p>
        </div>
        <div class="producto">
            <h3>Jugo natural (1 litro)</h3>
            <p>Precio: $1,900 CLP</p>
        </div>
        <div class="producto">
            <h3>Aceite vegetal (1 litro)</h3>
            <p>Precio: $2,400 CLP</p>
        </div>
        <div class="producto">
            <h3>Pasta (500g)</h3>
            <p>Precio: $1,000 CLP</p>
        </div>
        <div class="producto">
            <h3>Café instantáneo (170g)</h3>
            <p>Precio: $4,200 CLP</p>
        </div>
        <div class="producto">
            <h3>Yogur (1 litro)</h3>
            <p>Precio: $1,900 CLP</p>
        </div>
        <div class="producto">
            <h3>Detergente en polvo (3 kg)</h3>
            <p>Precio: $5,800 CLP</p>
        </div>
        <div class="producto">
            <h3>Mantequilla (250g)</h3>
            <p>Precio: $2,300 CLP</p>
        </div>
        <div class="producto">
            <h3>Papel higiénico (pack de 12 unidades)</h3>
            <p>Precio: $4,500 CLP</p>
        </div>
        <div class="producto">
            <h3>Cereal (400g)</h3>
            <p>Precio: $2,200 CLP</p>
        </div>
        <div class="producto">
            <h3>Atún en lata (170g)</h3>
            <p>Precio: $1,500 CLP</p>
        </div>
        <div class="producto">
            <h3>Galletas (250g)</h3>
            <p>Precio: $1,200 CLP</p>
        </div>
    </div>

    <div class="contacto" id="contacto">
        <h2>Contacto</h2>
        <form>
            <input type="text" placeholder="Tu nombre" required>
            <input type="email" placeholder="Tu email" required>
            <textarea rows="4" placeholder="Tu mensaje" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </div>

    <div class="informacion" id="informacion">
        <h2>Acerca de nosotros</h2>
        <p>En Supermercado Caami, estamos comprometidos a ofrecer productos de alta calidad a precios accesibles, con un servicio al cliente excepcional y una gran variedad de productos para todas tus necesidades diarias.</p>
    </div>
</main>

<footer>
    <p>Supermercado Caami &copy; 2024</p>
</footer>

</body>
</html>
