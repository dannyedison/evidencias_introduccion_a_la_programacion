<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->
## Actividad: Diseñar un formulario de pedido de un producto

### Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

###  Instrucciones:

1. Crear un nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
    * Nombre del producto
    * Cantidad
    * Precio unitario
    * Precio total
    * Dirección de envío
Información de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
    * Método de pago
    * Fecha de entrega
    * Comentarios
4. Utilizar las etiquetas HTML apropiados para cada campo.

En el ejercicio se utilizaron las herramientas para la creación de formularios vistas en clase.

``` html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formularios</title>
</head>

<body>
    <header>
        <h1>FORMULARIOS</h1>


    </header>
    <main>
        <section>
            <form action="ejemplo.com" method="post" enctype="application/x-www-form-urlencoded">
                <header>
                    <h1>Diligenciar el Formulario</h1>
                </header>
                <div>
                    <label for="idproducto">Nombre Del Producto:</label>
                    <input type="text" name="producto" id="idproducto" placeholder="Nombre Producto">
                </div>
                <br>
                <div>
                    <label for="idcantidad">Catidad:</label>
                    <input type="number" name="cantidad" id="idcantidad" value="0">
                </div>
                <br>
                <div>
                    <label for="idprecio">Precio Unitario:</label>
                    <input type="number" name="precio" id="idprecio" value="0">
                </div>
                <br>
                <div>
                    <label for="idtotal">Precio Total:</label>
                    <input type="number" name="total" id="idtotal" value="0">
                </div>
                <br>
                <div>
                    <label for="iddireccion">Dirección De Envío:</label>
                    <input type="text" name="direccion" id="iddireccion" placeholder="Dirección">
                </div>
                <br>

                <h3>Información De Cotacto</h3>
                <div>
                    <label for="idnombre">Nombre:</label>
                    <input type="text" name="nombre" id="idnombre" placeholder="Nombre">
                </div>
                <br>
                <div>
                    <label for="idmail">Correo Electrónico:</label>
                    <input type="email" name="mail" id="idmail" placeholder="Email">
                </div>
                <br>
                <div>
                    <label for="idphone">Número De Teléfono:</label>
                    <input type="tel" name="phone" id="idphone" placeholder="Teléfono">
                </div>
                <br>

                <h3>Método De Pago</h3>
                <div>
                    <select name="metpago" id="idmetpago" required>
                        <option value="credito">Tarjeta de Crédito</option>
                        <option value="debito">Tarjeta Débito</option>
                        <option value="pse">PSE</option>
                        <option value="pce">Pago Contra Entrega</option>
                    </select>
                </div>
                <br>

                <h3>Fecha de Entrega</h3>
                <div>
                    <label for="idfechaentrega">Fecha de Entrega</label>
                    <input type="datetime-local" name="fechaentrega" id="idfechaentrega" required>
                </div>
                <br>

                <h3>Comentarios</h3>
                <div>
                    <label for="idcomentarios"></label>
                    <textarea name="idcomentarios" cols="40" rows="10" placeholder="Escriba sus Comentarios" maxlength="450"></textarea>
                </div>
                <br>
                <div>
                    <button type="submit" value="Enviar">Enviar</button>
                </div>

            </form>

        </section>
    </main>

    <footer>
        <br>
        <br>
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

``` 





