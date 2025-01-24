<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>C&R - Refrigeración y Climatización</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background-color: #003366;
            display: flex;
            justify-content: center;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 2rem;
        }
        .services, .testimonials {
            background-color: #f4f4f4;
            margin: 1rem 0;
            padding: 1rem;
            border-radius: 8px;
        }
        footer {
            background-color: #004080;
            color: white;
            text-align: center;
            padding: 1rem 0;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
            max-width: 400px;
            margin: 0 auto;
        }
        .contact-form input, .contact-form textarea {
            margin-bottom: 1rem;
            padding: 0.5rem;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .contact-form button {
            background-color: #004080;
            color: white;
            border: none;
            padding: 0.5rem;
            border-radius: 4px;
            cursor: pointer;
        }
        .contact-form button:hover {
            background-color: #003366;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenidos a C&R</h1>
        <p>Especialistas en reparación y mantenimiento de equipos de refrigeración y climatización</p>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#servicios">Servicios</a>
        <a href="#testimonios">Testimonios</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="inicio">
        <h2>¿Quiénes somos?</h2>
        <p>En C&R nos dedicamos a ofrecer soluciones confiables y de calidad en el mantenimiento y reparación de equipos de refrigeración y climatización. Nuestro compromiso es garantizar tu comodidad y satisfacción.</p>
    </section>

    <section id="servicios" class="services">
        <h2>Nuestros Servicios</h2>
        <ul>
            <li>Reparación de equipos de refrigeración.</li>
            <li>Mantenimiento preventivo y correctivo de sistemas de climatización.</li>
            <li>Instalación de aires acondicionados y cámaras frigoríficas.</li>
        </ul>
    </section>

    <section id="testimonios" class="testimonials">
        <h2>Lo que dicen nuestros clientes</h2>
        <blockquote>"¡Excelente servicio! Mi aire acondicionado funciona como nuevo. 100% recomendados." - Cliente satisfecho</blockquote>
        <blockquote>"Profesionales y atentos. Resolvieron el problema de mi refrigerador en tiempo récord." - Cliente feliz</blockquote>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>¡Ponte en contacto con nosotros para más información o agendar una cita!</p>
        <form class="contact-form">
            <input type="text" placeholder="Tu nombre" required>
            <input type="email" placeholder="Tu correo" required>
            <textarea placeholder="Tu mensaje" rows="4" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>© 2025 C&R. Todos los derechos reservados. | Síguenos en <a href="#">Instagram</a></p>
    </footer>
</body>
</html>
