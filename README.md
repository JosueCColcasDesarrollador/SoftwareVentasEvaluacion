------------

[![Alt text](https://img.youtube.com/vi/0WzBeb2W3hI/0.jpg)](https://www.youtube.com/watch?v=0WzBeb2W3hI)

# SOFTWARE DE VENTAS

## Requerimientos
- Es necesario tener instalado [XAMPP](https://www.apachefriends.org/es/download.html "XAMPP") (versión **PHP** **8.0** o superior)  
- Es necesario tener instalado [Composer](https://getcomposer.org/download/ "Composer")

## Instalar en el entorno Local

1. Clone o descargue el repositorio a una carpeta en Local

1. Abra el repositorio en su editor de código favorito (**Visual Studio Code**)

1. Ejecute la aplicación **XAMPP** e inice los módulos de **Apache** y **MySQL**

1. Abra una nueva terminal en su editor 

1. Compruebe de que tiene instalado todas dependencias correctamente, ejecute los siguientes comandos: **(Ambos comandos deberán ejecutarse correctamente - ejecutar en la terminal)**
```bash
php -v
```
```bash
composer -v
```

1. Ahora ejecute los comandos para la configuración del proyecto (**ejecutar en la terminal**):

- Este comando nos va a instalar todas la dependencias de composer
```bash
composer install
```
- En el directorio raíz encontrará el arhivo **.env.example**, dupliquelo, al archivo duplicado cambiar de nombre como **.env**, este archivo se debe modificar según las configuraciones de nuestro proyecto. Ahí se muestran como debería quedar
```bash
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=dbsistemaventas 
DB_USERNAME=root
DB_PASSWORD=
```
- Ejecutar el comando para crear la Key de seguridad
```bash
php artisan key:generate 
```
- Ingrese al administrador de [PHP MyAdmin](http://localhost/phpmyadmin/) y cree una nueva base de datos, el nombre es opcional, pero por defecto nombrarla **dbsistemaventas**

- Correr la migraciones del proyecto
```bash
php artisan migrate
```
- Ejecute los seeders, esto creará un usuario administrador, puede revisar las credenciales en el archivo (**database/seeders/UserSeeder**)
```bash
php artisan db:seed
```
- Ejecute el proyecto
```bash
php artisan serve
```

## Notas
- Obtenga más información sobre este proyecto [aquí](https://www.youtube.com/@Andre_Raton).
- Puedes Escribirme por Tiktok para cualquier Consulta del Proyecto [aquí](https://www.tiktok.com/@blankuskaladoguita)

------------

 # DIAGRAMA ERD

![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diagrama_basedatos/tablas_part01.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diagrama_basedatos/tablas_part02.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diagrama_basedatos/tablas_part03.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diagrama_basedatos/tablas_part04.jpeg)

------------

# DISEÑO Y EXPLICACION DEL SOFTWARE

Esta es la Portada del Software cuando Iniciamos es una Presentación para Incentivar a los Expectadores a Adquirir un Sistema con el Fin de Hacerles Generar mas Ganancias a sus Negocios de Manera Optimizada.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_01.jpeg)

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_02.jpeg)

En Esta Captura Podemos Aprecias el Login para Iniciar Sesión en el Sistema te pedirá ingresar tu Correo y tu Contraseña, Con la Finalidad de poder acceder al Software de Ventas.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_03.jpeg)

Luego de Loguearnos, Ingresaremos al Sistemas donde nos dará la bienvenida con una ventanita Flotante asi como se muestra en la captura con Nuestros Nombres Completos Ingresador en Nuestro Usuario.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_04.jpeg)

En esta Parte es la Interface donde podremos apreciar las cantidades de Datos Ingresados al Sistema mejor dicho como un  Reportes de todos los datos que Ingresemos se estaren sumando en estos cuadritos de Colores que podemos Apreciar.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_05.jpeg)

En Esta captura tenemos Los Roles en esta pagina podremos Ingresar, Modificar y Eliminar los datos y darle un rol adecuado a cada participante para el sistema.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_06.jpeg)

En la pagina de Usuario podremos es Ingresar, Modificar y Eliminar los Usurios. Y ahí que tener presente una cosa que solo se podrá ingresar un solo Correo Electronico Unico ósea quiere decir que no se podrá ingresar mas de dos Correos Electrónicos Iguales.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_07.jpeg)

En la Pagina de Proveedores podremos Ingresar, Modificar y Ahí algo diferente al Eliminar Un dato no se eliminara sino se desactivara. También Podremos volverla a Activar el datos Eliminado con el Boton de Restaurar que tiene esta función la Pagina.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_08.jpeg)

En la Pagina de Clientes podremos Ingresar, Modificar y Ahí algo diferente al Eliminar Un dato no se eliminara sino se desactivara. También Podremos volverla a Activar el datos Eliminado con el Boton de Restaurar que tiene esta función la Pagina.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_09.jpeg)

En la Pagina de Marcas podremos Ingresar, Modificar y Ahí algo diferente al Eliminar Un dato no se eliminara sino se desactivara. También Podremos volverla a Activar el datos Eliminado con el Boton de Restaurar que tenie esta función la Pagina.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_10.jpeg)

En la Pagina de Categoria podremos Ingresar, Modificar y Ahí algo diferente al Eliminar Un dato no se eliminara sino se desactivara. También Podremos volverla a Activar el datos Eliminado con el Boton de Restaurar que tiene esta función la Pagina.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_11.jpeg)

En la Pagina de Presentaciones podremos Ingresar, Modificar y Ahí algo diferente al Eliminar Un dato no se eliminara sino se desactivara. También Podremos volverla a Activar el datos Eliminado con el Boton de Restaurar que tiene esta función la Pagina.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_12.jpeg)

En la Pagina de Productos podremos Ingresar, Modificar y Ahí algo diferente al Eliminar Un dato no se eliminara sino se desactivara. También Podremos volverla a Activar el datos Eliminado con el Boton de Restaurar que tiene esta función la Pagina.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_13.jpeg)

En la Pagina de Compras podremos Ingresar, Eliminar y Ver las Compras.

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_14.jpeg)

En la Pagina de Ventas podremos Ingresar, Eliminar y Ver las Compras. Para más Información detallada del Software te dejo un Link bien Explicado. [aquí](https://www.youtube.com/@Andre_Raton).

![Img](https://github.com/JosueCColcasDesarrollador/SoftwareVentasEvaluacion/blob/main/dise%C3%B1o_proyect/dise%C3%B1o_15.jpeg)

------------
