

<!DOCTYPE html> <!-- NOTE: indica el tipo de documento  -->
<html> <!-- NOTE: comienzo del tipo de documento  -->
    <head> <!-- NOTE: todo lo que va al principio del documento  -->
      <title>My Webtest</title> <!-- NOTE: Titulo visual del documento  -->
      <style>
      #Lists{
        color: red;
        font-size: 32px;
      }
      .name{
        font-weight: lighter;
        color: blue;
      }
      table{
        border: 2px solid black;
        border-collapse: collapse;
      }

      th, td{
        border: 1px solid black;
        padding: 4px;
        width: 30%;
        text-align: center;
      }

      th{
        background-color: lightgreen;
        border: 2px solid black;
      }


      div{
        color: darkgreen;
        margin: 10px;
        padding: 12px;
        font-family: Serif, Helvetica, Arial;
        font-weight: bold;
        border: 2px dotted red;

      }
      h3 {
        color: gold;
        text-align: left;
      }
      </style> <!-- NOTE: Todos los parametros asociados a modificaciones visuales de texto u otros, aplicados a un todo  -->
    </head>
    <body> <!-- NOTE: toda la logica va aqui  -->



      <h1 style="color:#0c8e05;text-align:center;">wena sapos culiaos fracasados hijos de la sobacocos.</h1>
      <p style="color:purple;text-align:center;"> Agrego parrafos porque puedo</p>
      <h2>Testing sizes right now</h2>
      <h3>and the text is smaller</h3>
      <h4>Now, I'll add a list</h4>
      <div id="Lists"> <!-- NOTE: Division de datos, utilizado para separar definiciones de estilos u otros formatos    -->
        This is the <span class="name">Lists</span> of the webpage;<!-- NOTE: span entrega atributos a ciertos parametros-->
      Something listed:
      <ul> <!-- NOTE: Lista sin orden numerico definido  -->
        <li>Something</li> 
        <li>Something 2</li>
        <li>Something 3</li>
      </ul>
      Something ordered
      <ol> <!-- NOTE: Lista numerada por orden de aparicion  -->
        <li>primero</li>
        <li>segundo</li>
        <li>3ro</li>
      </ol>
    </div>
      <table> <!-- NOTE: Agrega una tabla  -->
        <tr> <!-- NOTE: agrega una fila  -->
          <th>Primero</th> <!-- NOTE: Cada encabezado de columna se ordena aqui  -->
          <th>Segundo</th>
          <th>Tercero</th>
        </tr>
        <tr> <!-- NOTE: Agrega una fila siguiente  -->
          <td>Alex</td> <!-- NOTE: Agrega datos fuera del encabezado, siguiendo orden logico de lineas  -->
          <td>Fabian</td>
          <td>Jose</td>
        </tr>
        <tr>
          <td>Fabian</td>
          <td>Alex</td>
          <td>Jose</td>
        </tr>
        <tr>
          <td>Jose</td>
          <td>Fabian</td>
          <td>Alex</td>
        </tr>
        <form> <!-- NOTE: Agrega un formulario o forma para agregar datos, como cajas de texto  -->

        <input type="text" placeholder="Full Name">
        <button>Enviar al culiao</button>
      </form>



<img src="alex.jpg" width="30%"> <!-- NOTE: Agrega una imagen a la pagina web  -->

    </body>
</html>
