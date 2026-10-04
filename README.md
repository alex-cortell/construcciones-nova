\# Construcciones Nova



Este es mi proyecto de WordPress para una página web de una empresa de construcción llamada Construcciones Nova.



\## Qué tiene la página



\- 3 usuarios de WordPress.

\- Página principal personalizada.

\- Página para iniciar sesión.

\- Formulario de contacto.

\- Diferentes apartados sobre construcción, reformas y mantenimiento.

\- Dominio local: `www.miproyecto.local`



\## Instalación en Windows



Para instalar el proyecto en Windows he utilizado XAMPP.



1\. Instalar XAMPP.

2\. Copiar la carpeta `wordpress` dentro de:



`C:\\xampp\\htdocs\\`



3\. Abrir XAMPP y encender \*\*Apache\*\* y \*\*MySQL\*\*.

4\. Entrar en `http://localhost/phpmyadmin`.

5\. Crear una base de datos llamada:



`wordpress`



6\. Importar el archivo `wordpress.sql` que está en este repositorio.

7\. Configurar `wp-config.php` con los datos de la base de datos.

8\. Editar el archivo `hosts` de Windows y añadir:



```text

127.0.0.1 www.miproyecto.local

```



9\. Configurar el VirtualHost de Apache para que el dominio `www.miproyecto.local` apunte a la carpeta de WordPress.

10\. Reiniciar Apache.

11\. Abrir en el navegador:



`http://www.miproyecto.local`



\## Instalación en Linux



En Linux se necesita tener instalados Apache, PHP y MariaDB.



1\. Copiar la carpeta `wordpress` dentro de:



`/var/www/html/`



2\. Iniciar Apache y MariaDB.

3\. Crear una base de datos llamada:



`wordpress`



4\. Importar el archivo `wordpress.sql`.

5\. Configurar `wp-config.php` con los datos de la base de datos.

6\. Editar el archivo:



`/etc/hosts`



y añadir:



```text

127.0.0.1 www.miproyecto.local

```



7\. Crear la configuración de Apache para que `www.miproyecto.local` apunte a:



`/var/www/html/wordpress`



8\. Activar la configuración y reiniciar Apache.

9\. Abrir en el navegador:



`http://www.miproyecto.local`



\## Archivos importantes



\- `wordpress/` → archivos de WordPress.

\- `wordpress.sql` → copia de la base de datos.

\- `README.md` → instrucciones para instalar el proyecto.



\## Programas utilizados



\- WordPress

\- XAMPP en Windows

\- Apache

\- PHP

\- MySQL / MariaDB

\- Linux

