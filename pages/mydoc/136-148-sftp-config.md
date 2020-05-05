---
title: SFTP
keywords:
sidebar: netdrive_sidebar
permalink: 136-148-sftp-config.html
toc: false
hide_sidebar: true
---

CONNECT (CONECTAR)
==================
Elija SFTP en FROM (DESDE) y/o TO (HACIA) y luego pinche CONNECT (CONECTAR) para asociar la cuenta a la tarea de sincronización.

{% include inline_image.html file="sftp_config_1.jpg" max-width="200" %}


{% include inline_image.html file="sftp_config_2.jpg" max-width="200" %}

Escriba el Usuario de la cuenta SFTP y la contraseña (si es necesario).

También puede usar una llave Privada para conectar. Pinche "BROWSE" ("HOJEAR") para seleccionar el archivo de llave privada. El formato Putty no está soportado y sólo se soporta el formato openssh.  Si está disponible, necesita insertar la palabra clave en el archivo de llave privada. También puede indicar que se guarde la palabra clave.


OPTIONS (OPCIONES)
==================


{% include inline_image.html file="sftp_config_3.jpg" max-width="200" %}


* **Use server time for files/folders** : Usa el tiempo establecido de los archivos/carpetas guardados en el servidor en lugar de la zona horaria del computador local.

* **Use new file permission** : Establece los permisos de acceso para los archivos recién creados.

* **Use new folder permission** : Establece los permisos de acceso para las carpetas recién creadas.

* **Mount Point**
    * **User home** : Conecta a la carpeta raíz para el usuario.
    * **System root** : Conecta a la raíz del sistema del servidor SFTP.

* Max sessions : Limita el número de sesiones. (CloudSync usa múltiples conexiones simultáneas para mejorar el rendimiento al transferir datos.)

* Bandwidth :  Configuraciones para el Control de ancho de banda.

