<p align="center"><img src="https://res.cloudinary.com/dtfbvvkyp/image/upload/v1566331377/laravel-logolockup-cmyk-red.svg" width="400"></p>

## Proyecto blog con laravel
login registro con validaciones, diseño bootstrap 4 plantilla original se ven los posts, con titulo imagen o video, y parte del texto, para seguir leyendo se dirige a su post del usuario con nombre y fecha

crud consultar o ver,agregar o crear,editar y eliminar con sus validaciones iniciales.

agrega imagen, texto, video embebido como comapartir de yotube

falta agregar mas validaciones

posee seguridad de autenticacion, seguridad de token, seguridad de validaciones.

posee un componente llamado slug para los post, para que se agregue el titulo en el post de su url, para el posicionamiento seo

posee la relacion de base de datos con usuarios y su post

posee relacion en el modelo de laravel para que sepa sus relaciones en las tablas

posee factoris y seeds, en la base de datos, que son datos falsos o semillas, para que se agreguen tanto la tabla post como en tabla usuario de la base de datos

##  Comandos Laravel usados
## laravel new blog --auth 

se puede crear antes de hacer el proyecto

## php artisan make:model Post -mfc
migración Factory y controlador

## php artisan make:controller Backend/PostController --resource --model=Post
se crea el controlador dentro de una carpeta, con su modelo y de tipo recurso

## php artisan storage:link
con este comando generamos un enlace simbólico o acceso directo, para crear un acceso directo a la carpeta public para agregar la imagen y poderla mostrar

## Control de versiones en instalación
Composer Último 1.10.1

git 2.26.0) 64-bit version of Git for Windows

Laragon Full Apache 2.4, Nginx, MySQL 5.7, PHP 7.2, Redis, Memcached

Node.js Latest LTS Version 12.16.1 (includes npm 6.13.4)

Visual Studio Code Versión 16.5

Laravel Installer 3.0.1

## NOSTAS: 
cuando se instala composer hay que configurar las variables de entorno en php

cuando se instala Node.js Ahora, en Valor de variable, agregue la ruta de acceso donde se instaló Node.js. ( C:\Archivos de programa\nodejs).

luego con este comando en el terminal cmd instalamos NPM npm install npm@latest -g
