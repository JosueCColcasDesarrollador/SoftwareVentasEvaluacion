------------
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diagrama_basedatos/tablas_part01.jpeg)

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

- Obtenga más información sobre este proyecto [aquí](https://www.youtube.com/@Andre_Raton).
- Puedes Escribirme por Tiktok para cualquier Consulta del Proyecto [aquí](https://www.tiktok.com/@blankuskaladoguita)

![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_01.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_02.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_03.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_04.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_05.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_06.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_07.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_08.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_09.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_10.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_11.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_12.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_13.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_14.jpeg)
![Img](https://github.com/JosueCColcasDesarrollador/ProyectoEvaluacion/blob/main/diseño_proyect/diseño_15.jpeg)

------------
