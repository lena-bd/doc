---
title: Add and configure a drive item
keywords:
sidebar: netdrive_sidebar
permalink: add_configure_drive_item.html
toc: false
hide_sidebar: true
---

- Click "+" button at lower right side to add drive items. You can also change drive configuration of each added drive item by clicking "CONFIG".

{% include inline_image.html file="add_configure_drive_item_1.jpg" max-width="200" %}

- Select remote storage type from STORAGE TYPE field and then click "CONNECT" to authenticate remote storage. Available drive item types are as below.

  - [Backblaze B2](config_backblaze_b2)
  - [Box](config_box)
  - [Dropbox](config_dropbox)
  - [FTP](config_ftp)
  - [Google Drive](config_google_drive)
  - [Google Cloud Storage](config_google_cloud_stroage)
  - [hubiC](config_hubic)
  - [OneDrive](config_onedrive)
  - [OneDrive for Business](config_onedrive_for_business)
  - [S3](config_s3)
  - [S3 Compatible](config_s3_compatible)
  - [SFTP](config_sftp)
  - [Swift](config_swift)
  - [ucloud biz](config_ucloud_biz)
  - [WebDAV](config_webdav)
  - [Amazon Drive (discontinued)](config_amazon_drive)

- "OPTIONS" button allows to set available options values of each storage type.

- After authentication, click "BROWSE" button to browse the remote path.

{% include inline_image.html file="add_configure_drive_item_2.jpg" max-width="200" %}

- Type in the name of the drive item in LABEL category.

{% include inline_image.html file="add_configure_drive_item_3.jpg" max-width="200" %}

- Click "COLOR" button to select the background color of each drive item.

{% include inline_image.html file="add_configure_drive_item_4.png" max-width="200" %}

- Select drive letter for each mounted drive in MOUNT category. You may also select drive type, either network drive or local drive.

{% include inline_image.html file="add_configure_drive_item_5.jpg" max-width="200" %}

- AUTO CONNECT OPTIONS

- **No automatic mount** : Connects only when user proceeds CONNECT command.
- **Mount on boot** : Connects on system boot (Windows only). Note connected drives will be shown to all windows users since it is connected by SYSTEM account.
- **Mount on login** : Connects when Bdrive account is logged on after NetDrive Application is executed.

- UPLOAD OPTIONS : This option applies when you upload files using Windows Explorer or macOS Finder

- **Use background uploading** : After configuring a file in local cache, uploads files to remote site. Even the file copy is completed in Windows Explorer, it is possible that NetDrive is still uploading the file in background.
- **Use on-the-fly uploading in Explorer** : Copies files without using cache. It might be slightly slower than background uploading.

- READ ONLY OPTIONS

- **Writable drive** : Connects as writable drives.
- **Read only drive** : Connects as read only drives. Create/delete/rename of file or folder is not possible.

- ADVANCED OPTION

- **Always retrieve file list from server** : Does not use cache on file list but instead calls for the file list from the server. It might be slight slower in terms of speed.
- **As a removable drive** : Connects as removable drive such as USB memory stick.
- **Treat files and folders starting with a dot as hidden** : Files and folders with starting dot will not be shown.

- Click "OK" button to finish adding a drive item.

{% include links.html %}
