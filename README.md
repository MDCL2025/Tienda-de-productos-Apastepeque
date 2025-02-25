<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Productos  Originales</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenido a Nuestra Tienda busca el producto que mas te llame la atención entregas solo en Apastepeque</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <h2>Inicio</h2>
        <p>Bienvenido a nuestra tienda en línea. Aquí encontrarás los mejores productos al mejor precio elije  escribenos.</p>
    </section>

    <section id="productos">
        <h2>Nuestros Productos</h2>
        <div class="producto">
            <img src="chaqueta.png" alt="chaqueta original">
            <h3>Producto 1</h3>
            <p>Descripción del Producto 1.</p>Chaqueta de Béisbol Casual de Estilo Urbano con Parche de Letra R para Hombre - Poliéster, Morado y Negro con Rayas Blancas, Cierre con Botones, con Bolsillos
            <p>Precio: $20.50</p>
        </div>
        <div class="producto">
            <img src="pantalon cargo.png" alt="pantalon">
            <h3>Producto 2</h3>
            <p>Descripción del Producto 2.</p>Pantalones Cargo Casuales para Hombre, 100% Poliéster de Color Sólido, Ajuste Regular para Todas las Estaciones con Detalles de Botones, Tejido de Seda, 150-1.0g/m² - Estilo Urbano Pantalones de Moto para Exteriores, Pantalones de Moto
            <p>Precio: $16</p>
        </div>
        <div class="producto">
            <img src="teclado mecanico.png" alt="teclado">
            <h3>Producto 3</h3>
            <p>Descripción del Producto 3.</p>Teclado mecánico inalámbrico para juegos K68 60% compacto de 68 teclas, modo dual 5.0/2.4GHz con receptor 2 en 1, interruptor rojo lineal para PC Mac Xbox, diseño ergonómico, alimentado por batería (batería no incluida), teclado compacto

            <p>Precio: $39</p>
        </div>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes contactarnos a través del siguiente formulario:</p>
        <form action="enviar.php" method="post">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Tienda de Productos. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
