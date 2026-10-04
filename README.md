 Ejercicio 1 — WordPress: Construcciones Nova

Proyecto realizado para la actividad **UP01: Internet, Navegadores y Servidores**.

 Requisitos realizados

- Dominio local: `http://www.miproyecto.local/`
- Tres perfiles de usuario configurados.
- Tema y portada diseñados gráficamente para **Construcciones Nova**.
- Servicio de inicio de sesión mediante **Theme My Login**: `/iniciar-sesion/`.
- Servicio de formulario de contacto mediante **WPForms**: `/contacto/`.

   Diseño

La web está hecha para una empresa de construcción y reformas, con diferentes apartados sobre construcción, reformas, mantenimiento y otros servicios.

   Restauración del contenido

Para poder ver el proyecto en otro ordenador, independientemente de si se usa Windows o Linux:

1. Instalar un servidor web local compatible con WordPress (Apache, PHP y MariaDB/MySQL).
2. Instalar WordPress.
3. Instalar y activar **Theme My Login** y **WPForms**.
4. Copiar los archivos del proyecto en la carpeta de WordPress.
5. Ir a **Herramientas → Importar → WordPress**.
6. Seleccionar el archivo XML que se encuentra en `wordpress-export/`.
7. Importar el contenido y asignarlo al usuario correspondiente.
8. Configurar el dominio local `www.miproyecto.local` y añadirlo al archivo `hosts`.
9. Abrir `http://www.miproyecto.local/` en el navegador.

También se incluye el archivo `wordpress.sql` como copia de la base de datos.

> Las contraseñas y otros datos privados no se incluyen en el repositorio.