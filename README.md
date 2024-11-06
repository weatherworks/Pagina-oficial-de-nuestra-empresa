<html lang="es"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guía Completa para Crear una Estación Meteorológica</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600&display=swap');
        
        body {
            font-family: 'Open Sans', sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            background-image: url('https://www.transparenttextures.com/patterns/snow.png'); /* Fondo de copos de nieve */
            background-size: cover;
            color: #2c3e50;
            padding-left: 15%;
            padding-right: 15%;
        }

        header {
            background: linear-gradient(135deg, #ff8a65, #ffcc80);
            color: #fff;
            padding: 30px;
            text-align: center;
            font-size: 2.5em;
            font-weight: bold;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
        }

        .container {
            width: 85%;
            margin: 30px auto;
        }

        .box {
            background: #ffffff;
            margin: 20px 0;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
            border: 2px solid #00897b;
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
        }

        .box img {
            max-width: 40%;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #37474f;
            font-size: 1.8em;
            font-weight: bold;
            border-bottom: 3px solid #00897b;
            padding-bottom: 10px;
            margin-bottom: 20px;
        }

        p {
            font-size: 1.2em;
            margin: 15px 0;
            flex-basis: 55%;
        }

        a {
            color: #00897b;
            text-decoration: none;
            font-weight: 600;
            transition: color 0.3s ease;
        }

        a:hover {
            color: #ff8a65;
            text-decoration: underline;
        }

        .image-link {
            text-align: center;
            margin: 30px 0;
        }

        .image-link img {
            width: 80%;
            max-width: 700px;
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .image-link img:hover {
            transform: scale(1.05);
        }

        .video-container {
            text-align: center;
            margin: 40px 0;
        }

        .video-container iframe {
            width: 80%;
            max-width: 700px;
            height: 400px;
            border: none;
            border-radius: 12px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
        }

        .highlighted-link {
            font-size: 1.4em;
            font-weight: bold;
            color: #00897b;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .highlighted-link:hover {
            color: #ff8a65;
        }

        footer {
            background: linear-gradient(135deg, #76b6c4, #6c85a6);
            color: #fff;
            text-align: center;
            padding: 20px 0;
            font-size: 0.9em;
            position: relative;
        }

        footer a {
            color: #ffcc80;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Estilos para la barra de íconos sociales */
        .social-bar {
            margin-top: 10px;
        }

        .social-bar a {
            margin: 0 10px;
            font-size: 2em;
            color: #fff;
            transition: color 0.3s ease;
        }

        .social-bar a:hover {
            color: #ffcc80;
        }

        .social-bar .icon-whatsapp {
            color: #25D366;
        }

        /* Estilos para el cuadro que contiene los íconos sociales */
        .social-box {
            background-color: #ffffff;
            border-radius: 12px;
            padding: 20px;
            box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
            margin: 30px auto;
            max-width: 300px;
            text-align: center;
        }
    </style>
    <!-- Librería de iconos de Font Awesome -->
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
    <header>
Estación Meteorologica de Weather Works Engineering
    </header>

    <div class="container">
        <div class="box">
            <p><strong>Introducción:</strong> Las estaciones meteorológicas personales no solo te permiten recopilar datos sobre el clima local, sino que también ofrecen múltiples beneficios para mejorar tu entorno y tomar decisiones informadas. Conoce más sobre cómo pueden transformar tu día a día.</p>
            <img src="https://scontent.fpei2-1.fna.fbcdn.net/v/t39.30808-6/464512744_122119377026521478_3827279174906785252_n.jpg?stp=dst-jpg_s640x640&amp;_nc_cat=110&amp;ccb=1-7&amp;_nc_sid=127cfc&amp;_nc_ohc=Q0KqoZURTJUQ7kNvgE1gwj1&amp;_nc_zt=23&amp;_nc_ht=scontent.fpei2-1.fna&amp;_nc_gid=AN-IaB-wjnwz5k1WAh5-lEu&amp;oh=00_AYCV-WV7Z1jznecQItHpLg0joXsY3d2t0WIZzmUgCmtKsQ&amp;oe=6731A9D8" alt="Estación Meteorológica">
        </div>

        <div class="box">
            <p><strong>Beneficios:</strong> Al instalar tu propia estación meteorológica, tendrás acceso a datos en tiempo real sobre la temperatura, humedad, presión atmosférica y viento en tu localidad. Esto te permitirá anticiparte a cambios climáticos, planificar tus actividades, proteger tu hogar y contribuir a la ciencia comunitaria.</p>
            <img src="https://scontent.fpei2-1.fna.fbcdn.net/v/t39.30808-6/464591697_122119379474521478_1314294916555894626_n.jpg?stp=dst-jpg_p526x296&amp;_nc_cat=104&amp;ccb=1-7&amp;_nc_sid=127cfc&amp;_nc_ohc=IaVfcfnWHRsQ7kNvgHWy2Qi&amp;_nc_zt=23&amp;_nc_ht=scontent.fpei2-1.fna&amp;_nc_gid=AxXGBJJb9s1hDZy_3gG2iKl&amp;oh=00_AYDNZyY1jm2eABYwE_OGkVY_P8pFPz2OW6xmO4pzs08OMA&amp;oe=6731A722" alt="Beneficios de la Estación">
        </div>

        <div class="box">
            <p><strong>Control sobre tu entorno:</strong> Imagina poder monitorear las condiciones del clima y optimizar el uso de energía en tu hogar, como ajustar la calefacción o el aire acondicionado según las condiciones reales. ¡Es una gran ventaja en eficiencia y ahorro!</p>
            <img src="https://scontent.fpei2-2.fna.fbcdn.net/v/t39.30808-6/464519649_122119379690521478_4205827883713381775_n.jpg?stp=dst-jpg_p526x296&amp;_nc_cat=107&amp;ccb=1-7&amp;_nc_sid=127cfc&amp;_nc_ohc=Ql8Fej7QjjsQ7kNvgFf4boT&amp;_nc_zt=23&amp;_nc_ht=scontent.fpei2-2.fna&amp;_nc_gid=AxXGBJJb9s1hDZy_3gG2iKl&amp;oh=00_AYDEqXAs0Upw4qeSDB67ZVM6AzMP_1nv6efe934cHluObw&amp;oe=6731B354" alt="Ahorro de Energía">
        </div>

        <div class="image-link">
            <p>Esquema de una estación meteorológica:</p>
            <img src="https://scontent.fpei2-2.fna.fbcdn.net/v/t39.30808-6/464572777_122119380020521478_6191685006159723792_n.jpg?stp=dst-jpg_s960x960&amp;_nc_cat=109&amp;ccb=1-7&amp;_nc_sid=127cfc&amp;_nc_ohc=lwX8Nc4la6AQ7kNvgFJvhRM&amp;_nc_zt=23&amp;_nc_ht=scontent.fpei2-2.fna&amp;_nc_gid=AFZrnOGjEbHv7k3NHUNomer&amp;oh=00_AYCt0f_mr46L0s4TnN5OZZFbDyu-ypCJYGFn-l_AlULVcQ&amp;oe=67319B15" alt="Esquema de Estación Meteorológica">
        </div>

        <div class="video-container">
            <h2>Video Tutorial</h2>
            <iframe src="https://www.youtube.com/embed/pqg6V0yMmv4?si=_vnt-SsTsGlDa2_L" title="YouTube video player" allowfullscreen=""></iframe>
        </div>

        <div class="video-container">
        </div>

        <div class="video-container">
            <a href="[https://weatherworks.github.io/graficas-de-las-pagina-de-weatherwork/](https://weatherworks.github.io/Graficas-Oficiales-/)" class="highlighted-link">Ver Gráficas y Estadísticas</a>
        </div>

        <div class="box">
            <p><strong>Mantenimiento de la Estación:</strong> Asegúrate de que los sensores estén siempre en buen estado, realizando mantenimiento regular, especialmente si la estación está ubicada al aire libre. Cambia los componentes que se deterioren con el tiempo para mantener la precisión de los datos.</p>
            <img src="https://scontent.fpei2-1.fna.fbcdn.net/v/t39.30808-6/464421195_122119379912521478_1642730422400447495_n.jpg?stp=dst-jpg_p526x296&amp;_nc_cat=103&amp;ccb=1-7&amp;_nc_sid=127cfc&amp;_nc_ohc=xpCEJTowrzsQ7kNvgFBBk16&amp;_nc_zt=23&amp;_nc_ht=scontent.fpei2-1.fna&amp;_nc_gid=AxXGBJJb9s1hDZy_3gG2iKl&amp;oh=00_AYCedjinA3eS8AflhRSXm7bVFrJ4vp3g83FhWYePxn6iuQ&amp;oe=6731A09E" alt="Mantenimiento de Estación">
        </div>

        <div class="box">
            <p><strong>Puedes contactarnos a través  de:</strong></p><strong> </strong><p><strong> </strong> instagram:weatherworks1004 </p> 
             <p> facebook: We Ather </p> <p>whatsapp:+57 323 5928060 </p>
            <img src="https://resizer.iproimg.com/unsafe/1280x/filters:format(webp):quality(70)/https://assets.iprofesional.com/assets/jpg/2019/07/480394.jpg" alt="Ampliación del Proyecto">
        </div>
    </div>

    <div class="social-box">
        <a href="https://www.instagram.com/whatherworks1004" target="_blank" class="fab fa-instagram"></a>
        <a href="https://www.facebook.com/whatherworks1004" target="_blank" class="fab fa-facebook"></a>
        <a href="https://wa.me/573235928060" target="_blank" class="fab fa-whatsapp icon-whatsapp"></a>
    </div>

    <footer>
        © 2024 Proyecto Estudiantil | <a href="#">Política de privacidad</a> | <a href="#">Términos de uso</a>

        <div class="social-bar">
            <a href="https://www.instagram.com/whatherworks1004" target="_blank" class="fab fa-instagram"></a>
            <a href="https://www.facebook.com/whatherworks1004" target="_blank" class="fab fa-facebook"></a>
            <a href="https://wa.me/573235928060" target="_blank" class="fab fa-whatsapp icon-whatsapp"></a>
        </div>
    </footer>


</body></html>
