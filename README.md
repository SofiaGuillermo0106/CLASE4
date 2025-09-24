<!DOCTYPE html>
<html>
<head>
    <title>Tienda SuperRobot</title>
    <link rel="icon" type="image/jpeg" href="imagen.jpg">
    <style>
        /* MENÚ SUPERIOR */
        nav {
            background-color: black;
            padding: 10px 0;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: aquamarine;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: brown;
        }

        .contenedor {
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            justify-content: space-around;
            background-color: rgb(70, 219, 219);
            padding: 20px; 
        }

        .titulo, .imagen {
            text-align: center;
            flex-basis: 100px;
            flex-grow: 1;
        }

        .imagen img {
            max-width: 500px;
            height: auto;
            border-radius: 15px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.3);
            max-width: 100%;
        }

        .footer {
            background-color: rgb(27, 27, 24);
            color: rgb(233, 233, 188);
            text-align: center;
            padding: 15px 0;
            margin-top: 20px;
            font-size: 24px;
        }
    </style>
</head>
<body>
    <!-- Menú de Navegación -->
    <nav>
        <ul>
            <li><a href="#">Inicio</a></li>
            <li><a href="#">Productos</a></li>
            <li><a href="#">Ofertas</a></li>
            <li><a href="#">Contacto</a></li>
        </ul>
    </nav>

    <div class="contenedor">
        <div class="titulo">
            <h1>Bienvenidos a la tienda SuperRobot</h1>               
        </div>

        <div class="imagen">
            <img src="imagen.jpg" alt="Juguete SuperRobot">
        </div>

        <div class="titulo">
            <h2>Descubre el juguete más emocionante del año</h2>
        </div>
    </div>

    <footer class="footer">
        © 2025 SuperRobot – Todos los derechos reservados
    </footer>
</body>
</html>

