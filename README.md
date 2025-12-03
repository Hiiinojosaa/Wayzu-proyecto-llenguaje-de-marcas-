WAYZU

Este proyecto consiste básicamente en una Landing que ofrece paquetes de viajes con vuelo, hotel y activiades. 
Su funciones son principalmente informar sobre los servicios y establecer un negocio online (estatico).

El proyecto no es instalable y solo puede visualizarse de forma privada mediante una dirección IP específica.
Si necesitas acceso, puedes copiar esta carpeta y abrirla en Visual Studio Code.

DESCARGA:
https://code.visualstudio.com/download

HOME
- Pricipalmente tenemos un HEADER en el que incluimos WAYZU (que siempre nos redirecciona a HOME, asi que aquí en esta página no hará nada)
DESTINOS-NOSOTROS-CONTACTO (estos tres botonoes llevan al mismo sitio, una ventana en la que incluimos los destinos mas populares, una breve descripción de la empresa y unos datos de contacto más especificos)
- Tenemos un desplegable para seleccionar el destino deseado-disponible.
- Un botón que dice "viaje a ciega", este botón nos lleva a una ventana específica y esta creado para esas personas aventureras.
- Un botón que dice RESERVAR, el cual siempre que aparezca va a mostrar nuestra tarjeta de contacto.

Tecnologías Utilizadas: Lenguaje o framework (FIGMA)


Herramientas utilizadas
<img src= → Código imágenes + LINK

<link href= → Código fuente + LINK ["https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;500;700;800&display=swap" rel="stylesheet"]

<script>
        const btnBuscar = document.getElementById('buscar-btn');
        const menu = document.getElementById('destinos-menu');

        btnBuscar.addEventListener('click', () => {
            menu.classList.toggle('show');
        });

        document.addEventListener('click', (e) => {
            if (!btnBuscar.contains(e.target) && !menu.contains(e.target)) {
                menu.classList.remove('show');
            }
        });
    </script>

👤 Autor

Luis Ruiz Hinojosa
