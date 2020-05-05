---
title: WebDAV
keywords:
sidebar: netdrive_sidebar
permalink: 159-172-webdav-config.html
toc: false
hide_sidebar: false
---

CONNECT
==================
Choose WebDAV from FROM and/or TO, and then click CONNECT to associate the account to the synchronization task.

{% include inline_image.html file="webdav_config_1.jpg" max-width="200" %}


{% include inline_image.html file="webdav_config_2.jpg" max-width="200" %}


Enter the address of the WebDAV server.

* Synology NAS - port number (port number) 5005, SSL - port number (port number) 5006.

Enter the Username and Password of the account. Uncheck "Save user and password" if you do not want to save the user and password of the WebDAV account. In this case you need to indicate this information every time you connect to the disk.


OPTIONS
==================
{% include inline_image.html file="webdav_config_3.jpg" max-width="200" %}

* Use server time for files/folders: Use the time set in the files/folders saved on the server instead of the local computer's time zone.

* MS SharePoint Server: Check to connect to Sharepoint On-Premise. Note that NetDrive does not support SharePoint Online provided by Office365.

* Attempt converting non-UTF-8 files to UTF-8: For files that do not support UTF-8 encoding, this option attempts to change the file name to UTF-8.

* Bandwidth: Bandwidth Control Settings.

