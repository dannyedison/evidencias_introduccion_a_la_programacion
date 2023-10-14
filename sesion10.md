<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->


### Propiedades de posicionamiento de CSS.

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, crea una estructura básica de página web con dos elementos div.
En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

### index.html

```html
<!DOCTYPE html>
<html lang="es">
    <!---->
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>POSicionamiento en ccs</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <section>
    <h1>Elementos Posicionemiento</h1>
  <div class="elemento1">Posicionemiento absoluto</div>
  <div class="elemento2">Posicionemiento relativo</div>
</section>

<section class="display">
  <h2>Elementos Display</h2>
  <div class="elemento3">En bloque</div>
  <span class="elemento4">En linea</span>
  <div class="elemento5">Ancho y altura definido</div>
</section>
</body>
</html>    
```

### style.css

```css
.elemento1 {
  position: absolute;
  top: 50px;
  left: 20px;
  width: 200px;
  height: 200px;
  background-color:blue;
}

.elemento2 {
  position: relative;
  top: 50px;
  left: 50px;
  width: 100px;
  height: 100px;
  background-color: green;
}

.display{
  margin-top: 300px;
}
.elemento3 {
  display: block;
  width: 200px;
  height: 100px;
  background-color: red;
}

.elemento4 {
  display: inline;
  width: 200px;
  height: 100px;
  background-color: violet;
}

.elemento5 {
  display: inline-block;
  width: 200px;
  height: 100px;
  background-color: yellow;
}

```

## Preguntas

1. ¿Cuál es la diferencia entre los valores position: absolute y position: relative?
    * En la posición absolute, el elemento se coloca en una posición específica en la página, independientemente del flujo normal del documento, mientras que en la posición relative el elemento se desplaza desde su posición original en el flujo normal del documento hasta la posicion deseada.
2. ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
    * Cuando varios elementos se superponen, se usa la prpiedad z-index, donde según el valor de menor a mayor, se da el orden en que los elementos serán mostrados.

El valor de z-index puede ser un número entero positivo o negativo. Un valor de z-index de 0 significa que el elemento se comporta de forma normal.
3. ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?
    * La propiedad display permite el ordenamiento de los elementos para ser mostrados en:

        -   block: Donde los elementos ocupan toda la anchura de su contenedor y se muestran individualmente en una nueva línea (columna). 
        -   inline: Los elemento se muestran como una caja de línea, que se muestra en la misma línea que el texto circundante (fila).
        -   inline-block: Los elementos se muestran como una caja en línea, pero puede tener una anchura y una altura definidas individualmente.
        -   none: El elemento no se muestra en la página web.
