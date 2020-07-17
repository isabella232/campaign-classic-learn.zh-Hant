---
title: 問題解決控制面板
description: 「控制面板」可讓您依例項監視和管理SFTP儲存空間，並允許列出IP位址。
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '339'
ht-degree: 1%

---


# 故障排除 [!UICONTROL Control Panel]

## 登入與首頁

### 症狀： 無法登入Experience Cloud

**該做什麼：**
使用者必須找到其IMS組織ID(xxx)。 管理員需要將使用者新增至產品設定檔「Campaign-xxx-Admins」中，才能管理每個例項。 如果使用者是所有例項的管理員，則他們仍需將自己新增為使用者。

### 症狀： Experience Cloud首頁中的存取連結 [!UICONTROL Control Panel] 不會顯示給使用者

**原因：**
使用者直到新增為產品設定檔 _Campaign-xxx-Administrators/Admin的使用者後，才會看到連結_。

**該做什麼：**
管理員需要將使用者新增至產品設定檔 _Campaign-xxx_ -Admins，以便管理每個例項。 如果使用者是所有例項的管理員，則他們可能仍需將自己新增為「使用者」。

### 症狀： 例項未列於 [!UICONTROL Control Panel]

**原因：**
最可能的使用者需要新增為遺失例項的「使用者」產品設定檔 _Campaign-xxx-Administrators/Admin_ 。

**該做什麼：**
管理員需要將使用者新增至產品設定檔 _Campaign-xxx_ -Admins，以便管理每個例項。 如果使用者是所有例項的管理員，則他們可能仍需將自己新增為「使用者」。

### 有用的影片

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*檢查IMS組織ID（00:26分鐘）*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*如何將管理員新增至產品設定檔管理員，以便[!UICONTROL Control panel]使用（01:03分鐘）*

### 實用檔案

* [探索控制面板](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [管理 [!UICONTROL Control Panel]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## 建立與SFTP伺服器（用戶端或API）的連線

連線至SFTP伺服器需要：

* [!UICONTROL Allow listing] 您從中連接到SFTP伺服器的IP地址
* 需要向Adobe Campaign註冊的私密／公用金鑰對
* 如果直接連接到SFTP伺服器，您還需要SFTP客戶端軟體

### 有用的檔案

* [登入您的 SFTP 伺服器](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

