---
title: 如何設定循環和持續的電子郵件宣傳
description: 本教學課程說明如何設定循環和持續傳送，以及Adobe Campaign Classic(ACC)中兩種方法的差異。
feature: workflows
topics: channel activities
kt: 1560
doc-type: feature video
activity: use
team: TM
translation-type: tm+mt
source-git-commit: 838c617ca163a09fcb57b7b4706433e98869bc3d
workflow-type: tm+mt
source-wordcount: '272'
ht-degree: 0%

---


# 如何設定循環和持續的電子郵件宣傳

本教學課程說明如何設定循環和持續傳送，以及兩種方法的差異。

## 循環和持續傳送追蹤 {#recurring-and-continuous-delivery-tracking}

持續和持續的傳送方式與管理聯絡資料的方式不同：

* 持續 **傳送** ，可讓您將新收件者新增至現有的傳送，而且不必在每次新增收件者時建立新的傳送。 您可以直接在促銷活動工作流程中更新創作內容，並會在傳送範本「資源」檔案夾中更新範本。

   持續傳送將建立SINGLE傳送和傳送記錄檔(broadLog)和追蹤記錄檔，以參考每次執行時會新增一個傳送。

![持續傳送](/help/assets/delivery_continuous.jpg)

* 循 **環傳送** ，每次執行時都會建立新的傳送例項。 例如，如果排程工作流程每週執行一次，則一年後會產生52次傳送。 這也表示廣泛的記錄檔和追蹤記錄檔將依每個傳送例項分開。

![循環傳送](/help/assets/delivery_recurring.jpg)

## 如何設定循環傳送 {#how-to-set-up-a-recurring-delivery}

此影片說明如何設定循環傳送和排程器活動。

>[!VIDEO](https://video.tv.adobe.com/v/25040?quality=12)

## 如何設定連續傳送 {#how-to-set-up-a-continuous-delivery}

此視訊說明如何設定具有遞增查詢的連續傳送。

>[!VIDEO](https://video.tv.adobe.com/v/25039?quality=12)

## 其他資源

[在定位工作流程中建立循環傳送](https://docs.adobe.com/content/help/en/campaign-classic/using/automating-with-workflows/use-cases/sending-a-birthday-email.html#creating-a-recurring-delivery-in-a-targeting-workflow)