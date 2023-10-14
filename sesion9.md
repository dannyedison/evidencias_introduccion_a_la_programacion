<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->

### Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

Crea un nuevo archivo HTML y CSS.

### index.html

```html
<!DOCTYPE html>
<html lang="es">
    <!---->
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
  
</body>
</html>  
```

### style.css

```css
.contenedor {
    
    width: 200px;
    height: 200px;
    background-color:crimson;
  }
  
  .elemento {
    border-radius: 50%;
    border: 10px solid blue;
    padding: 20px;
    margin: 10px;
    width: 25px;
    height: 50%;
    background-color: blueviolet;
  }

```

## Preguntas

1. ¿Qué es la propiedad margin?
    * Es la propiedad que establece el margen para los cuatro lados. Es una abreviación para evitar tener que establecer cada lado por separado con las otras propiedades de margen: margin-top (en-US), margin-right , margin-bottom y margin-left (en-US).
2. ¿Qué es la propiedad padding?
    * La propiedad padding es la que crea el espacio o área alrededor del contenido de un elemento. Consiste en el relleno superior, derecho, inferior e izquierdo. En CSS se escriben como padding-top:, padding-right:, padding-bottom: y padding-left:. Sus valores por defecto son 0.
3. ¿Qué es la propiedad border?
    * La propiedad border permite definir en una única regla todos los bordes de los elementos seleccionados. Se puede utilizar border para definir el o los valores siguientes: border-width , border-style , border-color . 
4. ¿Qué es la propiedad border-radius?
    * La propiedad CSS border-radius permite definir qué tan redondeadas serán las esquinas. La redondez de cada esquina está definida usando uno o dos valores para el radio que define su forma dependiendo si es un círculo (50%) o una elipse.
5. ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?
    * Unidades de medida absolutas
Las unidades de medida en CSS de tipo absoluto hacen referencia a las unidades que no cambian, esas que en todos lo contextos son iguales. En CSS, existen siete unidades de medida absolutas, te las presentamos a continuación:

        * in: hace referencia a las pulgadas, que son iguales a 2.54cm.
        * cm: se refiere a los centímetros.
        * mm: hace referencia a los milímetros.
        * q: se refiere a un cuarto de la unidad mm. 1q=0.248mm.
        * pt: un punto es igual a 1/72 de una pulgada o 0.35mm.
        * pc: una pica es igual a 12 puntos, o sea 4.23mm.
        * px: esta etiqueta se refiere a los píxeles que, aunque son absolutos (0.26mm), también son relativos a la densidad de la pantalla. 

    * Unidades de medida relativas
Las unidades de medida en CSS de tipo relativo dependen del elemento o factor al que hagan referencia. Aunque pueden ser inicialmente más complejas, algunos prefieren las unidades de medidas de css relativas porque los tamaños de los elementos dependen el uno del otro. Esto hace que las proporciones entre los elementos se mantengan y todo encaje.
        * em
Esta unidad es relativa al tamaño de letra o font size establecida en el navegador. Su nombre es em porque el tamaño de letra se basa en el tamaño de la letra eme. A menos que haya sido modificada por el usuario, normalmente este tamaño es de 16px.
        * ex
Esta unidad es relativa a la altura de la «x» del elemento. También se conoce por ser más o menos la mitad del tamaño de la fuente del navegador o 0.5em.
        * ch
Conocido en inglés como zero width, esta unidad de medida es relativa al tamaño del ancho del cero en la fuente del navegador.
        * %
Esta unidad es relativa al tamaño del elemento padre.
        * rem
La unidad rem o root em es similar a la unidad em, pero, en vez de tomar como base el tamaño de letra del navegador, la unidad em toma el tamaño base del documento HTML. Este tamaño se personaliza bajo la etiqueta :root {font-size}. De este modo, podemos usar rem para dimensionar nuestros elementos con un múltiplo del tamaño base.

            Esta unidad puede ser muy útil a la hora de dimensionar una página cuando el usuario hace zoom, pues los elementos serán relativos unos a otros y mantendrán su proporción. Esta es una unidad de medida comúnmente utilizada para el tamaño de fuente en css

    * Unidades del viewport
Las siguientes unidades son relativas al viewport, que es el espacio o trozo de pantalla donde se renderiza y se muestra la página web. Estas unidades sirven para dimensionar la pantalla y organizar los elementos dentro de esta.
        * vw
Como sigla de la unidad en inglés viewport width, esta unidad es relativa al ancho del viewport.
        * vh
Como sigla de la unidad en inglés viewport height, esta unidad es relativa a la altura del viewport.
        * vmin
Esta unidad vmin css , también conocida como viewport minimum, es relativa al factor que sea más pequeño entre el ancho y al alto del viewport.

        * vmax
Esta unidad, conocida como viewport maximum, es relativa al factor que sea más grande entre el ancho y el alto del viewport. Junto con vmin, esta unidad puede ser muy útil si queremos que nuestros diseños sean flexibles y se adapten al tamaño visible de la página web.
