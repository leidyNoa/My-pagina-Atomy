# My-pagina-Atomy
Estética y cosmetología
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Atomy</title>
    <style>
        /* CSS */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #666;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
        }

        nav a:hover {
            background-color: #999;
        }

        #productos {
            padding: 20px;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .producto {
            margin: 20px;
            padding: 20px;
            border: 1px solid #ccc;
            text-align: center;
            width: 300px;
        }

        .producto img {
            max-width: 100%;
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>¡Bienvenido a Atomy!</h1>
    </header>
    <nav>
        <a href="#">Inicio</a>
        <a href="#">Productos</a>
        <a href="#">Acerca de Nosotros</a>
        <a href="#">Contacto</a>
    </nav>
    <section id="productos">
        <h2>Productos Destacados</h2>
        <div class="producto">
            <img src="imagen1.jpg" alt="Producto 1">
            <h3>Producto 1</h3>
            <p>Descripción del producto 1.</p>
        </div>
        <div class="producto">
            <img src="imagen2.jpg" alt="Producto 2">
            <h3>Producto 2</h3>
            <p>Descripción del producto 2.</p>
        </div>
        <!-- Agrega más productos según sea necesario -->
    </section>
    <footer>
        <p>Derechos de Autor &copy; 2024 - Mi Página Atomy</p>
    </footer>
</body>
</html>
