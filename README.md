
# Examen practico: Modelo vista controlador (MVC)

## Concepto
El proyecto propuesto para el examen práctico consiste en la inserción, modificación, búsqueda y eliminación de registros desde un formulario PHP hacia una base de datos por medio de botones y campos de texto.

El escenario del proyecto en cuestión es la de el manejo de una base de datos de las diferentes categorías de productos de una tienda, donde los datos relevantes son los nombres de dichas categorías y la fecha de inserción de las mismas, esto con la función de llevar una organización más sencilla.

## Uso
El uso de este proyecto es bastante sencillo, ya que solo basta con escribir el nombre de una categoría en el campo de texto correspondiente, elegir la fecha de inserción de ésta y hacer clic en el botón de Insertar.

Cada registro se mostrará en una tabla que que está conectada a una base de datos. En esta tabla se muestra el número de identificación de cada categoría, su nombre y la fecha en que fue insertada.

Además de que, si el que entra al formulario es un administrador, se le mostrará una fila extra con dos botones que le permitirán eliminar y/o modificar cada categoría. Al presionar Modificar, el formulario de Insertar se autorellenará con los datos de la categoría a modificar, y el botón cambiará de Insertar a Modificar, esto para sobreescribir los datos a los que se hayan hecho cambios.

Este proyecto también cuenta con una barra de búsqueda, la cual nos permitirá visualizar los registros que nosotros necesitemos ver: esto escribiendo el nombre de la categoría y presionando el botón de Buscar.

## Instalación y ejecución
### (Obligatorio: tener instalado el programa XAMPP)

Para poder utilizar este proyecto, se debe crear una base de datos que contenga una tabla con los campos del número de identificación de la categoría, el nombre y la fecha de inserción.

Ya creada la base de datos, se debe modificar el archivo "config.php" alojado en la carpeta "bd" con los respectivos datos de la base de datos creada: nombre, servidor, contraseña, usuario; esto para lograr conectar el proyecto con ella. Y, de ser necesario, hay que reemplazar líneas de código del archivo "modelo.php" alojado en la carpeta "Modelos" dependiendo de los campos de la base de datos.

Y para poder usar el proyecto en nuestro navegador basta con mover la carpeta de nuestro proyecto a la carpeta "htdocs" alojada en la raíz del programa XAMPP y, posteriormente en el navegador, ingresar a esta en el URL por medio del localhost.