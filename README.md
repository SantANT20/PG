<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>artesanias lupita durango</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fef9f4;
            color: #333;
        }

        header {
            background-color: #8c4a25;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #d99c6b;
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 10px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        h2 {
            color: #8c4a25;
        }

        .productos {
            display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: center;
        }

        .producto {
            background-color: white;
            border: 1px solid #ddd;
            padding: 15px;
            width: 250px;
            border-radius: 8px;
            text-align: center;
        }

        .producto img {
            max-width: 100%;
            border-radius: 5px;
        }

        .galeria {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            justify-content: center;
        }

        .galeria img {
            width: 200px;
            border-radius: 5px;
        }

        .galeria video {
            width: 300px;
            border-radius: 5px;
        }

        footer {
            background-color: #8c4a25;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }

        .boton-contacto {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px;
            border-radius: 5px;
            text-decoration: none;
            color: white;
            font-weight: bold;
        }

        .facebook {
            background-color: #3b5998;
        }

        .whatsapp {
            background-color: #25d366;
        }

        .maps {
            background-color: #4285F4;
        }
    </style>
</head>
<body>
    <header>
        <h1>artesanias lupita durango</h1>
        <p>elaboracion y venta de artesanias tipicas de durango Mexico</p>
    </header>

    <nav>
        <a href="#inicio" class="con-sonido">Inicio</a>
        <a href="#productos" class="con-sonido">Productos</a>
        <a href="#galeria" class="con-sonido">Galería</a>
        <a href="#contacto" class="con-sonido">Contacto</a>
    </nav>

    <section id="inicio">
        <h2>Bienvenidos</h2>
        <p>artesanias lupita le ofrece a usted una gran variedad de cosas tales son como los recuerditos para la familia o tambien puede llevarse una botellita de mezcal con su respectivo alacran dentro para los amigos tambien tiene usted la oportunidad de tomarse una foto con un alacran real en la mano o en donde usted quiera por tan solo 10 pesos no desaproveche esta oportunidad y venga a visitarnos en el mercado gomez palacio durango lo esperamos con ansias</p>
    </section>

    <section id="productos">
        <h2>Nuestros Productos</h2>
        <div class="productos">
            <div class="producto">
                <h3>Barro Duranguense</h3>
                <p>Decoraciones y utensilios de cocina únicos.</p>
            </div>
            <div class="producto">
                <h3>Textiles Artesanales</h3>
                <p>Tejidos coloridos hechos en telar de cintura.</p>
            </div>
            <div class="producto">
                <h3>Joyería de Cobre</h3>
                <p>Piezas únicas elaboradas a mano.</p>
            </div>
        </div>
    </section>

    <section id="galeria">
        <h2>Galería</h2>
        <div class="galeria">
            <!-- Fotos (23 espacios) -->
            <img src="imagen 3.jfif" alt="Foto 3">
            <img src="imagen 4.jfif" alt="Foto 4">
            <img src="imagen 5.jfif" alt="Foto 5">
            <img src="imagen 6.jfif" alt="Foto 6">
            <img src="imagen 7.jfif" alt="Foto 7">
            <img src="imagen 8.jfif" alt="Foto 8">
            <img src="imagen 9.jfif" alt="Foto 9">
            <img src="imagen 21.jfif" alt="Foto 21">
 

           <!-- Videos (4 espacios) -->
            <video controls>
                <source src="video1.mp4" type="video/mp4">
                Tu navegador no soporta videos HTML5.
            </video>
            <video controls>
                <source src="video 2.mp4" type="video/mp4">
                Tu navegador no soporta videos HTML5.
            </video>
            <video controls>
            <source src="animacion1.mp4" type="video/mp4">
            Tu navegador no soporta videos HTML5.
        </video>
        <video controls>
            <source src="animacion2.mp4" type="video/mp4">
            Tu navegador no soporta videos HTML5.
        </video>
        </div>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes encontrarnos en redes sociales, enviarnos un mensaje o visitar nuestra ubicación física:</p>
        <p><strong>Dirección:</strong> Mercado Gómez Palacio, Av. 20 de Noviembre 208-Local 90, Zona Centro, 34000 Durango, Dgo.</p>
        <div style="text-align: center; margin-top: 20px;">
            <a href="https://www.facebook.com/share/1AFUErwPKV/?mibextid=wwXIfr" target="_blank" class="boton-contacto facebook con-sonido">
                Visítanos en Facebook
            </a>
            <a href="https://wa.me/5216181385643" target="_blank" class="boton-contacto whatsapp con-sonido">
                Enviar WhatsApp
            </a>
            <a href="https://www.google.com/maps?q=Mercado+Gomez+Palacio,+Av.+20+de+Noviembre+208-Local+90,+Zona+Centro,+34000+Durango,+Dgo." target="_blank" class="boton-contacto maps con-sonido">
                Ver en Google Maps
            </a>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Artesanías de Durango | Todos los derechos reservados de Alan Francisco Adrián Meza y Rembran Leonardo</p>
    </footer>

    <!-- Audio oculto -->
    <audio id="salto-sonido" src="salto-mario.mp3" preload="auto"></audio>

    <!-- Script para reproducir el sonido al hacer clic -->
    <script>
        document.addEventListener('DOMContentLoaded', function () {
            const sonido = document.getElementById('salto-sonido');
            const elementos = document.querySelectorAll('.con-sonido');

            elementos.forEach(function (elemento) {
                elemento.addEventListener('click', function () {
                    sonido.play();
                });
            });
        });
    </script>
</body>
</html>
