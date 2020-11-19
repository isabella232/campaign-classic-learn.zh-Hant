---
title: 教學課程簡介
description: 本教學課程將逐步引導您完成從 Adobe Campaign 傳送推播通知以及在 Android 應用程式中接收這些通知的步驟。
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 9b26dfd30e60c3e12c52e4318a853498af186b4a
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 9%

---


# 教學課程簡介

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. 本教學課程將逐步引導您完成從Adobe Campaign傳送通 [!DNL push] 知至應用程式的相關 [!DNL Android] 步驟。

## 必要條件

在開始之前，您需要具備下列功能：

1) **Android Mobile應用程式**

   本教學課程不涵蓋設定行動應用程式所需的詳細步驟。 您將需要具備整合式 **[!DNL Android]行動應用程 [!DNL Campaign SDK] 式**。

   您可在產品檔案中找到所需步驟的詳細說明：

   [將 Campaign SDK 整合至行動應用程式](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   您也可以使用Experience Platform Mobile SDK。 如需詳細資訊，請觀看教學課程影片：

   [使用Experience Platform Mobile SDK設定推播頻道](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]軟體包已安裝**

   您 [!DNL Mobile App channel] 的實例上需要安裝該 [!DNL Campaign] 軟體包。 下面的影片說明如何檢查實 [!DNL Mobile App channel] 例中是否已安裝，如果沒有，如何安裝。

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## 教學課程概觀

我們想要傳送個人化促銷通 [!DNL push] 知給行動應用程式 [!DNL Neotrip] 的 [!DNL Android] 訂閱者。 應 [!DNL Neotrip] 用程式已設定 [!DNL Campaign SDK] ，我們已確保已在 [!DNL Mobile App channel] 執行個體上啟動 [!DNL Campaign] 。

需要下列設定步驟：

### 步驟1:擴充應用程式訂閱結構以個人化通 [!DNL push] 知

由於我們想要個人化通 [!DNL push] 知，我們會先擴充應用程式 [](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) 訂閱結構，以便儲存使用者訂閱服務時從應用程式收到的個人化值。

### 步驟2:設定Android服務並在Campaign中建立行動應用程式

接下來，我們需要 [設定Android服務並在Campaign中建立行動應用程式](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md)。 在此步驟中，我們會將應 [!DNL Neotrip] 用程式定義為推播通知的目標。

### 步驟3:設定並傳送推播通知

然後，我們就可以 [設定並傳送推播通知](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)。

## 開始教學課程

步驟1: [擴充應用程式訂閱結構](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
