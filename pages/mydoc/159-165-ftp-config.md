---
title: FTP/FTPS
keywords:
sidebar: netdrive_sidebar
permalink: 159-165-ftp-config.html
toc: false
hide_sidebar: true
---

CONNECT
==================
Choose FTP/FTPS from FROM and/or TO, and then click CONNECT to associate the account with the synchronization task.


{% include inline_image.html file="ftp_config_1.jpg" max-width="200" %}


{% include inline_image.html file="ftp_config_2.jpg" max-width="200" %}

The window to enter the FTP connection information will appear.

Enter the ftp server address and port number correctly.

Check "** Use SSL/TLS **" to use SSL/TLS.

Check "** Use Active Mode **" for Active Mode.

Enter the FTP user account and password.

Check "** Anonymous **" for an anonymous account.

OPTIONS
==================
{% include inline_image.html file="ftp_config_3.jpg" max-width="200" %}

* ** Charset **: Indicates the encoding information in the file names.
    * ** Autodetect **: Detects whether the FTP server supports UTF-8 or not.
    * ** Force UTF-8 **: Force to use UTF-8 when transferring file names with the FTP server.
    * ** Local charset **: Use the character set of the local computer when transferring file names with the FTP server.

* ** Use server time for files / folders **: Use the time set of files / folders stored on the server instead of the local computer's time zone.

* Max sessions: Limit the number of sessions. (CloudSync uses multiple simultaneous sessions to improve performance when transferring data.)

* Bandwidth: Controls bandwidth settings.
     