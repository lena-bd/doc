---
title: SFTP
keywords:
sidebar: netdrive_sidebar
permalink: 159-171-sftp-config.html
toc: false
hide_sidebar: false
---

CONNECT
==================
Choose SFTP from FROM and/or TO, and then click CONNECT to associate the account with the synchronization task.

{% include inline_image.html file="sftp_config_1.jpg" max-width="200" %}


{% include inline_image.html file="sftp_config_2.jpg" max-width="200" %}

Enter the SFTP Account User and password (if necessary).

You can also use a Private key to connect. Click on "BROWSE" to select the private key file. The Putty format is not supported and only the openssh format is supported. If available, you need to insert the keyword in the private key file. It can also indicate that the keyword is saved.


OPTIONS
==================


{% include inline_image.html file="sftp_config_3.jpg" max-width="200" %}


* ** Use server time for files/folders **: Use the set time of files/folders saved on the server instead of the local computer's time zone.

* ** Use new file permission **: Sets the access permissions for newly created files.

* ** Use new folder permission **: Sets the access permissions for newly created folders.

* ** Mount Point **
    * ** User home **: Connects to the root folder for the user.
    * ** System root **: Connects to the system root of the SFTP server.

* Max sessions: Limit the number of sessions. (CloudSync uses multiple simultaneous connections to improve performance when transferring data.)

* Bandwidth: Settings for Bandwidth Control.

