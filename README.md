<DOCTYPE html>
<html lang="es">
<head>
     <meta charset="UTF-8">
     <title>Formulario Simple</title>
</head>
<body>
     <h2>Formulario de contacto</h2>

     <form action="procesar.php" method="post">
         <!--Nombre-->
         <label for="nombre" title="ingrese su nombre">Nombre:</label>
         <input type="text" id="nombre" name="nombre" required>
         <br><br>

         <!--Apellido-->
         <label for="apellido" title="ingrese su apellido">Apellido:</label>
         <input type="text" id="apellido" name="apellido" required>
         <br><br>

         <!--Correo-->
         <label for="correo" title="ingrese su correo">Correo:</label>
         <input type="text" id="correo" name="correo" required>
         <br><br>

         <!--Password-->
         <label for="password" title="ingrese su contraseña">Password:</label>
         <input type="password" password="password" name="password" required>
         <br><br>


         <!--Fecha-->
         <label for="fecha">Fecha:</label>
         <input type="text" id="fecha" name="fecha" Readonly>
         <br><br>

         <!--Edad-->
         <label for="edad" title="ingrese su edad">Edad:</label>
         <input type="text" id="edad" name="edad" maxlength="2" required>
         <br><br>

         <!--País-->
         <label for="país">Seleccionar su País:</label>
          <select name= "País"> id="pais"
         <option disabled></option>
         <option label="Ecuador"selected>Ecuador</option>
         <option label="Brasil">Brasil</option>
         <option label="Perú">Perú</option>
         <option label="Colombia">Colombia</option>
         </select>
         <br><br>

         <!--Provincia-->
         <label for="Seleccione">Seleccionar su provincia:</label>
          <select name= "provincia">
         <option select></option>
         <option disabled></option>
         <option label="Esmeraldas"selected>Esmeraldas</option>
         <option label="Guayas">Guayas</option>
         <option label="Manabi">Manabi</option>
         <option label="Los Rios">Los Rios</option>
         </select>
         <br><br>

         <!--Cantón-->
         <label for="Seleccione">Seleccionar su cantón:</label>
          <select name= "cantón">
         <option select></option>
         <option disabled></option>
         <option label="Atacames"selected>Atacames</option>
         <option label="Muisne">Muisne</option>
         <option label="Quinindé">Quinidé</option>
         <option label="Esmeraldas">Esmeraldas</option>
         </select>
         <br><br>

         <!--Género-->
         <label>Seleccione tu género:</label><br><br>
         
         <input type="radio" id="masculino" name="genero" value="masculino" checked>
         <label for="masculino">Masculino</label><br><br>

         <input type="radio" id="femenino" name="genero" value="femenino" checked>
         <label for="femenino">Femenino</label><br><br>

         <input type="radio" id="otro" name="genero" value="otro" checked>
         <label for="otro">Otro</label><br><br>



<button type="submit"<button title="haz click para enviar">Enviar</button>
<button type="reset"<button title="haz click para limpiar">Limpiar</button>
<button type="button"<button style="background-color:green;"<button title="haz click para consultar">Consultar</button>
<button type="button"<button title="haz click para salir"</button>

</body>
</html>
