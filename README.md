  Ejercicio 1 — WordPress: Construcciones Nova

Proyecto realizado para la actividad **UP01: Internet, Navegadores y Servidores**.

   Requisitos realizados

- Dominio local: `http://www.miproyecto.local/` *(solo se puede ver desde mi PC por estar configurado como dominio local)*
- Tres perfiles de usuario configurados.
- Tema y portada diseñados gráficamente para **Construcciones Nova**.
- Servicio de inicio de sesión mediante **Theme My Login**: `/iniciar-sesion/`.
- Servicio de formulario de contacto mediante **WPForms**: `/contacto/`.

   Diseño

La web está hecha para una empresa de construcción y reformas, con diferentes apartados sobre construcción, reformas, mantenimiento y otros servicios.

   Restauración del contenido

El archivo de exportación de WordPress se encuentra en `wordpress-export/`. Para restaurarlo en otra instalación:

1. Instalar WordPress.
2. Instalar y activar **Theme My Login** y **WPForms**.
3. Ir a **Herramientas → Importar → WordPress**.
4. Seleccionar el archivo XML que se encuentra dentro de `wordpress-export/`.
5. Importar el contenido y asignarlo al usuario correspondiente.

También se incluye el archivo `wordpress.sql` con una copia de la base de datos.

> Las contraseñas y otros datos privados no se incluyen en el repositorio.