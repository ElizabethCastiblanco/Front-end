# Front-end
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        /* Estilo para el rectángulo */
        
        .rectangulo {
            width: 1885px;
            height: 50px;
            background-color: #db343f;
            border: 2px solid #db343f;
            margin-top: 20px;
            /* Espacio superior para separar del h1 */
            flex-direction: column;
            /* Colocar botones en columna */
            justify-content: flex-start;
            /* Alinear al inicio verticalmente */
            align-items: flex-start;
            /* Alinear al inicio horizontalmente */
        }
        /* Estilo para los botones */
        
        .rectangulo button {
            width: 200px;
            /* Ancho de los botones */
            height: 45px;
            margin-left: 10px;
            /* Espacio entre los botones */
        }
        
        .container {
            display: flex;
            align-items: center;
            /* Alinear verticalmente al centro */
        }
        /* Estilo para la imagen */
        
        .container img {
            width: 100px;
            /* Ancho de la imagen */
            margin-right: 10px;
            /* Espacio entre la imagen y el texto */
        }
        /* Estilo para la barra de búsqueda */
        
        .search-bar {
            width: 500px;
            /* Ancho de la barra de búsqueda */
            padding: 5px;
            /* Espaciado interno */
            border: 1px solid #ccc;
            /* Borde de la barra de búsqueda */
        }
        /* Estilo para el encabezado */
        
        h1 {
            margin: 0 330px 0 0;
            /* Eliminar margen superior e inferior del encabezado */
        }
        /* Estilo para las imágenes adicionales */
        
        .extra-images img {
            width: 50px;
            /* Ancho de las imágenes adicionales */
            margin-right: 10px;
            /* Espacio entre las imágenes */
        }
        /* Estilo para el rectángulo */
        
        .rectangulo1 {
            width: 1885px;
            height: 1500px;
            background-color: #db343f;
            border: 2px solid #010101;
            margin-top: 20px;
            /* Espacio superior para separar del h1 */
            flex-direction: column;
            /* Colocar botones en columna */
            justify-content: flex-start;
            /* Alinear al inicio verticalmente */
            align-items: flex-start;
            /* Alinear al inicio horizontalmente */
        }
        
        .rectangulo1 img {
            width: 200px;
            /* Ancho de las imágenes */
            margin: 15px;
            /* Espacio entre las imágenes */
        }
        /* Estilo para centrar las imágenes horizontalmente */
        
        .rectangulo2 {
            width: 1885px;
            height: 150px;
            background-color: #ffffff;
            border: 2px solid #ffffff;
            margin-top: 20px;
            /* Espacio superior para separar del h1 */
            flex-direction: column;
            /* Colocar botones en columna */
            justify-content: flex-start;
            /* Alinear al inicio verticalmente */
            align-items: flex-start;
            /* Alinear al inicio horizontalmente */
        }
        
        .rectangulo2 img {
            width: 80px;
            /* Ancho de las imágenes */
            margin: 20px;
            /* Espacio entre las imágenes */
        }
        /* Estilo para centrar las imágenes horizontalmente */
        
        .container1 {
            display: flex;
            align-items: center;
            /* Alinear verticalmente al centro */
        }
        /* Estilo para la imagen */
        
        .container1 img {
            width: 50px;
            /* Ancho de la imagen */
            margin-right: 10px;
            /* Espacio entre la imagen y el texto */
        }
        
        .container2 {
            display: flex;
            align-items: center;
            /* Alinear verticalmente al centro */
        }
        /* Estilo para la imagen */
        
        .container2 img {
            width: 50px;
            /* Ancho de la imagen */
            margin-right: 10px;
            /* Espacio entre la imagen y el texto */
        }
        
        .medios de pago {
            width: 50px;
            /* Ancho de las imágenes adicionales */
            margin-right: 10px;
            /* Espacio entre las imágenes */
        }
        
        .suscribirse {
            width: 400px;
            /* Ancho de los botones */
            height: 45px;
            margin-left: 280px;
            /* Espacio entre los botones */
        }
        
        .rectangulo1 button {
            width: 100px;
            /* Ancho de los botones */
            height: 45px;
            margin-left: 10px;
            /* Espacio entre los botones */
            display: block;
        }
        /* Estilo para el contenedor derecho */
        
        .contenedor-derecho {
            float: left;
            /* Alinea a la derecha */
            width: 300px;
            /* Establece el ancho del contenedor */
            margin-left: 250px;
            /* Agrega un margen izquierdo para separarlo del contenido principal */
        }
        /* Estilo para las imágenes dentro del contenedor */
        
        .contenedor-derecho img {
            width: 200px;
            /* Establece el ancho de las imágenes */
            margin-bottom: 10px;
            /* Agrega espacio entre las imágenes */
        }
        /* Estilo para el texto dentro del contenedor */
        
        .contenedor-derecho p {
            margin: 0;
            /* Elimina el margen predeterminado de los párrafos */
            font-size: 14px;
            /* Tamaño de fuente para el texto */
            color: #fff;
            /* Cambia el color del texto a blanco */
        }
        
        .contenedor-derecho1 {
            float: left;
            /* Alinea a la derecha */
            width: 300px;
            /* Establece el ancho del contenedor */
            margin-left: 10px;
            /* Agrega un margen izquierdo para separarlo del contenido principal */
        }
        /* Estilo para las imágenes dentro del contenedor */
        
        .contenedor-derecho1 img {
            width: 200px;
            /* Establece el ancho de las imágenes */
            margin-bottom: 10px;
            /* Agrega espacio entre las imágenes */
        }
        /* Estilo para el texto dentro del contenedor */
        
        .contenedor-derecho1 p {
            margin: 0;
            /* Elimina el margen predeterminado de los párrafos */
            font-size: 14px;
            /* Tamaño de fuente para el texto */
            color: #fff;
            /* Cambia el color del texto a blanco */
        }
        
        .contenedor-derecho2 {
            float: left;
            /* Alinea a la derecha */
            width: 300px;
            /* Establece el ancho del contenedor */
            margin-left: 10px;
            /* Agrega un margen izquierdo para separarlo del contenido principal */
        }
        /* Estilo para las imágenes dentro del contenedor */
        
        .contenedor-derecho2 img {
            width: 200px;
            /* Establece el ancho de las imágenes */
            margin-bottom: 10px;
            /* Agrega espacio entre las imágenes */
        }
        /* Estilo para el texto dentro del contenedor */
        
        .contenedor-derecho2 p {
            margin: 0;
            /* Elimina el margen predeterminado de los párrafos */
            font-size: 14px;
            /* Tamaño de fuente para el texto */
            color: #fff;
            /* Cambia el color del texto a blanco */
        }
        
        .contenedor-derecho3 {
            float: left;
            /* Alinea a la derecha */
            width: 300px;
            /* Establece el ancho del contenedor */
            margin-left: 10px;
            /* Agrega un margen izquierdo para separarlo del contenido principal */
        }
        /* Estilo para las imágenes dentro del contenedor */
        
        .contenedor-derecho3 img {
            width: 200px;
            /* Establece el ancho de las imágenes */
            margin-bottom: 10px;
            /* Agrega espacio entre las imágenes */
        }
        /* Estilo para el texto dentro del contenedor */
        
        .contenedor-derecho3 p {
            margin: 0;
            /* Elimina el margen predeterminado de los párrafos */
            font-size: 14px;
            /* Tamaño de fuente para el texto */
            color: #fff;
            /* Cambia el color del texto a blanco */
        }
        
    </style>
</head>

<body>

    <div class="container">
        <img src="fresa.jpg" alt="Imagen de Ecomarket" width="30">
        <h1>Ecomarket Salud y bienestar</h1>
        <input type="text" class="search-bar" placeholder="Buscar...">
        <div class="extra-images">
            <img src="compras.jpg" alt="compras" width="80">
            <img src="usuario.jpg" alt="usuario" width="80">
            <img src="pagos.jpg" alt="pagos" width="80">
            <img src="inicio.jpg" alt="inicio" width="80">

        </div>

    </div>

    <div class="rectangulo">
        <button>Categorías</button>
        <button>Ofertas</button>
    </div>

    <div class="rectangulo1">
        <!-- Imágenes en rectangulo1 -->
        <img src="carnes.jpg" alt="carnes">
        <img src="arroz.jpg" alt="arroz">
        <img src="frutas.jpg" alt="frutas">
        <img src="leches.jpg" alt="leches">
        <img src="pan.jpg" alt="pan">
        <img src="aceites.jpg" alt="aceites">
        <img src="gaseosas.jpg" alt="gaseosas">
        <img src="detergentes.jpg" alt="detergentes">
        <h1>Filtros</h1>
        <h2>Filtrado por</h2>


        <div class="rectangulo button">
            <h3>Categorías</h3>
            <button>Frutas</button>
            <button>Verduras</button>
            <button>Lacteos</button>
            <button>Carnes</button>
            <button>Aseo personal</button>
            <button>Viveres y abarrotes</button>
            <button>Otros</button>
            

            <h3>Marcas</h3>
            <button>Primavera</button>
            <button>Alpina</button>
            <button>Roa</button>
            <button>La Fazenda</button>
            <button>Colanta</button>
            <button>La Granja</button>
            <button>Otros</button>

            <h3>Tipo de producto</h3>
            <button>Manzana</button>
            <button>Arroz</button>
            <button>Banano</button>
            <button>Pollo</button>
            <button>Cerdo</button>
            <button>Salchicas</button>
            <button>Otros</button>

        </div>

        <div class="contenedor-derecho">
            <img src="huevos.jpg" alt="Huevo campesino AA">
            <p> Precio: $600 Und.</p>
            <p> Cantidad: 30 Und.</p>
            <p> Total: 18.000 </p>

            <img src="aceiteo.jpg" alt="Aceite de oliva">
            <p>Precio: $8550 / 1000 ml.</p>
            <p>Cantidad: 1 Und.</p>
            <p>Total: $8.550 </p>

            <img src="manzana.jpg" alt="Manzana Roja">
            <p>Precio: $2250 Und.</p>
            <p>Cantidad: 10 Und.</p>
            <p>Total: $22.500 </p>

       
        
        </div>
        
    </div>
