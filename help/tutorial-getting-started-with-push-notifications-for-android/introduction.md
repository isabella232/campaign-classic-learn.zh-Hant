---
title: Android 推播通知教學課程快速入門 - 簡介
description: 本教學課程將逐步引導您完成從 Adobe Campaign 傳送推播通知以及在 Android 應用程式中接收這些通知的步驟。
feature: 推播
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
translation-type: ht
source-git-commit: 298d3745a32d4509a82295be851f6e390f33749a
workflow-type: ht
source-wordcount: '366'
ht-degree: 100%

---

# Android 推播通知教學課程快速入門 - 簡介

Adobe Campaign 可讓您將個人化和分段的 [!DNL push] 通知傳送至 [!DNL iOS] 和 [!DNL Android] 行動裝置。本教學課程將引導您完成從 Adobe Campaign 傳送 [!DNL push] 通知至 [!DNL Android] 應用程式的相關步驟。

## 必要條件

在開始之前，您需要具備下列功能：

1) **Android 行動應用程式**

   本教學課程不涵蓋設定行動應用程式所需的詳細步驟。您需要將 **[!DNL Android]行動應用程式與 [!DNL Campaign SDK] 整合**。

   您可在產品檔案中找到所需步驟的詳細說明：

   [將 Campaign SDK 整合至行動應用程式](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=zh-Hant)

   您也可以使用 Experience Platform Mobile SDK。如需詳細資訊，請觀看教學課程影片：

   [使用 Experience Platform Mobile SDK 設定推播通道](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=zh-Hant)

2) 已安裝 **[!DNL Mobile App channel]軟體套件**

   [!DNL Mobile App channel] 套件必須安裝在您的 [!DNL Campaign] 執行個體上。下列影片說明如何檢查是否已在您的執行個體上安裝 [!DNL Mobile App channel]，若未安裝，則會指導您進行安裝。

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## 教學課程概觀

我們想要傳送個人化促銷 [!DNL push] 通知給 [!DNL Neotrip] [!DNL Android]行動應用程式的訂閱者。[!DNL Neotrip] 應用程式已使用 [!DNL Campaign SDK] 設定，我們確定 [!DNL Mobile App channel] 已在 [!DNL Campaign] 執行個體上啟動。

需要下列設定步驟：

### 步驟 1：擴充應用程式訂閱結構以個人化 [!DNL push] 通知

由於我們想要個人化 [!DNL push] 通知，因此我們將先[擴充應用程式訂閱綱要](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)，以儲存使用者訂閱服務時從應用程式收到的個人化值。

### 步驟 2：設定 Android 服務並在 Campaign 中建立行動應用程式

接下來，我們需要[設定 Android 服務，並在 Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md) 中建立行動應用程式。在此步驟中，我們會將 [!DNL Neotrip] 應用程式定義為推播通知的目標。

### 步驟 3：設定並傳送推播通知

然後，我們準備好[設定並傳送推播通知](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md)。

## 開始教學課程

步驟 1：[擴充應用程式訂閱綱要](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
