<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Supermercado Ejemplo</title>
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
    <h1>Supermercado Ejemplo</h1>
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
            <h3>Leche</h3>
            <p>Precio: $1,290</p>
        </div>
        <div class="producto">
            <h3>Pan de molde</h3>
            <p>Precio: $2,190</p>
        </div>
        <div class="producto">
            <h3>Huevos</h3>
            <p>Precio: $3,200</p>
        </div>
        <div class="producto">
            <h3>Arroz</h3>
            <p>Precio: $1,290</p>
        </div>
        <div class="producto">
            <h3>Pollo fresco</h3>
            <p>Precio: $3,490</p>
        </div>
        <div class="producto">
            <h3>Carne molida</h3>
            <p>Precio: $6,990</p>
        </div>
        <div class="producto">
            <h3>Manzanas</h3>
            <p>Precio: $1,290</p>
        </div>
        <div class="producto">
            <h3>Plátanos</h3>
            <p>Precio: $1,090</p>
        </div>
        <div class="producto">
            <h3>Aceite vegetal</h3>
            <p>Precio: $2,590</p>
        </div>
        <div class="producto">
            <h3>Coca-Cola</h3>
            <p>Precio: $1,690</p>
        </div>
        <div class="producto">
            <h3>Cerveza Austral</h3>
            <p>Precio: $1,690</p>
        </div>
        <div class="producto">
            <h3>Detergente Omo</h3>
            <p>Precio: $8,990</p>
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
        <p>Somos un supermercado comprometido con la calidad, la satisfacción del cliente y la sostenibilidad. Ofrecemos productos frescos y locales para satisfacer todas tus necesidades.</p>
    </div>
</main>

<footer>
    <p>&copy; 2024 Supermercado Ejemplo. Todos los derechos reservados.</p>
</footer>

</body>
</html>
