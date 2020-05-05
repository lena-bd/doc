---
title: WebDAV
keywords:
sidebar: netdrive_sidebar
permalink: 102-123-webdav-config.html
toc: false
hide_sidebar: false
---

CONECTAR
==================
Elija WebDAV en TIPO DE ALMACENAMIENTO y luego pinche CONECTAR.

{% include inline_image.html file="webdav_config_1.jpg" max-width="200" %}


{% include inline_image.html file="webdav_config_2.jpg" max-width="200" %}


Escriba la dirección del servidor WebDAV.

* Synology NAS - número de puerto (port number) 5005, SSL - número de puerto (port number) 5006.

Escriba el Usuario y Contraseña de la cuenta. Desmarque "Save user and password" (Guardar usuario y contraseña) sino quiere guardar el usuario y contraseña de la cuenta WebDAV. En este caso necesita indicar esta información cada vez que se conecte al disco.


OPCIONES
==================


{% include inline_image.html file="webdav_config_3.jpg" max-width="200" %}


* Use server time for files/folders : Usa el tiempo establecido en los archivos/carpetas guardados en el servidor en lugar de la zona horaria del computador local.

* MS SharePoint Server : Marque para conectar a Sharepoint On-Premise. Note que NetDrive no soporta SharePoint En línea provisto por Office365.

* Attempt converting non-UTF-8 files to UTF-8 : Para los archivos que no soporten la codificación UTF-8, esta opción intenta cambiar el nombre de archivo a UTF-8.

* Bandwidth : Configuraciones de Control de ancho de banda.

