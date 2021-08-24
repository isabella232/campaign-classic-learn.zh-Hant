---
title: 控制面板疑難排解
description: 「控制面板」可讓您依執行個體及允許清單IP位址來監視和管理您的SFTP儲存。
feature: 控制面板
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '332'
ht-degree: 42%

---


# 疑難排解 [!UICONTROL Control Panel]

## 登入和首頁

### 症狀：無法登入Experience Cloud

**該做什麼：**
使用者必須找到其IMS組織ID(xxx)。管理員必須將使用者新增至產品設定檔「Campaign-xxx-Admins」，以管理其要管理的每個執行個體。 如果使用者是所有執行個體的管理員，則他們必須將自己新增為使用者。

### 症狀：使用者看不到 experience Cloud 首頁存取 [!UICONTROL Control Panel] 的連結

**原因：**
使用者直到新增為產品設定檔 _Campaign-xxx-Administrators/Admin 的使用者後，才能看到連結_。

**該做什麼：**
管理員必須將使用者新增至產品設 _定檔Campaign-xxx-_  Admin，以管理他們想要管理的每個執行個體。如果使用者是所有執行個體的管理員，則必須將自己新增為「使用者」。

### 症狀：執行個體未列於 [!UICONTROL Control Panel]

**原因：**
可能的是，使用者必須新增為遺失執行個體的 _「使用者」產品設定檔Campaign-xxx-Administrators/_ Admin

**該做什麼：**
管理員必須將使用者新增至產品設 _定檔Campaign-xxx-_  Admin，以管理他們想要管理的每個執行個體。如果使用者是所有執行個體的管理員，則他們必須將自己新增為「使用者」。

### 有用的影片

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*檢查 IMS 組織 ID (00:26分鐘)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*如何為產品設定檔管理員新增管理員，以便使用[!UICONTROL Control panel] (01:03 分鐘)*

### 實用文件

* [探索「控制面板」](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=zh-Hant)
* [管理 [!UICONTROL Control Panel]](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en) 的權限

## 建立與 SFTP 伺服器（用戶端或 API）的連線

連線至 SFTP 伺服器需要：

* [!UICONTROL Allow listing] 您連接到 SFTP 伺服器的 IP 位址
* 必須向Adobe Campaign註冊的私密/公開金鑰組
* 如果直接連線至SFTP伺服器，您需要SFTP用戶端軟體

### 實用文件 {#helpful-docs}

* [登入您的 SFTP 伺服器](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

