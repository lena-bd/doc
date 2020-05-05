---
title: Agregar & Configurar un Elemento de Disco
keywords:
sidebar: netdrive_sidebar
permalink: 94-102-agregar-configurar-un-elemento-de-disco.html
toc: false
hide_sidebar: true
---

Pinche el botón "+" en el lado inferior derecho para agregar elementos de disco. También puede cambiar la configuración del disco de cada elemento agregado pinchando "CONFIGURAR".

{% include inline_image.html file="agregar_configurar_un_elemento_de_disco_1.jpg" max-width="200" %}

- Elija el tipo de almacenamiento remoto desde el campo TIPO DE ALMACENAMIENTO y luego pinche "CONECTAR" para autenticar el almacenamiento remoto. Los tipos disponibles de elemento disco son los siguientes.

  - [Backblaze B2](102-109-backblaze-b2-config)
  - [Box](102-110-box-config)
  - [Dropbox](102-111-dropbox-config)
  - [FTP](102-112-ftp-config)
  - [Google Drive](102-113-google-drive-config)
  - [Google Cloud Storage](102-114-google-cloud-storage-config)
  - [hubiC](102-115-hubic-config)
  - [Local disk (Disco local)](102-124-localdisk-config)
  - [OneDrive](102-116-onedrive-config)
  - [OneDrive for Business](102-117-onedrive-for-business-config)
  - [S3](102-118-s3-config)
  - [Compatible con S3](102-119-s3-comp-config)
  - [SFTP](102-120-sftp-config)
  - [Swift](102-121-swift-config)
  - [ucloud biz](102-122-ucloud-biz-config)
  - [WebDAV](102-123-webdav-config)
  - [Amazon Drive (descontinuado)](102-104-amazon-drive-config)

- El botón "OPCIONES" permite establecer los valores de las opciones disponibles para cada tipo de almacenamiento.

- Después de autenticarse, pinche el botón "HOJEAR" para hojear la ruta remota.

{% include inline_image.html file="agregar_configurar_un_elemento_de_disco_2.jpg" max-width="200" %}

- Escriba el nombre del elemento disco en la categoría ETIQUETA.

{% include inline_image.html file="agregar_configurar_un_elemento_de_disco_3.jpg" max-width="200" %}

- Pinche el botón "COLOR" para seleccionar el color de fondo de cada elemento de disco.

{% include inline_image.html file="agregar_configurar_un_elemento_de_disco_4.jpg" max-width="200" %}

- Escoja la letra del disco para cada disco montado en la categoría MONTAR. Usted podría también elegir el tipo de disco, ya sea de red o local.

{% include inline_image.html file="agregar_configurar_un_elemento_de_disco_5.jpg" max-width="200" %}

- OPCIONES DE AUTO CONEXION

  - **Sin montaje automático** : Sólo se conecta cuando el usuario procede con el comando CONECTAR.
  - **Montar al iniciar** : Se conecta al arrancar el sistema (Sólo Windows). Note que los discos conectados se mostrarán a todos los usuarios de Windows ya que son conectados por la cuenta SYSTEM (SISTEMA).
  - **Montar al autenticarse** : Se conecta cuando la cuenta Bdrive es autenticada luego que la Aplicación de NetDrive es ejecutada.

- OPCIONES DE SUBIDA : Esta opción aplica cuando sube archivos usando el Explorador de Windows o el Buscador de macOS

  - **Usar subida en segundo plano** : Después de configurar un archivo en caché local, sube archivos a un sitio remoto. Aún cuando la copia se haya completado en el Explorador de Windows, es posible que NetDrive aún esté subiendo el archivo en segundo plano.
  - **Usar subida al vuelo en el Explorador** : Copia los archivos sin usar caché. Podría ser un poco más lento que la subida en segundo plano.

- OPCIONES DE SOLO LECTURA

  - **Disco escribible** : Conecta como discos escribibles.
  - **Disco de sólo lectura** : Conecta como discos de sólo lectura. Crear/borrar/renombrar archivos o carpetas no es posible.

- OPCION AVANZADA

  - **Siempre recuperar la lista de archivos desde el servidor** : No usa caché sobre la lista de archivos, ya que en su lugar solicita dicha lista directo del servidor. Podría ser un poco más lento en términos de velocidad.
  - **Como un disco removible** : Conecta como un disco removible tal y como se hace con las memorias USB.
  - **Tratar archivos y carpetas que inician con punto como ocultos** : Los archivos y carpetas que inician con un punto no se mostrarán.

- Pinche el botón "ACEPTAR" para terminar de agregar un elemento disco.
