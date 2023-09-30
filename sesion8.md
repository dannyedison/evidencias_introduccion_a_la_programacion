<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 

Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

1. Crea el esqueleto de una página web simple con la siguiente estructura:
* Encabezado <header>
* Tres párrafos <p>
* Una imagen <img>
* Un pie de página <footer>

2. Aplica los siguientes estilos usando selectores de etiqueta:
* Color rojo a los encabezados <h1>
* Color azul a los párrafos <p>
* Borde grueso negro a la imagen <img>
* Aplica los siguientes estilos usando seleccionadores de 

3. clase:
* Color verde a los elementos con la clase ".destacado"
* Tamaño de fuente grande a los elementos con la clase ".grande"


4. Aplica los siguientes estilos usando seleccionadores de ID:

* Color amarillo al elemento con ID "#principal"
* Sombra al elemento con ID "#sombras"
* Aplica los siguientes estilos usando seleccionadores 

5. descendientes:
* Color gris a los párrafos dentro de un <div>
* Centrar el contenido de la sección <section>

<!-- Su documentación aquí -->


## index.html

```html

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>La felicidad</title>
  <link rel="stylesheet" href="index.css">

  <title>Etiquetas Multimedia HTML5</title>
  <style>
    body {
      font-family: Arial, sans-serif;
    }

    header {
      background-color: #9a8c8c;
      color: rgb(185, 177, 177);
      padding: 20px;
      text-align: center;
    }

    section h3 {
      text-align: center;
    }

    p {
      color: blue;
    }

    div p {
      color: grey;
      padding: 16px;
      text-align: justify;
    }

    div {
      text-align: center;
    }

    h1 {
      color: rgb(255, 0, 0);
    }

    h3 {
      color: cadetblue;
    }

    #p5 {
      color: white;
    }

    #principal {
      color: yellow;
      text-align: justify;
    }

    #sombras {
      text-shadow: 1px 1px 2px black;
      font-size: 20px;
      text-align: center;
    }

    .destacado {
      font-size: 20px;
      color: green;
    }

    .grande {
      font-size: 40px;
      color: rgb(123, 69, 130);
    }
  </style>
</head>

<body>

  <header>
    <div>
      <h1>La vida es un paisaje</h1>
      <h3 style="color: rgb(5, 92, 121);">Vívela, disfrútala y se feliz</h3>
      <img
        src="https://firebasestorage.googleapis.com/v0/b/imagenes-d40f0.appspot.com/o/road-1072821_640.jpg?alt=media&token=3785fdb6-5130-4f82-bd54-ad3c189d877b&_gl=1*jqpcp8*_ga*MTgzMzU1OTEwNi4xNjk0NzMwNzcx*_ga_CW55HF8NVT*MTY5NTkxNjI5OS4xMi4xLjE2OTU5MTY1NDIuNDQuMC4w"
        alt="imagen" style="border: 10px solid black;">
    </div>
  </header>

  <main>
    <div>
      <h1 style="box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.10);">Es sencillo ser feliz, lo difícil es ser sencillo</h1>
      <img
        src="https://firebasestorage.googleapis.com/v0/b/imagenes-d40f0.appspot.com/o/Paisajes%20y%20Globos.jpg?alt=media&token=f11b447a-50ea-41aa-8800-d4233fff0e06"
        alt="imagen" style="border: 10px solid black;">
      <p id="sombras">Viajar en globo es una experiencia inigualable</p>
    </div>

    <section>
      <h3>¿Qué significa para ti la palabra sencillo? y ¿qué hay de tu concepto de felicidad?</h3>
    </section>

    <p id="principal">
      En estos tiempos donde la autopromoción, la exageración, lo impostado, el vivir
      hacia fuera como lo hacemos en las redes sociales hace que el concepto de persona sencilla, no sea una meta a
      seguir como forma de vida, porque quedarías fuera de la modernidad, el glamur que exige encajar en un mundo
      globalizado, donde las personas parecen valer ya ni siquiera por lo que tiene, si no, por lo que aparentan que
      tienen.</p>

    <h2 style="color: chartreuse; text-align: center;">A veces nos conformamos con aquello que no nos hace feliz</h2>
    <div>
      <p> Por costumbre, por indecisión, por miedo. El corazón
        se oxida y la mente queda cautiva por las alambradas de la zona de confort. Se nos olvida, quizá, que ser feliz
        puede ser muy fácil. Lo complicado es saber dilucidar qué es lo importante, lo más nutritivo y mágico para
        nosotros. Y entonces luchar por ello.
      </p>
    </div>

    <p>
      Tal y como suele decir esa expresión popular:“es tan sencillo ser feliz pero tan difícil ser sencillo…” Pocas
      frases pueden encerrar una verdad tan evidente. Para entenderlo, pensemos en algo durante un momento. A la
      mayoría nos han educado en la idea de que debemos conseguir determinadas cosas para definirnos. Por ejemplo,
      para alcanzar un estatus, para poder tener unas cualidades y unas habilidades adecuadas para un fin.
    </p>

    <p class="destacado">
      Para estar en un estado de felicidad tendríamos primero que saber que es lo que realmente nos causa felicidad y
      hablo no solo de un gozo momentáneo, efímero o peor aún de la idea o creencias que tenemos implantadas de lo que
      creemos que nos causa felicidad. ¿Te ha pasado que obtienes algo que decías que querías con todas tus fuerzas y
      ya que lo obtienes no te da la felicidad que esperabas?, o como cuando añoras eventos o personas de tu pasado y
      que curiosamente los primeros recuerdos que llegan a la mente son los momentos felices y esos bastan para pensar
      que antes eras feliz, o el pasado era mejor, argumento que usamos para seguir queriendo vivir en el pasado.
    </p>

    <p class="grande">
      “La felicidad no reside en las posesiones, ni en el oro, la felicidad habita en el alma”
    </p>
  </main>

  <footer>
    <p id="p5">Copyright 2023 - Danny Idarraga</p>
  </footer>

</body>

</html>

```

## index.css

```html

footer {
    background-color: black;
    text-align: center;
    padding: 40;
}

```

