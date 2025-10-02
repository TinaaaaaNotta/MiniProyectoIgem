<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyecto de Detección de Cadmio</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #215839;
            padding: 15px 30px;
            position: relative;
        }

        .header-container {
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: nowrap;
        }

        .header-logo {
            width: 100px;
            height: auto;
            margin-right: 20px;
        }

        .header-text {
            color: white;
            flex-grow: 1;
        }

        .header-text h1 {
            font-size: 24px;
            margin: 0;
            font-weight: 600;
        }

        .header-text p {
            margin: 5px 0 0;
            font-size: 14px;
        }

        .menu-icon {
            font-size: 26px;
            color: white;
            cursor: pointer;
        }

        main {
            padding: 40px;
            max-width: 900px;
            margin: auto;
            background-color: rgb(255, 255, 255);
        }

        h2 {
            color: #2e8b57;
        }

        img {
            max-width: 100%;
            height: auto;
            margin: 20px 0;
        }
        #equipo {
            text-align: center;
            margin-top: 40px;
        }

        .equipo-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 30px;
            margin-top: 20px;
        }

        .equipo-item {
            text-align: center;
        }

        .equipo-item img {
            width: 120px;
            height: 120px;
            object-fit: cover;
            border-radius: 50%;
            border: 3px solid #2e8b57;
            margin-bottom: 10px;
        }

        .equipo-item p {
            font-weight: 500;
            color: #215839;
        }
        

        footer {
            text-align: center;
            padding: 20px;
            background-color: #2e8b57;
            color: white;
            margin-top: 40px;
        }

        ul {
            line-height: 1.6;
        }
    </style>
</head>
<body>

<header>
    <div class="header-container">
        <img src="https://i.postimg.cc/hjMmnzj3/image-removebg-preview.png)](https://postimg.cc/8JJcBCLh)" alt="Árbol" class="header-logo">

        <div class="header-text">
            <h1>Proyecto de Detección de Cadmio</h1>
            <p>Mini Proyecto Igem 2025</p>
        </div>

        <div class="menu-icon" onclick="toggleMenu()">&#9776;</div>
    </div>
</header>

<main>
    <section>
        <h2>Sobre el proyecto</h2>
        <p>En los últimos meses, la preocupación por la presencia de cadmio en alimentos como la palta ha ido en aumento, especialmente tras la detección de este metal en productos importados. El cadmio es un contaminante ambiental silencioso que, al acumularse en el organismo, puede provocar graves efectos en la salud humana.

Este proyecto tiene como objetivo desarrollar métodos químicos y biotecnológicos para detectar la presencia de cadmio en muestras biológicas y ambientales. En particular, se busca implementar biosensores capaces de identificar este metal directamente en plantas, evitando así su comercialización y reduciendo el riesgo para los consumidores.</p>
    </section>

    <section>
        <h2>Objetivo General</h2>
        <ul>
            <li>Desarrollar un sistema biológico basado en biología sintética capaz de detectar la presencia de cadmio en plantas, generando señales visuales que permitan una detección accesible para prevenir riesgos en la salud pública y el medio ambiente</li>
        </ul>
    </section>

    <section>
        <h2>Sobre el Cadmio y sus efectos en la salud</h2>
        <p>El cadmio es un metal pesado clasificado como carcinógeno por la Organización Mundial de la Salud. Su exposición prolongada, incluso en pequeñas cantidades, puede provocar graves daños a la salud humana. Uno de sus principales efectos es el deterioro progresivo de los riñones y el hígado, órganos donde tiende a acumularse sin ser eliminado fácilmente por el cuerpo. Además, puede afectar la densidad ósea, aumentando el riesgo de fracturas, y alterar el sistema respiratorio si se inhala en ambientes contaminados.

A nivel sistémico, el cadmio también está relacionado con un mayor riesgo de enfermedades cardiovasculares, problemas gastrointestinales e incluso trastornos en la reproducción. Su presencia en alimentos es especialmente preocupante porque no se detecta por el sabor, el olor o la apariencia del producto. Por eso, su consumo repetido a lo largo del tiempo representa una amenaza silenciosa para la salud pública, haciendo urgente la implementación de métodos efectivos de detección y control.</p>
        <img src="[![control-de-palta-SENASAG-bolivia-1024x576.jpg](https://i.postimg.cc/FRFZ0QkT/control-de-palta-SENASAG-bolivia-1024x576.jpg)](https://postimg.cc/jW9PrmXf)" alt="Element">
    </section>
    <section id="diseno-genetico">
        <h2>Área de estudio</h2>
        <p> El proyecto se enmarca en el Objetivo de Desarrollo Sostenible (ODS) N.° 12: Producción y consumo responsable. </p>
        <img src="[![descarga.png](https://i.postimg.cc/TwSDh8VC/descarga.png)](https://postimg.cc/hzLj353d)" alt="Elemento Cadmio">
    </section>

    <!-- NUEVAS SECCIONES -->
    <section id="diseno-genetico">
        <h2>Diseño genético y ensamblaje</h2>
        <p> Usamos el plásmido psb2K3 como chasis y de insertos para ensamble usamos GFP y CadR </p>
         <li>Gen CadR: Es un  gen regulador que pertenece a la familia de reguladores de respuesta a metales pesados.
            Está también  involucrado en la detección y respuesta al cadmio (Cd²⁺).</li>
        <li>Gen GFP: El gen GFP es un Gen reportero, gracias a su capacidad de fluorescencia natural. Cuando la proteína GFP se excita con luz UV o azul (~395-475 nm), emite una luz verde visible (~509 nm).
            Esta propiedad permite usarla como marcador visual sin necesidad de añadir reactivos químicos.</li>
        <li>Plásmido psb2k3: Debido a sus cualidades y la facilidad de su uso en Benchling, elegimos este plásmido para las primeras pruebas de ensamblaje.</li>
         <img src="[![im.png](https://i.postimg.cc/pdJC9dr4/im.png)](https://postimg.cc/f3kmpDxf)" alt="Element">

        <h2>Funcionamiento</h2>
        <p>Una vez validado el ensamblaje, el fragmento completo se corta desde pSB2K3 usando enzimas de restricción. Se inserta en un vector binario como pCAMBIA, pBI121, u otro que sí puede funcionar en plantas.</p>
    </section>

    <section id="resultados-esperados">
        <h2>Resultados esperados</h2>
        <li>Construcción de un sistema biológico capaz de detectar cadmio (Cd²⁺) de forma específica.</li>
        <li>El cassette CadR + GFP en pSB2K3 mostrará fluorescencia verde solo en presencia de Cd²⁺.</li>
        <li>Una vez transferido a un vector binario y expresado en plantas → señal luminosa visible ante bajas concentraciones de cadmio.</li>
        <li>La intensidad de la fluorescencia será proporcional a la concentración del metal (uso semi-cuantitativo).</li>
        <li>Herramienta potencial de monitoreo ambiental y alimentario, alineada con los ODS (sostenibilidad y reducción de riesgo sanitario).</li>
    </section>

    <section id="impacto-etico">
        <h2>Impacto ético-social</h2>
        <li>Riesgo de liberar organismos modificados en el ambiente.</li>
        <li>Posibles efectos en biodiversidad y percepción negativa de transgénicos.</li>
        <li>Detección accesible de cadmio en alimentos y agua.</li>
        <li>Contribuye a la salud pública y seguridad alimentaria.</li>
        <li>Útil en comunidades rurales con pocos recursos.</li>
        <li>Requiere educación ambiental y acceso equitativo</li>
    </section>
</main>
 <section id="equipo">
        <h2>Fotos del equipo</h2>
        <p>Presentamos a los integrantes del proyecto:</p>
        <div class="equipo-container">
            <div class="equipo-item">
                <img src="imagenes/rena.jpg" alt="Integrante 1">
                <p>Renata López</p>
            </div>
            <div class="equipo-item">
                <img src="imagenes/fer.webp" alt="Integrante 2">
                <p>Fernanda Solis</p>
            </div>
            <div class="equipo-item">
                <img src="imagenes/notta.jpg" alt="Integrante 3">
                <p>Valentina Notta</p>
            </div>
            <div class="equipo-item">
                <img src="imagenes/Martina.jpg" alt="Integrante 4">
                <p>Martina Bonadona</p>
            </div>
            <div class="equipo-item">
                <img src="imagenes/monte.webp" alt="Integrante 5">
                <p>Camila Montecinos</p>
            </div>
        </div>
    </section>
<footer>
    <p>&copy; 2025 Proyecto de Detección de Cadmio | Biología Digital | Colegio San Agustín Cochabamba 2025</p>
</footer>

</body>

</html>
