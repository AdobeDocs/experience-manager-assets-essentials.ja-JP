---
title: ビデオの編集
description: ' [!DNL Adobe Express]  を利用したオプションを使用してビデオを編集し、更新したビデオをバージョンとして保存します。'
role: User
exl-id: 8468d572-89f1-431d-be7f-01e583d06cd7
source-git-commit: a9ef92194f55da9ad5352adf4251c85e3abcdcd1
workflow-type: tm+mt
source-wordcount: '841'
ht-degree: 83%

---

# [!DNL Assets Essentials] でのビデオの編集 {#edit-videos}

ビデオ用に組み込まれた [!DNL Adobe Express] クイックアクションを使用すると、Assets ユーザーはビデオコンテンツのバリエーションを簡単に作成できます。 [!DNL Adobe Express] を利用した [!DNL Assets Essentials] のクイックアクションには、ビデオの切り抜き、ビデオのサイズ変更、ビデオのトリミング、ビデオの GIF への変換など、使いやすいビデオ編集オプションが用意されています。

ビデオを編集するには、ビデオの詳細に移動し、「[!UICONTROL ビデオを編集]」をクリックします。 または、アセットを選択して「詳細」をクリックし、右側のパネルにある![はさみ](assets/do-not-localize/cut.svg)アイコンをクリックします。 ビデオを編集した後、新しいビデオを新しいバージョンとして保存したり、新しいアセットとして保存したりできます。

[ プレビューインターフェイス ](/help/using/navigate-view.md#preview-assets)について詳しく説明します。

## 前提条件 {#prerequisites}

[!DNL Adobe Express] と AEM Assets 内の 1 つ以上の環境にアクセスする権限。 環境には、[!DNL Assets as a Cloud Service] または [!DNL Assets Essentials] 内の任意のリポジトリを指定できます。

## Adobe Express を使用したビデオの編集 {#edit-video-using-express}

>[!CONTEXTUALHELP]
>id="assets_express_integration_videos"
>title="ビデオ編集のための Adobe Express の統合"
>abstract="Experience Manager Assets には、Adobe Express を活用した簡単で直感的なビデオ編集ツールが含まれており、コンテンツの再利用を増やし、コンテンツの速度を高速化します。 編集オプションには、ビデオのトリミング、切り抜き、サイズ変更、MP4 から GIF ファイルへの変換などが含まれます。"

組み込まれた [!DNL Adobe Express] クイックアクションを使用すると、ビデオを完璧なサイズや方向に簡単に変換できます。

### ビデオの切り抜き {#crop-video-using-express}

組み込まれた [!DNL Adobe Express] クイックアクションを使用して、ビデオから不要な部分を削除できます。 これを行うには、次の手順を実行します。

1. ビデオを選択し、「**[!UICONTROL 編集]**」をクリックします。
2. 左側のパネルにあるクイックアクションから「**[!UICONTROL ビデオを切り抜き]**」をクリックします。
3. ビデオの隅にあるハンドルをドラッグして、目的の切り抜きを作成するか、必要に応じて既存の画面サイズの中から選択します。
4. ビデオをミュートするかミュート解除するかを選択できます。
5. 「**[!UICONTROL 適用]**」をクリックします。
   ![Adobe Express を使用したビデオの切り抜き](/help/using/assets/adobe-express-crop-video.png)

   切り抜いたビデオはダウンロードできます。 編集したアセットは、同じアセットの新しいバージョンとして保存することも、新しいアセットとして保存することもできます。![Adobe Expressでビデオを保存](/help/using/assets/adobe-express-save-video.png)

### ビデオのサイズ変更 {#resize-video-using-express}

一般的に、DAMの最終的なビデオコンテンツは、特定のチャネルに配信するためにサイズを変更する必要があります。[!DNL Assets Essentials] 一般的なソーシャルチャネルに必要なサイズに合わせてビデオのサイズを簡単に変更でき、カスタム解像度にもサイズを変更できます。 [!DNL Assets Essentials] を使用してビデオをサイズ変更するには、次の手順を実行します。

1. ビデオを選択し、「**[!UICONTROL 編集]**」をクリックします。
2. 左側のパネルにあるクイックアクションから「**[!UICONTROL ビデオをサイズ変更]**」をクリックします。
3. ドロップダウンリストの&#x200B;**[!UICONTROL サイズ変更]**&#x200B;の下にあるソーシャルメディアプラットフォームから適切な寸法を選択します。 または、ビデオの隅にあるハンドルをドラッグして、目的の切り抜きを作成します。
4. 必要に応じて、「**[!UICONTROL ビデオの拡大・縮小]**」フィールドを使用してビデオを拡大・縮小します。
5. ビデオをミュートするかミュート解除するかを選択できます。
6. 「**[!UICONTROL 適用]**」をクリックし、変更を適用します。
   ![Adobe Express を使用したビデオのサイズ変更](/help/using/assets/adobe-express-resize-video.png)

サイズ変更した画像はダウンロードできます。 編集したアセットを同じアセットの新しいバージョンとして保存するか、新しいアセットとして保存することができます。

### ビデオのトリミング {#trim-video-using-express}

大きなビデオのクリップを使用する必要がある場合は、「ビデオのトリミング」機能を使用して、ビデオの一部を選択してトリミングできます。 次の手順を実行します。

1. ビデオを選択し、「**[!UICONTROL 編集]**」をクリックします。
2. 左側のパネルにあるクイックアクションから「**[!UICONTROL ビデオをトリミング]**」をクリックします。
3. ビデオの開始時間と終了時間を指定して、特定の部分をトリミングします。 または、ビデオの隅にあるハンドルをドラッグして、目的のトリミングを作成します。
4. **[!UICONTROL サイズ]**&#x200B;ドロップダウンリストから適切な寸法を選択します。
5. ビデオをミュートするかミュート解除するかを選択できます。
6. 「**[!UICONTROL 適用]**」をクリックし、変更を適用します。
   ![Adobe Express を使用したビデオのサイズ変更](/help/using/assets/adobe-express-trim-video.png)

トリミングしたビデオはダウンロードできます。 編集したアセットを同じアセットの新しいバージョンとして保存するか、新しいアセットとして保存することができます。

### GIF へのビデオの変換 {#convert-mp4-to-gif-using-express}

Adobe Express を使用すると、MP4 ビデオを GIF 形式にすばやく変換できます。 次の手順を実行します。

1. ビデオを選択し、「**[!UICONTROL 編集]**」をクリックします。
2. 左側のパネルにあるクイックアクションから「**[!UICONTROL GIF に変換]**」をクリックします。
3. 目的の画質に応じて適切なファイルサイズを選択します。 さらに、横、縦、正方形の向きを選択します。
4. ビデオの隅にあるハンドルをドラッグして、目的の切り抜きを作成します。
5. 「**[!UICONTROL 適用]**」をクリックします。

   ![Adobe Express を使用した GIF へのビデオの変換](/help/using/assets/adobe-express-convert-video-to-gif.png)

ビデオは GIF 形式でダウンロードできます。 編集したアセットを同じアセットの新しいバージョンとして保存するか、新しいアセットとして保存することができます。

## 制限事項 {#limitations-video-adobe-express}

* 編集には MP4 形式のビデオのみがサポートされます。

* サポートされるソースファイルの最大サイズは 1GB です。

* サポートされているビデオは、任意の側で46 ピクセルより大きく、3840 ピクセルより小さいサイズです。

* サポートされる web ブラウザーは、Google Chrome、Firefox、Safari、Edgeです。

* この機能は、web ブラウザーの匿名モードでは開くことができません。

### 次の手順 {#next-steps}

* Assets Essentials ユーザーインターフェイスの「[!UICONTROL フィードバック]」オプションを使用して、製品に関するフィードバックを提供する

* 右側のサイドバーにある「[!UICONTROL このページを編集]」 ![ページを編集](assets/do-not-localize/edit-page.png) または「[!UICONTROL イシューを記録]」 ![GitHub イシューを作成](assets/do-not-localize/github-issue.png) を使用してドキュメントのフィードバックを提供する

* [カスタマーケア](https://experienceleague.adobe.com/ja?support-solution=General#support)に問い合わせる

>[!MORELIKETHIS]
>
>* [Assets Essentialsでの画像の編集](/help/using/edit-images.md)
>* [アセットのプレビュー](/help/using/navigate-view.md#preview-assets)
