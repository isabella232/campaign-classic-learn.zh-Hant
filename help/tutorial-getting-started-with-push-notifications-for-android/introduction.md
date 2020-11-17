---
title: 教學課程Android推播通知快速入門——簡介
description: 本教學課程將逐步引導您完成從 Adobe Campaign 傳送推播通知以及在 Android 應用程式中接收這些通知的步驟。
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 217b0ec1b6f5c5e17009f1103d69726aa57dcaa4
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 6%

---


# 教學課程Android推播通知快速入門——簡介

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

本教學課程將逐步引導您完成從Adobe Campaign傳送通 [!DNL push] 知至應用程式的相關 [!DNL Android] 步驟。

## 必要條件

在開始之前，您需要滿足以下先決條件

1) 行動應用程式本教學課程不涵蓋設定行動應用程式所需的詳細步驟。 您將需要具備整合式 **[!DNL Android]行動應用程[!DNL Campaign SDK]** 式。

   * 您可在「將Campaign SDK整合至行動應用程式」中，找 [到所需步驟的詳細說明](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)。

   * 您也可以使用Experience Platform Mobile SDK。 如需詳細資訊，請 [觀看「使用Experience Platform Mobile SDK設定推播頻道](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) 」教學課程影片。

2) 已安裝行動應用程式頻道套件

   您的例項上必須安裝行動應用程式頻道套件。 以下影片說明如何檢查您的例項是否已安裝行動應用程式頻道，若未安裝，則說明如何安裝。

   [!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## 教學課程

我們想要傳送個人化促銷推播通知給Neotrip行動應用程式的 [!DNL Android] 用戶。 Neotrip應用程式已設定Campaign SDK，我們已確保行動應用程式渠道已在我們的Campaign例項上啟用。

需要下列設定步驟：

### 步驟1:擴充應用程式訂閱結構以個人化推播通知

由於我們想要個人化推播通知，因此我們會先擴充應用程式 [訂閱結構](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) ，以便儲存使用者訂閱服務時從應用程式收到的個人化值。

### 步驟2:設定Android服務並在Campaign中建立行動應用程式應用程式

接下來，我們需要設 [定Android服務，並在Campaign中建立行動應用程式應用程式](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md)。 在此步驟中，我們將定義Neotrip應用程式作為推播通知的目標。

### 步驟3:設定並傳送推播通知

然後，我們就可以 [設定並傳送推播通知](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)。

## 開始教學課程

**[步驟1:擴充應用程式訂閱結構](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**
