---
title: Add & configure drive items
keywords:
sidebar: netdrive_sidebar
permalink: 26-70-add-configure-drive.html
toc: false
hide_sidebar: false
---

우측 하단의 "+" 버튼을 누르면 드라이브 아이템을 추가할 수 있습니다. 또는 이미 추가된 드라이브에서 "CONFIG"를 선택하면 드라이브의 설정 값을 변경할 수 있습니다.

{% include inline_image.html file="add_configure_drive_1.jpg" max-width="200" %}

- STORAGE TYPE에서 사용하고자 하는 원격 스토리지 타입을 선택한 후, CONNECT 버튼을 눌러서 원격 스토리지를 사용할 수 있도록 인증을 받습니다.
  추가할 수 있는 드라이브 아이템의 종류는 아래와 같습니다.

  - [Amazon Drive](amazon-drive-config)
  - [Backblaze B2](backblaze-b2-config)
  - [Box](box-config)
  - [Dropbox](dropbox-config)
  - [FTP](ftp-config)
  - [Google Drive](google-drive-config)
  - [Google Cloud Storage](google-cloud-stroage-config)
  - [hubiC](hubic-config)
  - [OneDrive](onedrive-config)
  - [OneDrive for Business](onedrive-for-business-config)
  - [S3](s3-config)
  - [S3 compatible](s3-comp-config)
  - [SFTP](sftp-config)
  - [Swift](swift-config)
  - [ucloud biz](ucloud-biz-config)
  - [WebDAV](webdav-config)

- "CONNECT" 버튼 옆에 있는 "OPTIONS" 버튼을 누르면 스토리지 타입별로 지원하는 옵션값들을 설정할 수 있습니다.

- 인증이 완료되면 "BROWSE"를 눌러서 연결할 원격지의 경로를 선택할 수 있습니다.

{% include inline_image.html file="add_configure_drive_2.jpg" max-width="200" %}

- LABEL에는 드라이브 아이템의 이름을 입력합니다.

{% include inline_image.html file="add_configure_drive_3.jpg" max-width="200" %}

- 드라이브 아이템의 배경색을 설정할 수 있습니다.

{% include inline_image.html file="add_configure_drive_4.png" max-width="200" %}

- MOUNT에서 사용할 드라이브 레터를 선택하고, 드라이브의 타입을 네트워크 또는 컬 드라이브를 선택합니다.

{% include inline_image.html file="add_configure_drive_5.jpg" max-width="200" %}

- AUTO CONNECT OPTIONS

  - No automatic mount : 사용자가 CONNECT 명령을 내릴때에만 연결을 합니다.
  - Mount on boot : PC가 부팅이 될때 연결합니다. Windows만 지원. SYSTEM 계정으로 연결되기 때문에 연결된 드라이브는 모든 윈도우 사용자에게 보여집니다.
  - Mount on login : NetDrive Application이 실행된 후 Bdrive 계정이 로그인 될때 연결됩니다.

- UPLOAD OPTIONS : 탐색기를 사용하여 원격 스토리지에 파일을 올리때의 옵션입니다.

  - Use background uploading : 캐시에 파일을 구성한 후, 원격지에 파일을 올립니다. 탐색기에서는 복사가 완료되었더라도 NetDrive가 원격지에 파일을 올리는 중일 수 있습니다.
  - Use on-the-fly uploading in Explorer : 캐시를 사용하지 않고 복사하도록 합니다. 백그라운드 업로딩을 사용할때보다 느릴 수 있습니다.

- READ ONLY OPTIONS

  - Writable drive : 쓰기가 가능한 드라이브로 연결합니다.
  - Read only rive : 읽기만 가능한 드라이브로 연결합니다. 파일 또는 폴더의 생성, 삭제, 이름 변경등이 불가능합니다.

- ADVANCED OPTION

  - Always retrieve file list from server : 파일 목록에 대해서 캐시를 사용하지 않고 서버로부터 목록을 항상 읽어옵니다. 속도에 대한 성능이 느려질 수 있습니다.
  - As a removable drive : USB memory stick과 같은 제거 가능한 드라이브 속성을 가지도록 연결합니다.
  - Treat files and folders starting with a dot as hidden : "."으로 시작하는 파일 또는 폴더를 숨겨진 속성을 가지도록 연결합니다.

- "OK"를 누르면 드라이브 아이템이 추가됩니다.
