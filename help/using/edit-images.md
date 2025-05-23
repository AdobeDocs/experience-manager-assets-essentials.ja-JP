---
title: 画像の編集
description: ' [!DNL Adobe Express]  を利用したオプションを使用して画像を編集し、更新した画像をバージョンとして保存します。'
role: User
exl-id: fc21a6ee-bf23-4dbf-86b0-74695a315b2a
source-git-commit: 53f638e0dc934f2a4134acb89713b5d4828c8d1f
workflow-type: ht
source-wordcount: '1182'
ht-degree: 100%

---

# [!DNL Assets Essentials] での画像の編集 {#edit-images-in-assets-essentials}

Assets Essentials UI では、UI に統合された Adobe Express を活用した基本的な画像編集を行うことができます。この編集には、サイズ変更、背景の削除、切り抜き、JPEG 形式と PNG 形式間の変換が含まれます。また、Essentials UI に埋め込まれた Adobe Express インターフェイスを通じて高度な編集を行うこともできます。

画像の編集後、新しい画像を新しいバージョンとして保存できます。 バージョン管理により、必要に応じて後で元のアセットに戻すことができます。 画像を編集するには、[プレビューを開き](https://experienceleague.adobe.com/ja/docs/experience-manager-assets-essentials/help/navigate-view#preview-assets)、「**画像を編集**」をクリックします。

>[!NOTE]
>
>Adobe Express を使用すると、PNG および JPEG ファイルタイプの画像を編集できます。

<!--The editing actions that are available are Spot healing, Crop and straighten, Resize image, and Adjust image.-->

## 画像の編集 {#edit-images}

[Assets Essentials UI](https://experience.adobe.com/#/assets) のリンクを使用し、適切なリポジトリを選択して、Assets Essentials UI に移動します。アクセス権を取得するには、組織の管理者にお問い合わせください。
その他の参照情報について詳しくは、[Adobe Experience Manager Assets Essentials 使用の基本を学ぶ](https://experienceleague.adobe.com/ja/docs/experience-manager-assets-essentials/help/get-started)、[ユーザーインターフェイスについて](https://experienceleague.adobe.com/ja/docs/experience-manager-assets-essentials/help/navigate-view)、[Assets Essentials のユースケース](https://experienceleague.adobe.com/ja/docs/experience-manager-assets-essentials/help/get-started#use-cases)および[既知の問題](https://experienceleague.adobe.com/ja/docs/experience-manager-assets-essentials/help/release-notes)を参照してください。

### Adobe Express を使用した Essentials UI での画像編集{#edit-images-using-adobe-express}

>[!CONTEXTUALHELP]
>id="assets_express_integration"
>title="Adobe Express の統合"
>abstract="AEM Assets 内で直接使用できる Adobe Express を活用した、簡単で直感的な画像編集ツールにより、コンテンツの再利用性を高め、コンテンツの速度を向上させます。"

Essentials UI に移動したら、「**アセット**」をクリックし、画像を選択して、上部のパネルから「**編集**」をクリックします。新しい画面には、サイズ変更、背景の削除、切り抜き、JPEG 形式と PNG 形式間の変換など、Adobe Express を活用した使用可能な編集オプションが表示されます。

#### 画像のサイズ変更 {#resize-image-using-express}

画像を特定のサイズに変更するのが一般的なユースケースです。 Assets Essentials では、特定の写真サイズに対応する新しい解像度を事前に計算し、一般的な写真サイズに合わせて画像サイズをすばやく変更できます。 Assets Essentials インターフェイス内で画像サイズを変更するには、次の手順に従います。

1. 左側のパネルから「**画像のサイズを変更**」をクリックします。ダイアログボックスに、Adobe Express を活用した画像のサイズ変更機能が表示されます。
2. サイズ変更ドロップダウンリストから適切なソーシャルメディアプラットフォームを選択し、表示されるオプションから画像サイズを選択します。
3. 必要に応じて、「**画像の拡大・縮小**」フィールドを使用して画像を拡大・縮小します。
4. 「**適用**」をクリックし、変更を適用します。
   ![Adobe Express を使用した画像の編集](/help/using/assets/adobe-express-resize-image.png)

   編集した画像はダウンロードできます。 編集したアセットを同じアセットの新しいバージョンとして保存するか、新しいアセットとして保存することができます。
   ![Adobe Express を使用した画像の保存](/help/using/assets/adobe-express-resize-save.png)

#### 背景を削除 {#remove-background-using-express}

次の手順に従って、画像から背景を削除できます。

1. 左側のパネルから「**背景を削除**」をクリックします。 Experience Manager Assets では、背景のない画像が表示されます。
2. 「**[!UICONTROL 適用]**」をクリックし、変更を適用します。
   ![Adobe Express を使用した画像の保存](/help/using/assets/adobe-express-remove-background.png)

   編集した画像はダウンロードできます。 編集したアセットを同じアセットの新しいバージョンとして保存するか、新しいアセットとして保存することができます。

#### 画像を切り抜き {#crop-image-using-express}

埋め込まれた [!DNL Adobe Express] クイックアクションを使用すると、画像を完璧なサイズに簡単に変換できます。

1. 左側のパネルから「**[!UICONTROL 画像の切り抜き]**」をクリックします。
2. 画像の隅にあるハンドルをドラッグして、目的の切り抜きを作成します。
3. 「**[!UICONTROL 適用]**」をクリックします。
   ![Adobe Express を使用した画像の保存](/help/using/assets/adobe-express-crop-image.png)
切り抜いた画像はダウンロードできます。 編集したアセットを同じアセットの新しいバージョンとして保存するか、新しいアセットとして保存することができます。

#### JPEG を PNG に変換 {#Convert-JPEG-to-PNG}

Adobe Express を使用すると、JPEG 画像形式と PNG 画像形式間ですばやく変換できます。 以下の手順を実行します。

1. 左側のペインで「**JPEG から PNG**」または「**PNG から JPEG**」をクリックします。
   ![Adobe Express を使用した PNG への変換](/help/using/assets/adobe-express-convert-image.png)
2. 「**[!UICONTROL ダウンロード]**」をクリックします。

#### 制限事項 {#limitations-adobe-express}

* サポートされる画像解像度：最小 - 50 ピクセル、最大 - ディメンションあたり 6000 ピクセル。
* サポートされるファイルの最大サイズ：17 MB。

### Adobe Express 埋め込みエディターでの画像編集 {#edit-images-in-adobe-express-embedded-editor}

Express の使用権限を持つユーザーは、Assets Essentials UI 内に埋め込まれた Express エディターを使用して、コンテンツを編集し、Adobe Firefly から GenAI を使用して簡単に新しいコンテンツを作成できます。この機能により、コンテンツの再利用が高まり、コンテンツベロシティが加速されます。また、定義済みの要素を使用して、アセットの見栄えを良くしたり、数回クリックするだけで画像を編集するクイックアクションを実行したりすることもできます。

![Essentials UI で表現](/help/using/assets/express-in-essentials-ui.jpg)
Adobe Express 埋め込みエディター内で画像を編集するには、次の手順に従います。

1. [AEM Assets Essentials UI](https://experience.adobe.com/#/assets) のリンクを使用し、適切なリポジトリを選択し、AEM Assets Essentials UI に移動します。
1. 「**Assets**」をクリックし、フォルダーを入力して画像を選択します。
1. 「**Adobe Express で開く**」をクリックします。 画像が Express キャンバスで開きます。
1. 画像に必要な編集を行います。
1. プロジェクトでさらにページを追加する必要がある場合は、「**追加**」をクリックし、アセットを選択します。次に、フォルダーを入力し、キャンバスページに取り込む画像を選択して、画像に必要な編集を行います。
1. 1 つ以上のアセットを保存するには、「**保存**」をクリックします。保存ダイアログボックスに、保存オプションが表示されます。保存オプションを選択するには、要件に合わせて、次のいずれかの手順に従います。
   1. 単一ページを保存するには、「**バージョンとして保存**」をクリックして、画像を新しいバージョンとして（元の形式を保持して）書き出し、同じフォルダーに保存します。

   1. 単一ページを保存するには、「**新しいアセットとして保存**」をクリックして、アセットを異なる形式に書き出し、新しいアセットとして任意のフォルダーに保存します。

   1. 複数のページから単一ページを保存するには、「**バージョンとして保存**」をクリックして、元の形式で元の場所にアセットを保存します。

   1. 複数のページを保存する場合または複数のページの中から単一ページを保存するには、「**新しいアセットとして保存**」をクリックします。このアクションにより、単一または複数のアセットを任意のフォルダーに書き出し、元の形式または別の形式で新しいアセットとして保存できます。

1. 保存ダイアログボックスで、次の手順を実行します。
   1. 「**名前を付けて保存**」フィールドにファイルの名前を入力します。
   1. 宛先フォルダーを選択します。
   1. オプション：プロジェクトまたはキャンペーンの名前、キーワード、チャネル、時間枠、地域などの詳細を指定します。
1. 「**バージョンとして保存**」または「**新しいアセットとして保存**」をクリックして 1 つ以上のアセットを保存します。

#### Express エディターでの画像編集の制限事項 {#limitations-of-editing-images-in-the-express-editor}

* サポートされているファイルタイプ：JPEG または PNG。
* サポートされるファイルの最大サイズ：40 MB。
* サポートされている幅と高さの範囲：50～8000 ピクセル。
* ページをリロードすると、ソースフォルダーに最新の保存済みアセットが表示されます。

### Adobe Express を使用した新しいアセットの作成 {#create-new-assets-using-embedded-editor}

Assets Essentials では、Adobe Express 埋め込みエディターを使用して、新しいテンプレートを最初から作成できます。Adobe Express を使用して新しいアセットを作成するには、次の手順を実行します。

1. **マイワークスペース**&#x200B;に移動し、上部の Adobe Express 内に表示される Adobe Express バナー内の「**作成**」をクリックします。 Adobe Express の空白のキャンバスが Assets Essentials ユーザーインターフェイス内に表示されます。
1. [テンプレート](https://helpx.adobe.com/jp/express/using/work-with-templates.html)を使用してコンテンツを作成します。 それ以外の場合は、自分のアイテムに移動して既存のコンテンツを変更します。
1. 編集が完了したら、「**保存**」をクリックします。
1. 作成したアセットの宛先パスを指定し、「**新しいアセットとして保存**」をクリックします。

#### 制限事項 {#limitations}

* 変更できるのは、`JPEG` および `PNG` 形式タイプの画像のみです。
* アセットサイズは 40 MB 未満にする必要があります。
* 画像は、`PDF`、`JPEG` または `PNG` 形式で保存できます。

<!--
## Edit images using [!DNL Adobe Photoshop Express] {#edit-using-photoshop-express}

<!--
After editing an image, you can save the new image as a new version. Versioning helps you to revert to the original asset later, if needed. To edit an image, [open its preview](/help/using/navigate-view.md#preview-assets) and click **[!UICONTROL Edit Image]** ![edit icon](assets/do-not-localize/edit-icon.png) from the rail on the right.

![Options to edit an image](assets/edit-image2.png)

*Figure: The options to edit images are powered by [!DNL Adobe Photoshop Express].*
-->
<!--
### Spot heal images {#spot-heal-images-using-photoshop-express}

If there are minor spots or small objects on an image, you can edit and remove the spots using the spot healing feature provided by Adobe Photoshop.

The brush samples the retouched area and makes the repaired pixels blend seamlessly into the rest of the image. Use a brush size that is only slightly larger than the spot you want to fix.

![Spot healing edit option](assets/edit-spot-healing.png)

<!-- 
TBD: See if we should give backlinks to PS docs for these concepts.
For more information about how Spot Healing works in Photoshop, see [retouching and repairing photos](https://helpx.adobe.com/jp/photoshop/using/retouching-repairing-images.html). 
-->
<!--
### Crop and straighten images {#crop-straighten-images-using-photoshop-express}

Using the crop and straighten option that you can do basic cropping, rotate image, flip it horizontally or vertically, and crop it to dimensions suitable for popular social media websites.

To save your edits, click **[!UICONTROL Crop Image]**. After editing, you can save the new image as a version.

![Option to crop and straighten](assets/edit-crop-straighten.png)

Many default options let you crop your image to the best proportions that fit various social media profiles and posts.

### Resize image {#resize-image-using-photoshop-express}

You can view the common photo sizes in centimeters or inches to know the dimensions. By default, the resizing method retains the aspect ratio. To manually override the aspect ratio, click ![](assets/do-not-localize/lock-closed-icon.png).

Enter the dimensions and click **[!UICONTROL Resize Image]** to resize the image. Before you save the changes as a version, you can either undo all the changes done before saving by clicking [!UICONTROL Undo] or you can change the specific step in the editing process by clicking [!UICONTROL Revert].

![Options when resizing an image](assets/resize-image.png)

### Adjust image {#adjust-image-using-photoshop-express}

[!DNL Assets Essentials] lets you adjust the color, tone, contrast, and more, with just a few clicks. Click **[!UICONTROL Adjust image]** in the edit window. The following options are available in the right sidebar:

* **Popular**: [!UICONTROL High Contrast & Detail], [!UICONTROL Desaturated Contrast], [!UICONTROL Aged Photo], [!UICONTROL B&W Soft], and [!UICONTROL B&W Sepia Tone].
* **Color**: [!UICONTROL Natural], [!UICONTROL Bright], [!UICONTROL High Contrast], [!UICONTROL High Contrast & Detail], [!UICONTROL Vivid], and [!UICONTROL Matte].
* **Creative**: [!UICONTROL Desaturated Contrast], [!UICONTROL Cool Light], [!UICONTROL Turquoise & Red], [!UICONTROL Soft Mist], [!UICONTROL Vintage Instant], [!UICONTROL Warm Contrast], [!UICONTROL Flat & Green], [!UICONTROL Red Lift Matte], [!UICONTROL Warm Shadows], and [!UICONTROL Aged Photo].
* **B&W**: [!UICONTROL B&W Landscape], [!UICONTROL B&W High Contrast], [!UICONTROL B&W Punch], [!UICONTROL B&W Low Contrast], [!UICONTROL B&W Flat], [!UICONTROL B&W Soft], [!UICONTROL B&W Infrared], [!UICONTROL B&W Selenium Tone], [!UICONTROL B&W Sepia Tone], and [!UICONTROL B&W Split Tone].
* **Vignetting**: [!UICONTROL None], [!UICONTROL Light], [!UICONTROL Medium], and [!UICONTROL Heavy].

![Adjust image by editing](assets/adjust-image.png)

<!--
TBD: Insert a video of the available social media options.
-->

### 次の手順 {#next-steps}

* Assets Essentials ユーザーインターフェイスの「[!UICONTROL フィードバック]」オプションを使用して製品に関するフィードバックを提供する

* 右側のサイドバーにある「[!UICONTROL このページを編集]」（![ページを編集](assets/do-not-localize/edit-page.png)）または「[!UICONTROL 問題を記録] 」（![GitHub イシューを作成](assets/do-not-localize/github-issue.png)）を使用してドキュメントに関するフィードバックを提供する

* [カスタマーケア](https://experienceleague.adobe.com/ja?support-solution=General&amp;lang=ja#support)に問い合わせる

>[!MORELIKETHIS]
>
>* [アセットのバージョン履歴の表示](/help/using/navigate-view.md)
