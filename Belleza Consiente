<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Belleza Consiente - Masajes & Limpieza Facial</title>
    <!-- Google Fonts para tipografías similares a las de la imagen -->
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <!-- Iconos de Bootstrap Icons, puedes incluirlos vía CDN o como SVG inline -->
    <!-- Para este ejemplo, usaremos SVG inline en el HTML para los iconos -->

    <style>
        /* Variables de color para fácil mantenimiento */
        :root {
            --primary-pink: #af6e77; /* Rosa principal de los botones y acentos */
            --dark-brown: #5d4037;   /* Marrón oscuro para textos principales */
            --light-cream: #f7f3f0;  /* Fondo general claro */
            --light-pink-bg: #f7e6e9; /* Fondo rosa claro de secciones */
            --gray-text: #777;       /* Gris para textos secundarios */
        }

        /* Reset básico y estilos generales */
        body {
            font-family: 'Montserrat', sans-serif; /* Fuente general */
            margin: 0;
            padding: 0;
            background-color: var(--light-cream);
            color: var(--dark-brown);
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Estilos del Encabezado (Header) */
        .header {
            background-color: #f7e6e9; /* Color de fondo si no carga la imagen */
            /* URL de imagen principal (persona recibiendo masaje facial) */
            background-image: url('https://images.unsplash.com/photo-1622384793663-e38ce713a275?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
            background-size: cover;
            background-position: center center;
            min-height: 550px;
            display: flex;
            align-items: center;
            justify-content: flex-start;
            position: relative;
            padding: 40px;
            border-bottom-left-radius: 20px;
            border-bottom-right-radius: 20px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
            overflow: hidden;
        }

        .header::before {
            content: '✨'; /* Adornos */
            position: absolute;
            top: 20px;
            left: 20px;
            font-size: 2em;
            color: var(--primary-pink);
            opacity: 0.7;
        }
        .header::after {
            content: '✨'; /* Adornos */
            position: absolute;
            top: 50px;
            left: 50px;
            font-size: 1.5em;
            color: var(--primary-pink);
            opacity: 0.5;
        }


        .header-content {
            position: relative;
            z-index: 2;
            background-color: rgba(255, 255, 255, 0.85);
            padding: 30px 40px;
            border-radius: 15px;
            max-width: 450px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.08);
            margin-left: 5%;
        }

        .header .logo {
            margin-bottom: 20px;
            text-align: center;
        }
        .header .logo img {
            max-width: 180px;
            height: auto;
            margin-bottom: 5px;
        }
        .header .logo p {
            font-family: 'Montserrat', sans-serif;
            font-size: 0.8em;
            color: var(--dark-brown);
            margin: 0;
            font-style: italic;
        }

        .header h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3.5em;
            color: var(--dark-brown);
            margin: 0 0 5px 0;
            line-height: 1;
        }
        .header h2 {
            font-family: 'Playfair Display', serif;
            font-size: 3em;
            color: var(--primary-pink);
            margin: 0 0 20px 0;
            line-height: 1;
        }
        .header p {
            font-size: 1.1em;
            color: var(--gray-text);
            margin-bottom: 30px;
        }
        .header p strong {
            color: var(--dark-brown);
        }

        .reserve-button {
            display: inline-flex;
            align-items: center;
            background-color: var(--primary-pink);
            color: #fff;
            padding: 15px 30px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            font-size: 1.1em;
            transition: background-color 0.3s ease, transform 0.2s ease;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }
        .reserve-button:hover {
            background-color: #e08390;
            transform: translateY(-2px);
        }
        .reserve-button svg {
            margin-right: 10px;
        }

        .header .priority-message {
            margin-top: 20px;
            font-size: 0.9em;
            color: var(--dark-brown);
            font-style: italic;
        }

        /* Secciones */
        section {
            padding: 40px 0;
        }

        .section-title {
            text-align: center;
            font-family: 'Playfair Display', serif;
            font-size: 2.5em;
            color: var(--dark-brown);
            margin: 60px 0 40px 0;
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .section-title::before,
        .section-title::after {
            content: '';
            height: 1px;
            background-color: var(--primary-pink);
            width: 80px;
            margin: 0 15px;
            display: block;
        }
        .section-title .decorative-element {
            font-size: 1.2em;
            color: var(--primary-pink);
            margin: 0 10px;
        }

        /* Grid de Servicios */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-bottom: 60px;
        }
        .service-card {
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            text-align: center;
            padding-bottom: 20px;
            overflow: hidden;
            transition: transform 0.3s ease;
        }
        .service-card:hover {
            transform: translateY(-5px);
        }
        .service-card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            border-top-left-radius: 15px;
            border-top-right-radius: 15px;
        }
        .service-card h3 {
            font-family: 'Playfair Display', serif;
            font-size: 1.8em;
            color: var(--dark-brown);
            margin: 25px 0 10px 0;
        }
        .service-card p {
            color: var(--gray-text);
            padding: 0 25px;
            margin-bottom: 20px;
        }
        .service-card .info-row {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 10px;
            color: var(--dark-brown);
            font-size: 1.1em;
        }
        .service-card .info-row svg {
            margin-right: 8px;
            color: var(--primary-pink);
        }
        .service-card .price {
            font-weight: bold;
            font-size: 1.5em;
            color: var(--primary-pink);
            margin-bottom: 20px;
        }
        .service-card .reserve-btn {
            display: inline-block;
            background-color: var(--primary-pink);
            color: #fff;
            padding: 12px 25px;
            border-radius: 25px;
            text-decoration: none;
            font-weight: bold;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }
        .service-card .reserve-btn:hover {
            background-color: #e08390;
            transform: translateY(-2px);
        }

        /* Por Qué Elegirnos */
        .why-choose-us {
            background-color: var(--light-pink-bg);
            padding: 60px 20px;
            margin-bottom: 60px;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.05);
        }
        .why-choose-us h2 {
            text-align: center;
            font-family: 'Playfair Display', serif;
            font-size: 2em;
            color: var(--dark-brown);
            margin-bottom: 50px;
        }
        .why-choose-us-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 30px;
            text-align: center;
        }
        .why-choose-us-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 15px;
        }
        .why-choose-us-item svg {
            width: 45px;
            height: 45px;
            color: var(--primary-pink);
            margin-bottom: 15px;
        }
        .why-choose-us-item p {
            color: var(--dark-brown);
            font-weight: 600;
            font-size: 1.05em;
        }

        /* Contáctanos */
        .contact-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            padding: 50px 20px;
            background-color: #fff;
            margin-bottom: 60px;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        .contact-info-block {
            flex: 1;
            min-width: 300px;
            max-width: 500px;
            margin: 20px;
            padding: 30px;
            border-radius: 10px;
            background-color: var(--light-cream);
            box-shadow: inset 0 1px 5px rgba(0,0,0,0.05);
        }
        .contact-info-block h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2em;
            color: var(--dark-brown);
            margin-bottom: 30px;
            text-align: center;
        }
        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 20px;
            color: var(--dark-brown);
            font-size: 1.1em;
        }
        .contact-item svg {
            width: 28px;
            height: 28px;
            margin-right: 15px;
            color: var(--primary-pink);
            flex-shrink: 0;
        }
        .contact-item a {
            color: var(--dark-brown);
            text-decoration: none;
            transition: color 0.3s ease;
        }
        .contact-item a:hover {
            color: var(--primary-pink);
        }

        .contact-image-block {
            flex: 1;
            min-width: 300px;
            max-width: 500px;
            margin: 20px;
            text-align: center;
        }
        .contact-image-block img {
            max-width: 100%;
            height: auto;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        /* Cupos Limitados */
        .limited-slots-section {
            background-color: var(--light-pink-bg);
            padding: 50px 20px;
            text-align: center;
            border-radius: 15px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
            position: relative;
            overflow: hidden;
            margin-bottom: 60px;
        }
        .limited-slots-section .decorative-flower-left {
            position: absolute;
            bottom: -20px;
            left: -20px;
            font-size: 6em;
            color: var(--primary-pink);
            opacity: 0.1;
            transform: rotate(-30deg);
        }
        .limited-slots-section .decorative-flower-right {
            position: absolute;
            top: -20px;
            right: -20px;
            font-size: 6em;
            color: var(--primary-pink);
            opacity: 0.1;
            transform: rotate(30deg);
        }
        .limited-slots-section .content {
            position: relative;
            z-index: 1;
        }
        .limited-slots-section .icon {
            width: 55px;
            height: 55px;
            color: var(--primary-pink);
            margin-bottom: 15px;
        }
        .limited-slots-section h2 {
            font-family: 'Playfair Display', serif;
            font-size: 2.2em;
            color: var(--dark-brown);
            margin-bottom: 10px;
        }
        .limited-slots-section p {
            color: var(--dark-brown);
            margin-bottom: 25px;
            font-size: 1.1em;
            max-width: 600px;
