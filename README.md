
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.2/jquery.min.js"></script>
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap.min.css">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/css/bootstrap-theme.min.css">
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.1/js/bootstrap.min.js"></script>

    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.cdnfonts.com/css/project-space" rel="stylesheet">
                
    <title>Inicio</title>
</head>
<body>
    <div style="margin: 24px;">
        <nav class="navbar navbar-inverse navbar-stick-static-top">
            <div class="container">
                <ul class="nav navbar-nav">
                    <li>
                        <a href="index.html">inicio</a>
                    </li>
                    <li>
                        <a href="menu.html">menu</a>
                    </li>
                    <li>
                        <li class="active">
                        <a href="pedido.html">pedido</a>
                    </li>
                    <li>
                        <a href="contacto.html">contacto</a>
                    </li>
                </ul>
            </div>
         </nav>
    </div>
    <titulo1>pedido</titulo1><br>


    <form action="pedidorealizado.html" method="get">
<p>Nombre: <input type="text" id="nombre" name="Nombre" size="30"></p>
<p>Apellido: <input type="text" id="Apellido" name="Apellido" size="30"></p>
<p>Telefono: <input type="text" id="Telefono" name="Telefono" size="20"></p>
<p>Direccion: <input type="text" id="Direccion" name="Direccion" size="30"></p>    
<p>Colonia: <input type="text" id="Colonia" name="Colonia" size="30"></p>
<p>Sexo: <input type="radio" name="sexo" value="hombre">hombre
      <input type="radio" name="sexo" value="mujer">mujer</p>  

        <input type="submit"value="enviar">

        <input type="reset"value="borrar">
         
    </form>
</body>
</html>
