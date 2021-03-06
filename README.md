# Web APP de Gesti贸n Del Historial De Reservas De un Restaurante
# SARA-CONNOR

_Aplicaci贸n web dediacada a la gestion de mesas, m谩s especificamente al historial de ocupaci贸n de las mesas_

## Comenzando 馃殌

_A trav茅s de estas breves instrucciones, podr谩s instalar esta aplicaci贸n en tu maquina local._

Echale un ojo a **Deployment** (Despliegue) para conocer como desplegar el proyecto de la manera correcta.


### Pre-requisitos 馃搵

_Para poder tener nuestro proyecto funcionando en local necesitaremos las siguientes cosas:_


1. Tener instalado el XAMPP (o servidor APACHE y mysql)
    1.1. Para instalar XAMPP ejecuta el .exe y guardalo en una unidad (Ej. C:\xampp).
2. Tener instalado un editor de texto (como VSCode, o como notepad+++).
    2.2. Instala el editor de texto como un programa.


### Instalaci贸n 馃敡

_Aqui se te explicara como instalar/hacer todo lo necesario para que la aplicaci贸n web funcione correctamente:_

_Importar la Base De Datos_


1. Comprobar que el servicio de MySQL de tu ordenador no esta activado. Para comprobarlo escribe en la lupa "Servicios" busca "MySQL80" y si esta activo desactivalo.
2. Una vez instalado XAMPP activa el servicio MySQL y Apache.
3. Dale Administrar MySQL (bot贸n a la derecha del de iniciar servicio).
4. Cuando se abra la p谩gina arriba en el centro con una flecha de color rojo tenemos el bot贸n "Importar", le damos click.
5. Cuando se nos abra la nueva ventano tendremos otro bot贸n que dice "Selecionar Archivo", le damos click y buscamos nuestro archivo .sql que se encuentra dentro de la carpeta "db".


_Crear el fichero "config.php" (En caso de no tenerlo en services_


1. Si este fichero no existe, lo creas siguiendo el siguiente ejemplo:
    ```php
    <?php 
    define("SERVIDOR","localhost"); 
    define("USUARIO","root");
    define("PASSWORD","");
    define("BD","db_restaurante");
    ?>
    ```
2. Sustituyes los segundos valores (localhost, root, etc.)
3. En caso de que este fichero este creado, realizamos el paso n煤mero 2 directamente.


_Ejemplo: Para poder hacer login en nuestro proyecto_


1. *IMPORTANTE:* Tener la base de datos bien linkeada
2. Utilizar de usuario "isaac@fje.edu" y pass "1234" en caso de acceder como camarero
3. Utilizar de usuario "manolo@fje.edu" y password "1234
" en caso de acceder como mantenimiento


## Despliegue 馃摝

_Hemos alojado nuestro proyecto en una web de hosting gratuito. Para poder testear la herramienta, hacer click en el enlace (http://easyiom.infinityfreeapp.com) y podreis provar la web. Recordamos que para poder hacer el login sin problema teneis que utilizar los usuarios que estan arriba._

1. Crearse una cuenta en infinityfree
2. Crear un webpage
3. Ir a la herramienta de BDD (database tool)
4. Crear un usuario y contrase帽a, y apuntarse esos datos
5. Subir la base de datos al "database manager" (es un ohomyadmin, funciona igual que como l ohemos hecho en xampp)
6. comprovar que se ha subido correctamente la base de Datos
7. Ahora nos dirijimos al FTP (onlie file manager)
8. En public html subimos lo que encontramos en la raiz del proyecto
9. Vamos a config.php, y ponemos en el nombre de la base de datos la que no ha facilitado el database manager
10. Repetir el paso 9. en el username y el pass de la abse de datos
11. La aplicacions ya deberia estar funcionando


* IMPORTANTE: revisad que tengais en el FTP el archivo htacces

Si no funciona bien, m谩s abajo os facilitamos un mail de contacto con el equipo, para poder solucioanr cualquier problea

## Construido con 馃洜锔?



* [Visual Studio Code](https://code.visualstudio.com/download) - Editor de codigo para el proyecto
* [XAMPP](https://www.apachefriends.org/es/download.html) - Compliador de PHP
* [Inkscape](https://inkscape.org/es/) - Para crear los graficos vectoriales de las mesas

## Contribuyendo 馃枃锔?

_Si quieres colaborar en este proyecto, puede realizar su colaboraci贸n a trav茅s de BIZUM con el siguiente n煤mero xxx xxx xxx._
_Me puedes invitar a un cafe con este link: _




## Versionado 馃搶

Usamos [SemVer](http://semver.org/) para el versionado. Para todas las versiones disponibles, mira los [tags en este repositorio](https://github.com/tu/proyecto/tags). _Versi贸n Actual del Proyecto: 0.1.0_

## Autores 鉁掞笍

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Ra煤l Garcia** - *Back-End y base de datos*
* **Alfredo Blum** - *Back-End y base de datos*
* **Isaac Ortiz** - *Full stack y project manager*

Tambi茅n puedes mirar la lista de todos los [contribuyentes](https://github.com/your/project/contributors) qu铆enes han participado en este proyecto. 

## Licencia 馃搫

Este proyecto est谩 bajo la Licencia MIT - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 馃巵

* Muchas gracias a todo por descargar y probar nuestro proyecto.
* Cualquier sugerencia enviad mail a tumami@gmail.com
