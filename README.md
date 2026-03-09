# Guía de Instalación y Configuración de WordPress

## Introducción
Esta guía te llevará a través de los pasos necesarios para instalar y configurar WordPress en tu servidor.

## Requisitos Previos
Antes de comenzar, asegúrate de tener:
- Un dominio registrado.
- Un servidor web (Apache o Nginx).
- PHP (versión 7.4 o superior).
- MySQL o MariaDB (versión 5.7 o superior).

## Paso 1: Descargar WordPress
1. Ve al [sitio oficial de WordPress](https://wordpress.org/download/).
2. Descarga la última versión de WordPress.
3. Descomprime el archivo descargado en tu computadora.

## Paso 2: Subir WordPress al Servidor
1. Conéctate a tu servidor mediante FTP (por ejemplo, usando FileZilla).
2. Sube todos los archivos de WordPress a la carpeta raíz de tu dominio.

## Paso 3: Crear una Base de Datos
1. Accede a tu panel de control de hosting (cPanel, Plesk, etc.).
2. Crea una nueva base de datos y un usuario con todos los privilegios para esa base de datos.
3. Anota el nombre de la base de datos, el nombre de usuario y la contraseña.

## Paso 4: Configurar el Archivo `wp-config.php`
1. Renombra el archivo `wp-config-sample.php` a `wp-config.php`.
2. Abre el archivo y completa los detalles de la base de datos:
   ```php
   define('DB_NAME', 'nombre_de_tu_base_de_datos');
   define('DB_USER', 'nombre_de_usuario');
   define('DB_PASSWORD', 'contraseña');
   ```

## Paso 5: Ejecutar la Instalación
1. Abre tu navegador y accede a tu dominio.
2. Sigue las instrucciones en pantalla para completar la instalación de WordPress.

## Paso 6: Configuración Inicial
1. Accede al panel de administración de WordPress (`tudominio.com/wp-admin`).
2. Configura los ajustes generales, como el título del sitio y la zona horaria.
3. Instala un tema y plugins según tus necesidades.

## Conclusión
¡Felicidades! Has instalado y configurado WordPress exitosamente. Ahora puedes comenzar a crear contenido y personalizar tu sitio web.
