---
title: 控制面板
seo-title: 控制面板
description: 「控制面板」可以讓您依執行個體及允許清單 IT 位址，監控及管理 SFTP 儲存。
seo-description: 「控制面板」可以讓您依執行個體及允許清單 IT 位址，監控及管理 SFTP 儲存。
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: ca3b7933927914b9965f6f059293041dd1db1da2
workflow-type: tm+mt
source-wordcount: '419'
ht-degree: 76%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>Adobe Campaign 文件中的「[!UICONTROL whitelist]」及「[!UICONTROL blacklist]」字詞，已由「[!UICONTROL allow list]」及「[!UICONTROL block list]」取代。
>產品 UI、選項名稱、內部代碼及教學課程影片仍可能出現這些詞語。即將發行的「控制面板」版本，則將徹底取代原先的字詞。

[!UICONTROL Control Panel] 讓 Adobe Campaign 管理員監控關鍵資產並執行管理工作，例如依執行個體或 [!UICONTROL allow list] IP 位址管理 SFTP 儲存。

## 存取 [!UICONTROL Control Panel]

若要存取「控制面板」，請前往 Experience Cloud 首頁：[https://experiencecloud.adobe.com](https://experiencecloud.adobe.com)：

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   或
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]：**Campaign** > **[!UICONTROL Control Panel]卡片&#x200B;**

   或

* 直接從 URL：[https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## 必要條件

開始使用前，請先完成下列必要條件：

### 確認 [!DNL IMS Org ID]

您要瞭解您的 [!DNL IMS org ID]。以下影片說明您可以在何處查閱執行個體的 [!DNL IMS org ID]。

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*檢查[!DNL IMS Org ID](00:26 分鐘)*

### 管理員權限

必須擁有管理員權限才能存取 [!UICONTROL Control Panel]。
以下影片說明如何為 Campaign 執行個體新增管理員

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*如何為產品設定檔新增管理員「[!UICONTROL Administrators]」，以便使用[!UICONTROL Control Panel](01:03 分鐘)*

## [!UICONTROL Control Panel] 教學課程

* **管理SFTP伺服器**

   *瞭解如何監控伺服器容量、[!UICONTROL allow list]IP地址和添加SSH密鑰*

   * [監控伺服器容量、允許清單 IP 地址及新增 SSH 金鑰](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [產生 SSH 金鑰](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [連接到 SFTP 伺服器](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[委派子網域](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *瞭解如何將子網域完全委派至[!UICONTROL Adobe Campaign]*

* **[新增 SSL 憑證](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *瞭解如何使用「控制面板」新增SSL憑證以保護您的子網域。*

* **[新增URL權限](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *如何新增一些外部URL至授權URL清單，讓您的例項可以連線至這些URL。*

* **[IP 允許執行個體存取清單](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *瞭解如何依據IP位址範圍設定新的例[!UICONTROL allow listing]項連線。*

* **[Google TXT 記錄管理](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *瞭解如何將網站驗[!DNL Google TXT]證記錄新增至您用來透過網站傳送電子郵件至地址[!DNL GMAIL]的所有子網域[!UICONTROL Campaign Control Panel]。*

* **GPG 金鑰管理**

   *瞭解如何在指定的 Campaign 執行個體上產生和安裝公開/私人金鑰組，以加密傳出資料，以及在 Campaign 執行個體匯入和安裝公開金鑰，以解密傳入資料：*

   * [產生並安裝用於資料加密的 GPG 金鑰](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [使用 GPG 金鑰加密資料](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [解密資料](./gpg-key-management/decrypting-data.md)

* **[控制面板疑難排解](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *瞭解如何疑難排解[!UICONTROL Control Panel]*

## 其他資源：

* [控制面板說明中心](https://docs.adobe.com/content/help/zh-Hant/control-panel/using/control-panel-home.html)
