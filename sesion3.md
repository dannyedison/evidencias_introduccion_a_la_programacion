<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->
## Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

* 4 Imagenes
* 2 Videos
* 4 Audios
* 2 Inline Frame

En el código HTML se incluyen la mayoría de las etiquetas herramientas vistas en clase.

``` html
<!DOCTYPE html>
<html>

<!--atributos CSS-->
<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #400d0d;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(44, 44, 105);
        }

        footer {
            background-color: #262424;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
        
    </header>

    <section>
        <h2>Imágenes Autos Deportivos</h2>
        <h3> <span style="color: red;"> AUDI R8 COUPE </span></h3>
        <p>El súper deportivo <strong>Audi R8 Coupé V10 Plus</strong> tiene un potente motor V10 de 5.2 litros y 610 caballos de potencia. <br>
            Este vehículo es producido en la fábrica de Neckarsulum, Alemania, con la participación de 241 especialistas que miden y ensamblan cada pieza a mano.   <a href="https://www.elcarrocolombiano.com/lanzamientos/audi-r8-coupe-v10-plus-caracteristicas-y-precio-en-colombia/" target="_blank">Mas información</a></p>
            
            <img src="AUDI-R8-COUPE.jpg" alt="Audi AUDI-R8-COUPE" width="300"> 

        <h3> <span style="color: rgb(142, 139, 139);"> CORVETTE Z06 </span></h3>
        <p>La esperada versión potenciada del <strong>Corvette C8</strong> de motor central llega con un motor V8 5.5 l de cigüeñal plano que garantizará un sonido más intenso. <br>
            <u>Con sus 679 CV y 623 Nm</u>, mejoras a nivel aerodinámico y de chasis será la gran apuesta de Chevrolet para batir a los superdeportivos europeos.  <a href="https://www.caranddriver.com/es/coches/novedades/a30627829/corvette-c8-z06/" target="_blank">Mas información</a></p>
            
            <img src="Corvette-Z06.jpg" alt="chevrolet Corvette-Z06" width="300">

        <h3> <span style="color: red;"> FERRARI 488 PISTA </span></h3>
        <p>Ferrari ha concebido el 488 Pista para llevar a la calle todo lo que ha aprendido en los circuitos. Para ello ha cogido como base al modelo central de su gama y le ha aplicado todo lo aprendido en el Mundial de Resistencia y en las copas monomarca de la firma de Maranello. <br>
             <i>El resultado es un biplaza deportivo con 90 kilos menos (se queda en solo 1.280), 50 caballos más de potencia para plantarse nada menos que en 720 caballos y mejoras aerodinámicas que hacen al <strong>Ferrari 488 Pista</strong> digno del calificativo de súper deportivo.</i>    <a href="https://www.marca.com/motor/salon-ginebra/2018/02/20/5a8c0c65468aebd55f8b4605.html" target="_blank">Mas información</a></p>
           
            <img src="ferrari-488.jpg" alt="Ferrari 488 Pista" width="300">

        <h3> <span style="color: rgb(91, 87, 87);"> MUSTAG DARK </span></h3>
        <p>Ubicado en la cima de la nueva familia <strong>Ford Mustang,</strong> esta versión cuenta con la mayor capacidad de pista jamás vista y un motor V8 de 5.0 litros. <br> <u>
            También cuenta con cuerpos de aceleración duales y lo proyecta para alcanzar 500 hp.</u>   <a href="https://www.elcarrocolombiano.com/autos-del-mundo/ford-mustang-dark-horse-2024-una-autentica-bestia-de-carreras-para-ir-a-otro-nivel/" target="_blank">Mas información</a></p>
            
            <img src="MustangDark.jpg" alt="Mustang Dark" width="300">

    </section>

    <section>
        <h2>Videos</h2>
        <h3>Auto Derportivo BMW</h3>
        <p>Video auto deportivo BMW blanco</p>
        <video src="Video1.mp4"controls width="300"> </video> 

        <h3>Auto Derportivo rojo</h3>
        <p>Video de auto deportivo rojo</p>
        <video src="Video2.mp4#t=2,5"controls width="300"> </video> 
        <div>
            <p><strong><i>Etiqueta con control de inicio de reproducción: #t=2,5 (inicia en el segundo 2 y termina en el segundo 5)</i></strong></p>
        </div>

    </section>

    <section>
        <h2>Audios</h2>
        <h3>Música para conducir</h3>

        <h4>Si quiero algo para alta velocidad</h4>
        <audio src="lady-of-the-80x27s-128379.mp3" controls></audio>
        <br>
        <h4>Si quiero algo rockerito</h4>
        <audio src="stylish-rock-beat-trailer-116346.mp3" controls></audio>
        <br>
        <h4>Si quiero algo para disfrutar la ruta</h4>
        <audio src="lofi-chill-medium-version-159456.mp3" controls></audio>
        <br>
        <h4>Para el regreso a casa</h4>
        <audio src="easy-lifestyle-137766.mp3" controls></audio>

    </section>

    <section>
        <h2>iFrames</h2>
        <h3><strong>Los mejores carros deportivos del 2022</strong></h3>
        <iframe width="800" height="400" src="https://es.digitaltrends.com/autos/carros-deportivos/" frameborder="0"
        ></iframe>
        <br>
        <br>
        <br>
        <br>
        <br>
        <h3><strong>¿Donde comprar autos deportivos en Colombia?</strong></h3>
        <iframe width="800" height="400" src="https://revistadiners.com.co/tendencias/autos-motos/68092_donde-comprar-autos-deportivos-colombia/" frameborder="0"
            ></iframe>

    </section>

    <footer>
        <strong>DANNY EDISON IDARRAGA</strong> <br> <br>
        INTRODUCCIÓN A LA PROGRAMACIÓN <br>
        JUEVES EN LA NOCHE
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```





