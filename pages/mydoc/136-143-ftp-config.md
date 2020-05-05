---
title: FTP/FTPS
keywords:
sidebar: netdrive_sidebar
permalink: 136-143-ftp-config.html
toc: false
hide_sidebar: true
---

CONNECT (CONECTAR)
==================
Elija FTP/FTPS en FROM (DESDE) y/o TO (HACIA) y luego pinche CONNECT (CONECTAR) para asociar la cuenta a la tarea de sincronización.


{% include inline_image.html file="ftp_config_1.jpg" max-width="200" %}


{% include inline_image.html file="ftp_config_2.jpg" max-width="200" %}

Aparecerá la ventana para escribir la información de la conexión FTP.

Escriba la dirección del servidor ftp y el número de puerto correctamente.

Marque "**Use SSL/TLS**" para usar SSL/TLS.

Marque "**Use Active Mode**" para Modo Activo.

Escriba la cuenta de usuario FTP y la contraseña.

Marque "**Anonymous**" para una cuenta anónima.

OPTIONS (OPCIONES)
==================
{% include inline_image.html file="ftp_config_3.jpg" max-width="200" %}

* **Charset** : Indica la información de codificación en los nombres de archivo. 
    * **Autodetect** : Detecta si el servidor FTP soporta o no UTF-8.
    * **Force UTF-8** : Fuerza a usar UTF-8 cuando transfiere nombres de archivo con el servidor FTP.
    * **Local charset** : Usa el juego de carácteres del computador local cuando transfiere nombres de archivo con el servidor FTP.

* **Use server time for files/folders** : Usa el conjunto de tiempo de archivos/carpetas guardados en el servidor en lugar de la zona horaria del computador local.

* Max sessions : Limita el número de sesiones. (CloudSync usa múltiples sesiones simultáneas para mejorar el rendimiento al transferir datos.)

* Bandwidth : Controla las configuraciones de ancho de banda.
