<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->
## Actividad: Creando mi primer sitio web

Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

* Index o página de inicio
* Acerca
* Contacto

### index.html
Página principal.
Contiene los enlaces a la página de **Acerca** y **Contacto**

``` html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primer sitio web</title>
    <meta name="description" content="Esta página web es sobre la empresa 3D AUTOMATIZACIÓN S.A.S.">
    <meta name="keywords" content="automatizacion, programacion, plc, hmi, suministros electricos">
</head>

<body>

    <header>
        <img src="Logo 3D SAS.png" alt="Logotipo de la empresa">
        <h1>Mi sitio web</h1>
    </header>

    <nav>
        <br>
        <a href="about.html">Acerca</a>
        <a href="contact.html">Contacto</a>
    </nav>

    <main>
        <p>Bienvenidos a <strong>3D AUTOMATIZACIÓN S.A.S</strong> </p>
        <p><span style="color: blue;">Aquí encontraran <i>información</i> sobre nuestros <u>servicios</u></span></p>

        <section>

        </section>

        <h3>Servicios</h3>
        <ul>
            <!-- Lista desordenada ul -->
            <li>Diseño de Planos Eléctricos</li>
            <li>Programación de PLC y HMI</li>
            <li>Suministros Equipos Eléctricos</li>
            <li>Suministros Automatización</li>
            <li>Ensamble de Gabinetes Eléctricos</li>
            <li>Asesorias</li><br>
        </ul>
    </main>

    <footer>
        <p>Copyright 2023 - Danny Idarraga</p>
        <p>dannyedison@gmail.com</p>
    </footer>

</body>

</html>
```

### about.html
Contiene la información e historia sobre la empresa.
Tiene enlace a la página **Inicio** y **Contacto**


``` html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sobre nosotros</title>
</head>

<body>

    <header>
        <img src="Logo 3D SAS.png" alt="Logotipo de la empresa">
        <h1>Sobre nosotros</h1>
        </header>

    <nav>
        <br>
        <a href="index.html">Inicio</a>
        <a href="contact.html">Contacto</a>
    </nav>

    <section>
      <h2>Historia</h2>
      <p>Fundada en 2016 con el propósito de prestar a las empresas los servicios de automatización industrial, suministros</p>
      <p>de materiale y repuestos eléctricos, diseño y ensamble de tableros de control eléctrico.</p><br>
      <p>Contamos con personal capacitado para las labores que la industria necesita para suplir sus necesidades en el </p>
      <p>área de la automatización de procesos industriales.</p><br>

      <article>
        <h3>Misión y Visión</h3>
        <p>Nuestra misión es ...</p><br>
      </article>

    </section>

    <footer>
        <p>Copyright 2023 - Danny Idarraga</p>
        <p>dannyedison@gmail.com</p>
    </footer>
  
</body>

</html>
```

### contact.html
Contiene la información y formulario de contacto con la empresa.
Tiene enlace a la página **Inicio** y **Acerca**

``` html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contacto</title>
</head>

<body>

    <header>
        <img src="Logo 3D SAS.png" alt="Logotipo de la empresa">
        <h1>Contacto</h1>
    </header>

    <nav>
        <br>
        <a href="index.html">Inicio</a>
        <a href="about.html">Acerca</a>
    </nav>

    <main>
      <form>
        <br>
        <label for="nombre">Nombre:</label>
        <input type="text" id="nombre"><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email"><br>
        
        <label for="mensaje">Mensaje:</label>
        <textarea id="mensaje"></textarea><br>

        <input type="submit" value="Enviar">

      </form>

      <aside>
        <h3>Ubicación</h3>
        <p>Avda 38 67-17 Apto 804</p>
        <p>Bello - Antioquia</p>
        <p>604 4474321 - 3113252744</p>
        <a href="mailto:">3dautomatizacion@gmail.com</a><br>

      </aside>

    </main>

    <footer>
      <p>Copyright 2023 - Danny Idarraga</p>
      <p>dannyedison@gmail.com</p>
    </footer>
  
</body>

</html>
```




