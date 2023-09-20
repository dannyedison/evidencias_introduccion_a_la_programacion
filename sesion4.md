<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->
## Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

* Código
* Nombre
* Descripción
* Precio
* Stock
* Fecha de creación

En el siguiente ejercicio, se utilisa la combinación de celdas en la tabla, encabezados y etiquetas.

``` html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Actividad 4</title>
</head>

<body>
    <header>
        <h1>TABLA INVENTARIO EQUIPOS MÓVILES</h1>
        <nav>

        </nav>
    </header>

    <main>
        <section>
            <table border="2" cellpadding="5" cellspacing="10">
                <thead>
                    <tr>
                        <th>Código</th>
                        <th>Nombre</th>
                        <th>Descripción</th>
                        <th>Precio</th>
                        <th>Stock</th>
                        <th>Fecha de creación</th>
                    </tr>
                </thead>

                <tbody>
                    <tr>
                        <td rowspan="2">0001</td>
                        <td rowspan="2">iPhone 14 Pro Max</td>
                        <td>El iPhone 14 Pro Max es el smartphone más potente del mercado. Cuenta con una pantalla OLED
                            de 6,7 pulgadas, un procesador A16 Bionic y un sistema de cámaras de 48 megapixeles</td>
                        <td>4.899.000 COP</td>
                        <td>10</td>
                        <td>2022-09-21</td>
                    </tr>
                    <tr>
                        <td>El iPhone 14 Pro Max está disponible en cuatro colores: grafíto, plata, oro y sierra</td>
                        <td>100</td>
                    </tr>

                    <tr>
                        <td rowspan="2">0002</td>
                        <td rowspan="2"> MacBook Pro M2 Pro</td>
                        <td>El MacBook Pro M2 Pro es el nuevo portatil profesional de Apple. Cuenta con el procesador M2
                            Pro, una pantalla Liquid Retina XDR y un sistema de cámaras TrueDepth con cámara FaceTime HD
                        </td>
                        <td>10.499.000 COP</td>
                        <td>10</td>
                        <td>2022-06-06</td>
                    </tr>
                    <tr>
                        <td>El MacBook está disponible en dos colores: gris espacial y plata</td>
                        <td>75</td>
                    </tr>

                    <tr>
                        <td rowspan="2">0010</td>
                        <td rowspan="2">Nintendo Switch OLED</td>
                        <td>La Nintendo Switch OLED es la versión mejorada de la consola Nintendo Switch. Cuenta con una
                            pantalla OLED de 7 pulgadas, más almacenamiento y un soporte ajustable.</td>
                        <td>1.099.000 COP</td>
                        <td>10</td>
                        <td>2021-10-08</td>
                    </tr>
                    <tr>
                        <td>La Nintendo Switch OLED está disponible en dos colores: blanco y negro</td>
                        <td>75</td>
                    </tr>

                    <tr>
                        <td rowspan="2">0011</td>
                        <td rowspan="2">Redmi Note 12 Pro Plus 5g</td>
                        <td>Cámara de 200 MP líder en el mundo con OIS, Carga HyperCharge de 120 W, Pantalla AMOLED de
                            120 Hz.</td>
                        <td>1.399.000 COP</td>
                        <td>14</td>
                        <td>2023-10-08</td>
                    </tr>
                    <tr>
                        <td>El Redmi Note 12 Pro Plus 5g está disponible en tres colores: blanco polar, negro media
                            noche y azul cielo</td>
                        <td>65</td>
                    </tr>

                    <tr>
                        <td rowspan="2">0012</td>
                        <td rowspan="2">Poco X5 Pro 5G </td>
                        <td>Dual SIM 256 y 8 GB RAM, Cámara principal de 108 MP, Carga de de y bateria de 5000mA,
                            Pantalla AMOLED de 6.67" 120 Hz.</td>
                        <td>1.219.900 COP</td>
                        <td>9</td>
                        <td>2023-02-08</td>
                    </tr>
                    <tr>
                        <td>El Poco X5 Pro 5G está disponible en tres colores: negro, amarillo y azul</td>
                        <td>65</td>
                    </tr>

                    <tr>
                        <td rowspan="2">0013</td>
                        <td rowspan="2">Samsung Galaxy S21 FE 5G (Exynos) 5G </td>
                        <td>Dual SIM 256 GB lavender 8 GB RAM, Cámara principal de 12 MP, bateria de 4500mA, Pantalla
                            AMOLED de 6.4".</td>
                        <td>2.421.900 COP</td>
                        <td>12</td>
                        <td>2023-04-20</td>
                    </tr>
                    <tr>
                        <td>Samsung Galaxy S21 FE 5G está disponible en tres colores: grafito, lavanda y olivo</td>
                        <td>70</td>
                    </tr>

                    <tr>
                        <td rowspan="2">0014</td>
                        <td rowspan="2">Samsung Galaxy S21 Ultra 5g </td>
                        <td>Almacenamiento de 128 GB y 12 GB RAM, Cámara principal de 108 MP, bateria de 5000mA,
                            Pantalla AMOLED de 6.8" 120 Hz.</td>
                        <td>4.299.900 COP</td>
                        <td>5</td>
                        <td>2023-03-10</td>
                    </tr>
                    <tr>
                        <td>El Samsung Galaxy S21 Ultra 5G está disponible en dos colores: Phantom Silvef, Phantom black
                        </td>
                        <td>50</td>
                    </tr>

                    <tr>
                        <td rowspan="2">0015</td>
                        <td rowspan="2">Honor X8 </td>
                        <td>Dual SIM 128 GB y 6 GB RAM, Cámara principal de 64 MP, Carga de de y bateria de 4000mA,
                            Pantalla de 6.7".</td>
                        <td>1.138.900 COP</td>
                        <td>9</td>
                        <td>2023-03-05</td>
                    </tr>
                    <tr>
                        <td>El Honor está disponible en un color: plata sideral</td>
                        <td>66</td>
                    </tr>

                    <tr>
                        <td rowspan="2">0016</td>
                        <td rowspan="2">Poco F5 5G</td>
                        <td>Dual SIM 256 y 12 GB RAM, Cámara principal de 64 MP, Carga de de y bateria de 5000mA,
                            Pantalla AMOLED de 6.67".</td>
                        <td>1.649.900 COP</td>
                        <td>10</td>
                        <td>2023-03-08</td>
                    </tr>
                    <tr>
                        <td>El Poco F5 5G está disponible en tres colores: negro, azul y blanco</td>
                        <td>70</td>
                    </tr>

                    <tr>
                        <td rowspan="2">0017</td>
                        <td rowspan="2">Xiaomi 12 </td>
                        <td>Dual SIM 256 y 8 GB RAM, Cámara principal de 50 MP, Carga de de y bateria de 4500mA,
                            Pantalla AMOLED de 6.28".</td>
                        <td>1.949.900 COP</td>
                        <td>9</td>
                        <td>2023-02-08</td>
                    </tr>
                    <tr>
                        <td>El Xiaomi 12 está disponible en tres colores: azul, gris y púrpura</td>
                        <td>65</td>
                    </tr>

                </tbody>
            </table>
        </section>

    </main>
    <footer>

    </footer>
</body>

</html>
```


