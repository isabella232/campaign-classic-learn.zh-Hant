---
title: 控制面板疑難排解
description: 「控制面板」可以讓您依執行個體及允許清單 IP 位址監視及管理您的 SFTP 儲存空間。
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
role: Administrator
level: Experienced
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/trouble-shooting.html
translation-type: tm+mt
source-git-commit: 8847c322c63adb23ea33679714336d0aaac20100
workflow-type: tm+mt
source-wordcount: '343'
ht-degree: 99%

---


# 疑難排解 [!UICONTROL Control Panel]

## 登入和首頁

### 症狀：無法登入 Experience Cloud

**該做什麼：**
使用者需要找到其 IMS Org ID (xxx)。管理員需要將使用者新增到他們想要管理的每個執行個體的產品設定檔「Campaign-xxx-Admins」。如果使用者是所有執行個體的管理員，則他們仍需將自己新增為使用者。

### 症狀：使用者看不到 experience Cloud 首頁存取 [!UICONTROL Control Panel] 的連結

**原因：**
使用者直到新增為產品設定檔 _Campaign-xxx-Administrators/Admin 的使用者後，才能看到連結_。

**該做什麼：**
管理員需要將使用者新增至產品設定檔 _Campaign-xxx-Admins_，以便管理執行個體。如果使用者是所有執行個體的管理員，則他們仍需將自己新增為使用者。

### 症狀：執行個體未列於 [!UICONTROL Control Panel]

**原因：**
可能是，使用者需要新增為消失的執行個體的使用者產品設定檔 _Campaign-xxx-Administrators/Admin_

**該做什麼：**
管理員需要將使用者新增至產品設定檔 _Campaign-xxx-Admins_，以便管理執行個體。如果使用者是所有執行個體的管理員，則他們仍需將自己新增為使用者。

### 有用的影片

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*檢查 IMS 組織 ID (00:26分鐘)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*如何為產品設定檔管理員新增管理員，以便使用[!UICONTROL Control panel] (01:03 分鐘)*

### 實用文件

* [探索「控制面板」](https://helpx.adobe.com/tw/campaign/kb/control-panel-overview.html)
* [管理 [!UICONTROL Control Panel]](https://helpx.adobe.com/tw/campaign/kb/control-panel-access.html) 的權限

## 建立與 SFTP 伺服器（用戶端或 API）的連線

連線至 SFTP 伺服器需要：

* [!UICONTROL Allow listing] 您連接到 SFTP 伺服器的 IP 位址
* 需要向 Adobe Campaign 註冊私人/公有金鑰組
* 如果直接連接到 SFTP 伺服器，您還需要 SFTP 用戶端軟體

### 實用文件  {#helpful-docs}

* [登入您的 SFTP 伺服器](https://helpx.adobe.com/tw/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

