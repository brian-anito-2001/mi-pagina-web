# mi-pagina-web
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Venta de Artículos de Artes Marciales</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0f7fa;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #0277bd;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #01579b 3px solid;
        }
        header a {
            color: #fff;
            text-decoration: none;
            text-transform: uppercase;
            font-size: 16px;
        }
        header ul {
            padding: 0;
            list-style: none;
        }
        header ul li {
            display: inline;
            padding: 0 20px 0 20px;
        }
        .showcase {
            background: url('artes-marciales.jpg') no-repeat center center/cover;
            min-height: 400px;
            text-align: center;
            color: #fff;
        }
        .showcase h1 {
            margin-top: 100px;
            font-size: 55px;
            margin-bottom: 10px;
        }
        .showcase p {
            font-size: 20px;
        }
        .productos {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin: 20px 0;
        }
        .producto {
            background: #fff;
            padding: 20px;
            margin: 10px;
            width: 30%;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            border: 1px solid #0277bd;
        }
        .producto img {
            max-width: 100%;
        }
        footer {
            background: #0277bd;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Venta de Artículos de Artes Marciales</h1>
            <ul>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#contacto">Contacto</a></li>
                <li><a href="#ubicacion">Ubicación</a></li>
            </ul>
        </div>
    </header>
    <section class="showcase">
        <div class="container">
            <h1>Bienvenido a Nuestra Tienda</h1>
            <p>Encuentra todo lo que necesitas para tus entrenamientos de artes marciales.</p>
        </div>
    </section>
    <section id="productos" class="productos">
        <div class="container">
            <h2>Nuestros Productos</h2>
            <div class="producto">
                <h3>Uniformes</h3>
                <img src="uniformes.jpg" alt="Uniformes de artes marciales">
                <p>Uniformes de alta calidad para todas las disciplinas.</p>
            </div>
            <div class="producto">
                <h3>Armas</h3>
                <img src="armas.jpg" alt="Armas de artes marciales">
                <p>Gran variedad de armas tradicionales y modernas.</p>
            </div>
            <div class="producto">
                <h3>Protecciones</h3>
                <img src="protecciones.jpg" alt="Protecciones de artes marciales">
                <p>Equipo de protección para garantizar tu seguridad.</p>
            </div>
            <div class="producto">
                <h3>Accesorios</h3>
                <img src="accesorios.jpg" alt="Accesorios de artes marciales">
                <p>Todo tipo de accesorios para complementar tu entrenamiento.</p>
            </div>
        </div>
    </section>
    <section id="contacto" class="contacto">
        <div class="container">
            <h2>Contacto</h2>
            <p>Para más información o realizar una compra, contáctanos por WhatsApp al <a href="https://wa.me/1164762001">1164762001</a>.</p>
        </div>
    </section>
    <section id="ubicacion" class="ubicacion">
        <div class="container">
            <h2>Ubicación</h2>
            <p>Nos encontramos en el barrio Almagro.</p>
        </div>
    </section>
    <footer>
        <p>© 2024 Venta de Artículos de Artes Marciales</p>
    </footer>
</body>
</html>

