---
title: WebDAV
keywords:
sidebar: netdrive_sidebar
permalink: config_webdav.html
toc: false
hide_sidebar: true
---

# CONNECT

Select WebDAV in STORAGE TYPE and then click CONNECT.

{% include inline_image.html file="webdav_1.jpg" max-width="200" %}

Type in WebDAV server address.

- Synology NAS - port number 5005, SSL - port number 5006.

Type in User account and Password. Uncheck "Save user and password" if you do not want to save FTP User account and Password. In this case you need to type these information each time you connect to the drive.

# OPTIONS

{% include inline_image.html file="webdav_2.jpg" max-width="200" %}

- Use server time for files/folders : Use the time set of files/folders saved in the server instead of local PC timezone.

- MS SharePoint Server : Check to connect to Sharepoint On-Premise. Note NetDrive does not support Sharepoint Online provided by Office365.

- Attempt converting non-UTF-8 files to UTF-8 : For the files not supporting UTF-8 encoding,this option attempts to change the file name to UTF-8.

- Bandwidth : Control bandwidth settings.

{% include links.html %}
