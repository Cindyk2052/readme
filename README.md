# Patito Travel
## Acerca del proyecto (Manual de usuario)
<div align="center">
    <img src="captures/pantallaInicio.png" alt="Inicio" width="222" height="463">
</div>


Esta aplicación se ha creado con el objetivo de fomentar el turismo en Quito. Se ha desarrollado en el Framework Ionic.

La aplicación permite el acceso de tres roles, usuario turista, usuario propietario o encargado del sitio turístico y administrador general. El usuario encargado puede ingresar detalles del sitio turístico, el usuario turista puede ver todos los registros de los sitios ingresados y el administrador es capaz de eliminar los lugares que vea conveniente borrar. 

### Registro 
El registro de sesión cuenta con dos roles: Turista y Encargado 
<div align="center">
    <img src="captures/registroSesion.png" alt="Registro" width="232" height="492">
</div>

### Usuario Turista
El rol Turista al iniciar sesión puede ver los lugares turísticos que se han registrado y sus detalles
<div align="center">
    <img src="captures/detallesTurista.png" alt="Detaller" width="235" height="492">
</div>

Al ingresar en los detalles se pude ver la imagen del lugar, el nombre del local, nombre del dueño del local, la ciudad del sitio, detalles del local y la ubicación 
<div align="center">
    <img src="captures/verDetallesTurista.png" alt="Ver Detalles" width="232" height="492">
</div>

Es posible modificar el perfil. A quí se presenta el rol, el nombre de usuario y el correo con el que se registró. Es el nombre de usuario el cual se puede cambiar
<div align="center">
    <img src="captures/modPerfilTurista.png" alt="Mod Perfil" width="238" height="488">    <img src="captures/perfilTurista.png" alt="Perfil" width="246" height="488">
</div>

### Usuario Encargado
Los encargados registrados en la aplicación tienen la propiedad de crear lugares turísticos con las mismas características de los detalles que ve el turista y la ubicación actual
<div align="center">
    <img src="captures/crearSitioEncar.png" alt="Crear sitio" width="247" height="508">   <img src="captures/agregarSitioEncar.png" alt="Agregar sitio" width="242" height="508">    <img src="captures/listoSitioEncar.jpeg" alt="Sitio Listo" width="247" height="508">
</div>

Al registrar un sitio y colocar la ubicación, estas se obtienen de la ubicación actual
<img src="captures/ubicacionEncar.png" alt="Ubicacion" width="247" height="508">

Al igual que el turista, el usuario encargado puede modificar su nombre de perfil 
<div align="center">
    <img src="captures/modPerfilEncar.png" alt="Mod Perfil" width="236" height="500">   <img src="captures/perfilEncar.png" alt="Perfil" width="238" height="497">
</div>

### Usuario Administrador
El administrador tiene la autoridad de eliminar cualquier lugar turístico registrado por los encargados
<div align="center">
    <img src="captures/eliminarSitioAdmin.png" alt="Eliminar sitio" width="240" height="508">
</div>

Este usuario también tiene la cualidad de modificar su usuario
<div align="center">
    <img src="captures/modPerfilEncar.png" alt="Mod Perfil" width="238" height="506">   <img src="captures/perfilAdmin.png" alt="Perfil" width="237" height="507">
</div>

<p align="right">(<a href="#top">back to top</a>)</p>

### Herramientas
* [![Angular][Angular.io]][Angular-url]
* [![Ionic][Ionicframework.com]][Ionic-url]

## Getting Started

### Instalación (Manual de instalación)

1. Clona el repositorio
   ```sh
   git clone https://github.com/DanielGuachamin/proyecto-movil-1erbi.git
   ```
2. Instala las dependencias del proyecto
  	```sh
  	npm install 
  	```
 3. Levanta el servidor
 	```sh
  	ionic serve --lab 
  	```
## Anexos

Encuentra en el siguiente link como funciona la aplicación

* [LINK](https://choosealicense.com)

Además contamos con una página web

* [LINK](https://choosealicense.com)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->

[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Ionicframework.com]: https://img.shields.io/badge/Ionic-0769AD?style=for-the-badge&logo=ionic&logoColor=white
[Ionic-url]: https://ionicframework.com/
[product-screenshot]: captures/pantallaInicio.png
