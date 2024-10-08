<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tejedoras Tacana</title>
    <style>
        body {
            font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #EFEBE1;
            color: #485040;
        }
        header {
            background-color: #9DA48E;
            color: #EFEBE1;
            padding: 1em 0;
            text-align: center;
            display: flex;
            align-items: center;
            justify-content: center;
            position: relative;
        }
        header img {
            max-width: 100px;
            height: auto;
            margin-right: 20px;
        }
        header h1 {
            margin: 0;
        }
        nav {
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #485040;
        }
        nav a {
            color: #EFEBE1;
            padding: 1em;
            display: inline-block;
            text-decoration: none;
            cursor: pointer;
        }
        nav a:hover {
            background-color: #EFEBE1;
        }
        main {
            padding: 2em;
            text-align: center;
        }
        .content {
            display: none;
        }
        .content.active {
            display: block;
        }
        .contact-image {
            margin: 20px;
        }
        .home-content {
            display: flex;
            flex-direction: row;
            justify-content: center;
            align-items: flex-start;
            gap: 20px;
            text-align: left;
            padding: 1em;
        }
        .home-content img {
            max-width: 45%;
            height: auto;
            flex: 1 1 auto;
        }
        .home-content h2 {
            text-align: center;
            width: 100%;
        }
        .home-content .text {
            width: 45%;
            flex: 1 1 auto;
        }
        .about-content {
            display: flex;
            flex-direction: row;
            justify-content: center;
            gap: 20px;
        }
        .about-content .img {
            max-width: 30%;
            height: auto;

        }
        .projects-content{
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: flex-start;
            gap: 20px;
            text-align: left;
            padding: 1em;
        }
        .projects-content .project-item {
            width: 300px;
            background-color: #9DA48E;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .projects-content img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .gallery-images {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
            padding: 1em;
        }
        .gallery-item {
            display: flex;
            flex-direction: column;
            align-items: center;
            max-width: 250px;
            margin: 10px;
            box-sizing: border-box;
        }
        .gallery-images img {
            max-width: 100%;
            height: auto;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        .gallery-item h3 {
            margin: 10px 0 0 0;
            font-size: 1.2em;
            color:#485040;
            text-align: center;
        }
        footer {
            background-color: #EFEBE1;
            color: #9DA48E;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        img {
            max-width: 500px;
            height: auto;
        }


    </style>
</head>
<body>
    <header>
        <img src="logotacana.jpg" alt="Logo">
        <h1>Tejedoras Tacana</h1>
    </header>
    <nav>
        <a href="#" onclick="showContent('home')">Home</a>
        <a href="#" onclick="showContent('about')">Productos</a>
        <a href="#" onclick="showContent('contact')">Contact</a>
        <a href="#" onclick="showContent('projects')">Proyectos</a>
        <a href="#" onclick="showContent('gallery')">Gallery</a>
    </nav>
    <main>
        <div id="home" class="content active">
            <h2>Home Page</h2>
            <div class="home-content">
                <img src="https://scontent.flpb3-2.fna.fbcdn.net/v/t39.30808-6/456985478_17935698116899546_9080724303604954085_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=127cfc&_nc_ohc=_LDcmK94q64Q7kNvgFc4_Zu&_nc_ht=scontent.flpb3-2.fna&oh=00_AYDlH6HrHNXnssI-hNDIptQzjiwJ7KqkpjUSXiqGVt2cPg&oe=66DA997F" alt="Home Image">
                <div class="text">
                    <p>El emprendimiento de tejidos Tacana es un proyecto integral que no solo promueve las capacidades productivas y revaloriza la cultura, sino que también fomenta un desarrollo inclusivo y sostenible en armonía con la naturaleza. Nuestra misión es preservar y transmitir la rica tradición generacional de la comunidad Tacana, manteniendo vivo el estilo ancestral de tejer que ha unido y empoderado a las mujeres a lo largo del tiempo.</p>
                </div>
            </div>
        </div>
        <div id="about" class="content">
            <h2>Productos</h2>
            <div class="gallery-images">
                <div class="gallery-item">
                    <a href="sombrero.html">
                        <img src="sombrerotacana.jpeg">
                        <h3> Sombrero </h3>
                    </a>
                </div>
                <div class="gallery-item">
                    <a href="llaveros.html">
                        <img src="llaveros.jpeg">
                        <h3> Llaveros </h3>
                    </a>
                </div>
                <div class="gallery-items">
                    <a href="carteras.html">
                        <img src="images (1).jpeg">
                        <h3> Carteras </h3>
                    </a>
                </div>
            </div>
        </div>
        <div id="contact" class="content">
            <h2>Contact Us</h2>
            <p>Mantenganse en contacto!</p>
            <p>Elija una imagen para visitar nuestras redes sociales</p>
            <a href="https://www.facebook.com/p/Tejedoras-Tacana-100088210239057/">
                <img class="contact-image" src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Facebook_logo_%28square%29.png" alt="facebook logo" width="100" height="100">
            </a>
            <a href="https://www.instagram.com/tejedorastacana/">
                <img class="contact-image" src="Instagram_icon.png.webp" alt="instagram logo" width="100" height="100">
            </a>
            <img class="contact-image" src="112-gmail_email_mail-512.webp" alt="email logo" width="100" length="100">
        </div>
        <div id="projects" class="content">
            <h2>Proyectos</h2>
            <div class="projects-content">
                <div class="project-item">
                    <img src="Screenshot 2024-07-31 at 2.11.54 PM.png" alt="Proyecto 1">
                    <p>Estamos felices de anunciar que seremos parte de la 28 <a href="https://www.instagram.com/ferialibrolapaz/">@ferialibrolapaz</a> del 31 de julio al 11 de Agosto en el stand de <a href="https://www.conservation.org/">Conservacion International</a> (Bloque Rojo, 2do piso). Vengan a visitarnos!</p>
                </div>
                <div class="project-item">
                    <img src = "bisa.jpeg" alt="proyecto 2">
                    <p>Orgullasas de collaborar con el Banco Bisa! Estos llaveros son diseños Tacana hechos con colores del banco!</p>
                </div>
            </div>
        </div>
        <div id="gallery" class="content">
            <h2>Photo gallery</h2>
            <div class="gallery-images">
                <img src="https://scontent.flpb3-2.fna.fbcdn.net/v/t39.30808-6/456516103_17935255577899546_7572283721178844848_n.jpg?_nc_cat=102&ccb=1-7&_nc_sid=127cfc&_nc_ohc=FXBKJhKmgAEQ7kNvgERGBfo&_nc_ht=scontent.flpb3-2.fna&oh=00_AYB_v3UbarYuQX9shfqUWWnpGOzwcGw6Yk8BOSv7GHhPug&oe=66DABFEE" alt="sombrero">
                <img src="https://scontent.flpb3-1.fna.fbcdn.net/v/t39.30808-6/454323188_945998944239529_329583220009925412_n.jpg?stp=dst-jpg_p843x403&_nc_cat=110&ccb=1-7&_nc_sid=833d8c&_nc_ohc=ehiKIVAFvjoQ7kNvgG9GAfC&_nc_ht=scontent.flpb3-1.fna&oh=00_AYCgkJay3uWCPc6t9CwwWXa3eL2VeI9czYhKALqIJZs5qQ&oe=66DABBA0" alt="llaveros">
                <img src="https://scontent.flpb3-2.fna.fbcdn.net/v/t39.30808-6/415191870_330654976551508_7174040222299695254_n.jpg?stp=dst-jpg_p960x960&_nc_cat=100&ccb=1-7&_nc_sid=127cfc&_nc_ohc=SOOSr6dGM1IQ7kNvgGDJ257&_nc_ht=scontent.flpb3-2.fna&oh=00_AYBwcTwfwjW1qdiTTNYDDNptjcnFszwugbeFTFUZhFmi_g&oe=66DAC581" alt="sombrero modelado">
            </div>
        </div>
    </main>
    <footer>
        &copy; 2024 Tejedoras Tacana
    </footer>
    <script>
        function showContent(contentId) {
            // Hide all content
            var contents = document.querySelectorAll('.content');
            contents.forEach(function(content) {
                content.classList.remove('active');
            });


            // Show the selected content
            var selectedContent = document.getElementById(contentId);
            if (selectedContent) {
                selectedContent.classList.add('active');
            }
        }
    </script>
</body>
</html>
