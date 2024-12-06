<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Impermeabiliza - Protección Total Contra el Agua</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
        header { background: #005f99; color: white; padding: 20px; text-align: center; }
        nav { background: #003f66; color: white; padding: 10px; text-align: center; }
        nav a { color: white; margin: 0 15px; text-decoration: none; }
        section { padding: 20px; }
        footer { background: #005f99; color: white; text-align: center; padding: 10px; }
        form { max-width: 500px; margin: 0 auto; padding: 20px; border: 1px solid #ccc; border-radius: 10px; }
        form label { display: block; margin: 10px 0 5px; }
        form input, form textarea, form button {
            width: 100%; padding: 10px; margin-bottom: 15px;
            border: 1px solid #ccc; border-radius: 5px;
        }
        form button { background: #005f99; color: white; border: none; cursor: pointer; }
        form button:hover { background: #004070; }
    </style>
</head>
<body>
    <header>
        <h1>Impermeabiliza</h1>
        <p>Protección Total Contra el Agua</p>
    </header>
    <nav>
        <a href="#home">Inicio</a>
        <a href="#services">Servicios</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#about">Sobre Nosotros</a>
        <a href="#contact">Contacto</a>
    </nav>
    <section id="home">
        <h2>Bienvenido a Impermeabiliza</h2>
        <p>Ofrecemos los mejores servicios de impermeabilización para proteger tu hogar o negocio.</p>
    </section>
    <section id="services">
        <h2>Servicios</h2>
        <ul>
            <li>Impermeabilización de techos</li>
            <li>Protección de paredes</li>
            <li>Sellado de juntas</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Contáctanos</h2>
        <form action="https://formspree.io/f/tu-correo-aqui" method="POST">
            <label for="name">Nombre:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Correo Electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Mensaje:</label>
            <textarea id="message" name="message" rows="5" placeholder="Describe lo que necesitas..." required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </section>
    <footer>
        <p>© 2024 Impermeabiliza. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
