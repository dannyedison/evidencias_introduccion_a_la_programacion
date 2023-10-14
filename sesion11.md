<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


<!-- Su documentación aquí -->

### Crear un documento HTML y probar cada uno de los ejemplos de la sesión 11

Crea un nuevo archivo HTML y CSS.

### index.html

```html
<!DOCTYPE html>
<html lang="es">
<!---->

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejercicios sesion 11</title>
  <link rel="stylesheet" href="style.css">
</head>

<body>
  <section>
    <div>
    <h1>Ejemplos de la sesion 11</h1>
  </div>
  <div>
    <p>Este es un parrafo donde se aplicaran varias propiedades vistas en la sesión 11</p>
    <img src="https://cdn-icons-png.flaticon.com/512/107/107122.png" alt="">
  </div>
</section>
<br>
<section>
  <div class="enlace">
    <a href="#">Enlace a alguna página</a>
  </div>
</section>
<section>
  <div>
    <p class="pcambio">Cambio de color cuando pase el apuntador</p>
  </div>
</section>
<br>
<section>
  <div>
    <button class="boton">Boton con sombra</button>
  </div>
</section>
</body>

</html>
```

### style.css

```css
body {
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
  background-color: bisque;
}

h1 {
  width: 50%;
  height: 50px;
  margin: 10px auto;
  padding: 50px;
  text-align: center;
  background-color: aqua;
  font: 3em sans-serif;
}

h1::before {
  content: url("https://icons.iconarchive.com/icons/gartoon-team/gartoon-action/48/dialog-apply-icon.png");
}

p {

  float: left;
  width: 500px;
  height: 100px;
  margin: 0px;
  padding: 10px;
  color: rgb(229, 82, 19);
  font: 2em sans-serif;
  font-style: italic;
  text-align: justify;
  border-radius: 10px;
  background-color: aliceblue;
  background-image: url(https://cdn-icons-png.flaticon.com/512/6661/6661565.png);
  background-size: 110px;
}

img {
  width: 100px;
  margin-left: 100px;
  padding: 5px;
  background-color: aquamarine;
}

.enlace{
  
  width: 100%;
  height: 50%;
}

.enlace a {
  color: blue;
  font: 2em sans-serif;
  margin: 100px;

}

.enlace a:link {
  background-color: rgb(203, 162, 162);
}

.enlace a:active {
  background-color: rgb(150, 219, 150);
}

.pcambio{
    background-color: white;
}

.pcambio:hover {
  background-color: rgb(124, 83, 83);
}

.boton{
  margin: 100px;
  width: 10em;
  height: 5em;
  background-image: -moz-linear-gradient(135deg);
  border: none;
  border-radius: 10px;
  font-weight: bold;
  color: rgb(138, 138, 19);
  cursor: pointer;

}
.boton:active{
  box-shadow: 2px 2px 5px #9c3b3b;
}

```





