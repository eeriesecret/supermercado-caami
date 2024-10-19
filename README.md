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
            <img src="leche.jpg" alt="Leche" style="width:100%; height:auto;">
            <h3>Leche</h3>
            <p>Precio: $1.00</p>
        </div>
        <div class="producto">
            <img src="pan.jpg" alt="Pan" style="width:100%; height:auto;">
            <h3>Pan</h3>
            <p>Precio: $0.50</p>
        </div>
        <div class="producto">
            <img src="huevos.jpg" alt="Huevos" style="width:100%; height:auto;">
            <h3>Huevos</h3>
            <p>Precio: $2.00</p>
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
       <p>  
        <h4> Nuestra mision es brindar productos de calidad a precios accesibles, mejorando la calidad de vida de nuestras comunidades. Nos esforzamos por ofrecer un servicio excepcional, garantizando una experiencia de compra cómoda, rápida y satisfactoria, mientras promovemos prácticas sostenibles y el desarrollo de nuestros empleados.</h4>
       <h4> Nuestra vision es ser el supermercado líder en la región, reconocido por nuestra innovación, responsabilidad social y compromiso con la satisfacción del cliente. Queremos ser el lugar preferido para hacer las compras diarias, ofreciendo productos frescos, saludables y una experiencia de compra personalizada.</h4>
    <h4>Nuestros valores son fundamentales para todo lo que hacemos: nos comprometemos a ofrecer productos de alta calidad, frescos y de marcas reconocidas, priorizando siempre la satisfacción del cliente al superar sus expectativas. Innovamos constantemente en nuestros procesos y servicios para brindar una experiencia moderna y eficiente, mientras promovemos prácticas sostenibles, apoyando productos locales y reduciendo nuestro impacto ambiental. Valoramos a nuestros empleados, fomentando un ambiente de trabajo colaborativo, y actuamos con transparencia e integridad en todas nuestras operaciones.</h4>
    <h4>Nuestros objetivos se centran en mejorar la atención al cliente, reduciendo los tiempos de espera y optimizando la experiencia de compra. Planeamos incrementar en un 20% la oferta de productos locales el próximo año, y reducir en un 30% el uso de plásticos de un solo uso, promoviendo el reciclaje. También implementaremos nuevas tecnologías para hacer más eficiente la gestión de inventarios y el servicio en caja, mientras buscamos abrir al menos dos nuevas sucursales en áreas estratégicas en los próximos dos años.</h4>
</p>&copy; 2024 Supermercado Caami.
