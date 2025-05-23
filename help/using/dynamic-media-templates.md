---
title: Dynamic Media テンプレートの管理方法
description: WYSIWYG テンプレートエディターを使用して Dynamic Media テンプレートを作成し、複数の画像とテキストレイヤーを含めてバナーやチラシをすばやく作成し、ダウンストリームアプリケーションで使用する方法について説明します。
hide: true
role: User
exl-id: 07de648e-4ae2-4524-8e05-3cf10bb6006d
source-git-commit: 8bf4babf2fefb8735b14eb4d4cb08205c54a77bb
workflow-type: tm+mt
source-wordcount: '2810'
ht-degree: 93%

---

# Dynamic Media テンプレート{#dynamic-media-templates}

| [検索のベストプラクティス](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices) | [メタデータのベストプラクティス](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices) | [コンテンツハブ](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview) | [AEM Assets 開発者向けドキュメント](https://developer.adobe.com/experience-cloud/experience-manager-apis/) |
| ------------- | --------------------------- |---------|-----|

>[!CONTEXTUALHELP]
>id="assets_dm_templates"
>title="Dynamic Media テンプレートの管理"
>abstract="使いやすいWYSIWYG インターフェイスで画像バナーやテキストバナーをその場で作成およびパーソナライズし、Dynamic Media URL をファーストパーティまたはサードパーティのアプリケーションに埋め込むことで、非常に魅力的なエクスペリエンスを実現します。 試してみて。"
>additional-url="https://images-tv.adobe.com/mpcv3/4477/b74738ca-888c-4a37-9a9e-14fabd68ee45_1738206841.854x480at800_h264.mp4" text="ビデオを観る"

WYSIWYG テンプレートエディターを使用して Dynamic Media テンプレートを作成し、複数の画像とテキストレイヤーを含めてバナーやチラシをすばやく作成し、ダウンストリームアプリケーションで使用します。また、テンプレートに含まれる画像やテキストレイヤーにパラメーターを追加し、[Dynamic Media URL](https://experienceleague.adobe.com/ja/docs/commerce-admin/content-design/wysiwyg/storage/catalog-urls-dynamic-media) を使用して、これらのレイヤーの値をリアルタイムで更新することもできます。

主な機能は次のとおりです。

* **Dynamic Media WYSIWYG テンプレートエディター：**&#x200B;画像とテキストレイヤーを使用してカスタマイズ可能なバナーを作成します。
* **レイヤーのパラメーター化：**&#x200B;レイヤーの動的なキーと値のペアを定義して、リアルタイム更新を実現します。
* **Dynamic Media URL のサポート：**&#x200B;テンプレートに Dynamic Media URL を使用し、ファーストパーティまたはサードパーティのアプリケーションからのパーソナライズされた値を統合します。
* **レイヤー表示コントロール：**&#x200B;必要に応じて、レイヤーを動的に非表示または表示します。
* **スマートテキストのサイズ変更：**&#x200B;指定された領域に合わせて、テキストのサイズを自動的に調整します。

Dynamic Media テンプレートの主なメリットには、次のようなものがあります。

* **1:1 パーソナライゼーションを最適化：**&#x200B;リアルタイムの顧客シグナルに合わせて、コンテンツを調整します。
* **手作業を削減：**&#x200B;コンテンツの作成と管理を自動化および高速化します。
* **一貫したオムニチャネルエクスペリエンスを確保：**&#x200B;チャネル全体でブランドの一貫性を維持します。
* **コンテンツを効果的に再利用：** 1 回使用のコンテンツを避け、動的なパラメーター化されたテンプレートを使用して拡大します。
* **リスクを軽減：**&#x200B;価格、割引、リンクをリアルタイムで更新します。
* **顧客エンゲージメントの強化：** インタラクティブで文脈的に関連性の高いエクスペリエンスを促進します。

>[!NOTE]
>
>セキュリティの強化の SKU を購読しているお客様は、そのクラウドサービスプログラムで Dynamic Media テンプレートを含む Dynamic Media 機能を使用できません。

## 始める前に{#prerequisites-for-dynamic-media-wysiwyg-template}

Dynamic Media テンプレートを作成するには、次の操作が必要です。

1. Dynamic Media にアクセスします。
1. [AEM Assets インスタンスで使用可能な画像を Dynamic Media と同期して、テンプレートの作成に使用します](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm)。
1. タッチ UI で次の内容を確認しました。
   * **[!UICONTROL Dynamic Media設定を編集ページ]** で、**[!UICONTROL デフォルトで無効]** に設定されている **[!UICONTROL Dynamic Media同期モード]** が、すべてのAEM フォルダーに適用されない（**[!UICONTROL すべてのコンテンツを同期]** がオフになっている）。 詳しくは [Dynamic MediaCloud Serviceの設定 ](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm) を参照してください。
   * **[!UICONTROL Dynamic Media同期モード]** は、作成後にテンプレートを保存する出力先フォルダーまたはサブフォルダーに対して **[!UICONTROL サブフォルダーで有効にする]** に設定されています。 詳しくは [Dynamic MediaCloud Serviceの設定 ](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/dynamicmedia/config-dm) を参照してください。

## Dynamic Media WYSIWYG テンプレートの作成{#how-to-create-dynamic-media-wysiwyg-template}

DM テンプレートを作成するには、次の手順に従います。

1. [空のキャンバスを作成](#create-a-canvas)
1. [キャンバスに画像を追加](#add-images-to-the-canvas)
1. [キャンバスにテキストレイヤーを追加](#add-text-to-the-canvas)
1. [レイヤーを編集または削除](#edit-or-delete-a-layer)
1. [レイヤーをパラメーター化](#parameterise-a-layer)

### 空のキャンバスを作成{#create-a-canvas}

空のキャンバスを作成するには、次の手順を実行します。

1. Assets Essentialsに移動し、左側のパネルで使用可能な **[!UICONTROL Dynamic Media Assets]** をクリックします。

   ![Dynamic Media テンプレート](/help/using/assets/DM-Assets1.png)

1. 「**[!UICONTROL テンプレートを作成]**」をクリックしてテンプレートを Dynamic Media アセットに保存するか、フォルダーに移動して「**[!UICONTROL テンプレートを作成]**」をクリックし、そのフォルダー内にテンプレートを保存します。**[!UICONTROL 新規テンプレート]**&#x200B;ダイアログボックスが表示されます。
   ![リアルタイムでカスタマイズできる動的テンプレートの作成方法](/help/using/assets/new-template.png)
**[!UICONTROL Dynamic Media アセット]**&#x200B;の下に[フォルダーを作成](/help/using/add-delete.md)するには、**[!UICONTROL アセット]**&#x200B;の下にフォルダーを作成します。**[!UICONTROL アセット]**&#x200B;の下のフォルダーツリーは、**[!UICONTROL Dynamic Media アセット]**&#x200B;の下にレプリケートされます。
1. テンプレート名を指定し、キャンバスの幅と高さを定義して、「**[!UICONTROL 作成]**」をクリックします。空白のキャンバスが表示され、テンプレートの作成に使用するメニューオプションが両側に表示されます。メニューオプションにポインタを合わせると、ツールチップが表示されます。
   ![リアルタイムのカスタマイズ可能なテンプレート](/help/using/assets/blank-canvas-page.png)

>[!NOTE]
>
> 許容される幅と高さの範囲は 50～5000 です。

**右側のパネルのメニューオプション：**&#x200B;これらのオプションを使用して、必要な画像とテキストレイヤーをキャンバスに追加します。

* ![DM テンプレート](/help/using/assets/add-image.svg)：クリックして、画像をキャンバスに追加します。
* ![カスタマイズ可能なテンプレート](/help/using/assets/add-text.svg)：クリックして、テキストをキャンバスに追加します。
* ![カスタマイズ可能なテンプレート](/help/using/assets/show-layers-list.svg)：クリックして、キャンバス上のすべてのレイヤー（画像とテキスト）のリストを表示します。キャンバスに追加されたすべての画像とテキストは、個別のレイヤーとして表されます。

**左側のパネルのメニューオプション：**&#x200B;以下に示すように、一般的なエディターアクションにこれらのオプションを使用します。

* ![DM テンプレート](/help/using/assets/layer-selector.svg)：レイヤーを選択します。
* ![すぐにカスタマイズできるテンプレートを作成](/help/using/assets/undo.svg)：クリックして最後のアクションを取り消すか、**Ctrl** + **Z** キー（Windows）または **Cmd** + **Z** キー（Mac）を押します。
* ![バナーをすばやく作成するテンプレート](/help/using/assets/redo.svg)：クリックして最後のアクションをやり直すか、**Ctrl** + **Y** キー（Windows）または **Cmd** + **Y** キー（Mac）を押します。
* ![チラシをすばやく作成するテンプレート](/help/using/assets/zoomin.svg)：クリックしてキャンバスをズームインするか、**Ctrl** + **+** キー（Windows）または Cmd + **+** キー（Mac）を押します。
* ![バナーをすばやく作成するテンプレート](/help/using/assets/ZoomOut-1.svg)：クリックしてキャンバスをズームアウトするか、**Ctrl** + **-** キー（Windows）または **Cmd** + **-** キー（Mac）を押します。
* テキストやプロパティが編集されていない場合は、**Backspace** キーまたは **Delete** キーを押すと、選択したレイヤーが削除されます。

テンプレートの作成中にいつでもキャンバスの寸法を編集するには、キャンバスレイヤーで![チラシをすばやく作成するテンプレート](/help/using/assets/show-layers-list.svg)**／**&#x200B;その他のオプション（![](/help/using/assets/three-dots.svg)）をクリックします。
![](/help/using/assets/edit-canvas1.png)

>[!NOTE]
>
> テンプレートでは、キャンバスを含めて最大 20 個のレイヤーを使用できます。

### キャンバスに画像を追加{#add-images-to-the-canvas}

キャンバスに画像を追加するには、次の手順を実行します。

1. 「![バナーをすぐに作成](/help/using/assets/add-image.svg)」をクリックして、[アセットセレクター](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/manage/asset-selector/overview-asset-selector)パネルを表示します。パネルには、Dynamic Media に同期される AEM Assets インスタンス内の画像が表示されます。
1. パネルを参照するか、検索バーでキーワードを使用して、特定の画像を見つけます。
1. 画像をキャンバス上にドラッグ＆ドロップして使用します。キャンバス上のレイヤーのサイズ変更や再配置について詳しくは、[**[!UICONTROL プロパティパネル]**](#reposition-resize-delete-a-layer)を参照してください。
   ![数秒以内にバナーを作成](/help/using/assets/add-image-to-canvas.png)

### キャンバスにテキストレイヤーを追加{#add-text-to-the-canvas}

キャンバスにテキストレイヤーを追加するには、次の手順を実行します。

1. 「![新しいバナーをすばやく作成](/help/using/assets/add-text.svg)」をクリックして、キャンバスにテキストレイヤーを追加し、プロパティパネルを開きます。
1. レイヤーを選択し、テキストをクリックして更新します。
1. プロパティパネルで&#x200B;**[!UICONTROL スマートテキストのサイズ変更]**&#x200B;を有効にすると、テキストの長さとフォントサイズが自動的に調整され、指定された領域に最適に収まります。
   ![カスタマイズ可能な最適なバナー](/help/using/assets/add-text-layer.png)

レイヤーの再配置、サイズ変更、回転または削除について詳しくは、[**[!UICONTROL プロパティパネル]**](#reposition-resize-delete-a-layer)を参照してください。パネルの「**[!UICONTROL テキスト]**」セクションの下にある各フィールドの値を変更して、テキストを目的のフォント、サイズ、カラー、スタイル、位置（レイヤー内）に書式設定します。

>[!NOTE]
>
> デフォルトの Adobe Sans F2 フォントファミリー以外のフォントを使用するには、フォントファイルを AEM Assets および Dynamic Media にアップロードして公開する必要があります。インスタンスに古いフォントがある場合、テンプレートエディターで表示するには、必ず[再処理](/help/using/reprocessing.md)します。

### レイヤーを編集または削除 {#edit-or-delete-a-layer}

キャンバスレイヤーを編集または削除するには、次の手順を実行します。

1. 「![動的更新をサポートするテンプレート](/help/using/assets/show-layers-list.svg)」をクリックして、キャンバスまたはレイヤーリストからレイヤーを選択します。
1. 「**その他のオプション**」（![リアルタイムの更新をサポートするテンプレート](/help/using/assets/three-dots.svg)）をクリックして、レイヤーを編集または削除します。
1. 「**[!UICONTROL 削除]**」をクリックして、レイヤーを削除します。
1. 「**[!UICONTROL 編集]**」をクリックして、[**[!UICONTROL プロパティパネル]**](#reposition-resize-delete-a-layer)を使用してレイヤーを編集します。
   ![迅速なバナー作成](/help/using/assets/edit-delete-layer.png)

### プロパティパネル{#properties-panel}

レイヤーのプロパティパネルに移動するには：

1. 「![迅速なコンテンツ作成](/help/using/assets/show-layers-list.svg)」をクリックします。
1. リストからレイヤーを選択します。

このパネルには、キャンバスプレーン上のレイヤーの中心点の位置（X 値と Y 値）とレイヤーの寸法（幅と高さ）が、テキストの書式設定オプションと共に表示されます。

![迅速なコンテンツ作成](/help/using/assets/properties-panel.png)

レイヤーのプロパティパネルからキャンバス上の別のレイヤーを選択して、そのプロパティパネルに移動します。


#### レイヤーの再配置、サイズ変更、回転または削除{#reposition-resize-delete-a-layer}

テキストまたは画像レイヤーを編集するには、次の一般的なレイヤー編集アクションを参照してください。

* **レイヤーを再配置：**&#x200B;レイヤーをドラッグして、キャンバス上の任意の場所に移動します。このアクションにより、プロパティパネルの X 値と Y 値が更新されます。
* **レイヤーをサイズ変更：**&#x200B;レイヤーを選択し、エッジハンドルをドラッグしてサイズ変更します。このアクションにより、プロパティパネルの W（幅）値と H（高さ）値が更新されます。
* **レイヤーを回転：**&#x200B;レイヤーの上に垂直に配置された正方形のハンドルをドラッグして、レイヤーを中心に回転させます。このアクションにより、プロパティパネルの角度値が更新されます。
* **レイヤーを削除**：**Backspace** キーまたは **Delete** キーを押し、「**[!UICONTROL 確認]**」をクリックして、選択したレイヤーを削除します。

#### テキストの書式設定オプション{#text-formatting-options-on-properties-panel}

パネルの「**[!UICONTROL テキスト]**」セクションの下にある各フィールドの値を変更して、テキストを目的のフォント、サイズ、カラー、スタイル、位置（レイヤー内）に書式設定します。

**[!UICONTROL スマートテキストのサイズ変更]**：フォントサイズと長さをスマートに調整して、指定された領域にテキストを最適に収めるには、**[!UICONTROL スマートテキストのサイズ変更]**（[コピーフィット](https://experienceleague.adobe.com/ja/docs/dynamic-media-developer-resources/image-serving-api/image-serving-api/http-protocol-reference/text-formatting/r-copy-fitting)）を必ず含めてください。この機能により、テキストのオーバーフローが防止され、テキストの下部にある余分なスペースが最小限に抑えられます。
![すぐにコンテンツを作成](/help/using/assets/smart-text-resize.png)

### レイヤーをパラメーター化 {#parameterise-a-layer}

複数の画像とテキストのレイヤーを含むテンプレートを作成したら、選択したレイヤーをパラメーター化します。レイヤーまたはそのプロパティをパラメーター化すると、キーと値のペア（パラメーターとも呼ばれる）が取得されます。このパラメーターをテンプレートの URL に含めると、レイヤーの位置、サイズまたはコンテンツをリアルタイムで更新できるので、テンプレートのカスタマイズをすぐに行うことができます。

レイヤーをパラメーター化するには：

1. 「![即時コンテンツ作成](/help/using/assets/show-layers-list.svg)」をクリックし、レイヤーを選択して「**[!UICONTROL パラメーター]**」をクリックします。**[!UICONTROL パラメーター]**&#x200B;パネルが表示されます。
1. **[!UICONTROL パラメーターを含める]**&#x200B;を切り替えて、プロパティをパラメーター化します。パラメーター化後のプロパティの動作について詳しくは、[こちら](#parameterisation-options-or-allowed-parameters)を参照してください。
1. **オプション：**&#x200B;パラメーター名を変更します。パラメーター名には、レイヤー名の後に接尾辞が続きます。選択したレイヤーでは、そのすべてのパラメーター化されたプロパティは同じレイヤー名を共有し、その後に様々な接尾辞が続きます。セマンティックの命名規則に従ってレイヤー名を変更すると、URL にパラメーターを含める際に、パラメーター名自体がレイヤーのコンテンツや目的についての説明となります。
1. 「**[!UICONTROL 保存]**」をクリックします。
   ![即時コンテンツ作成](/help/using/assets/parameterise-a-layer.png)
画像とテキストレイヤーのパラメーターパネルを切り替えるには、キャンバス上でレイヤーを選択し、「**[!UICONTROL パラメーター]**」をクリックします。

#### パラメーターパネルオプション {#parameterisation-options-or-allowed-parameters}

パラメーター化されたプロパティをテンプレートの URL に URL パラメーターとして含めることで、URL を使用してテンプレートをリアルタイムで編集できます。

**画像パラメーター：**

**X：**&#x200B;URL のパラメーターの値を変更して、テンプレートプレーンの X 軸に平行な中心線に沿ってレイヤーを水平方向に移動する場合に含めます。
**Y：**&#x200B;URL のパラメーターの値を変更して、テンプレートプレーンの Y 軸に平行な中心線に沿ってレイヤーを垂直方向に移動する場合に含めます。
**幅：**&#x200B;URL のパラメーターの値を変更して、レイヤーの幅を調整する場合に含めます。
**高さ：**&#x200B;URL のパラメーターの値を変更して、レイヤーの高さを調整する場合に含めます。
**非表示：**&#x200B;0（表示）と 1（非表示）を使用して、テンプレートのレイヤーを非表示または表示する場合に含めます。
**ソース：** URL のパラメーターの値の画像パスを変更して、レイヤーの画像を新しい画像に置き換える場合に含めます。

**テキストの書式設定パラメーター：**

URL のパラメーター値を更新して、URL からテキスト、フォント、カラー、サイズを編集するには、以下のパラメーターを含めます。

**テキスト：**&#x200B;URL からテキストを更新する場合に含めます。
**フォントファミリー：**&#x200B;URL からテキストのフォントを更新する場合に含めます。
**フォントサイズ：**&#x200B;URL からテキストのフォントサイズを更新する場合に含めます。
**テキストカラー：** URL からテキストのフォントカラーを更新する場合に含めます。

### レイヤーをグループ化して同時に表示をコントロール{#group-layers}

テンプレートの柔軟性を維持するもう 1 つの方法は、単一のパラメーター名を使用して複数のレイヤーを制御することです。この戦略は、表示（レイヤーを非表示または表示）パラメーターで、単一のテンプレートからデザインまたはグラフィックを更新する場合に役立ちます。

複数のレイヤーの非表示パラメーター（![高速コンテンツ作成](/help/using/assets/Visibility-icon.svg)）に同じ名前を割り当て、同時に非表示または表示できるようにするには、次の手順に従います。

1. レイヤーの[**[!UICONTROL プロパティパネル]**](#parameterise-a-layer)に移動します。
1. 以前にパラメーター化していない場合は、**[!UICONTROL 非表示]**&#x200B;パラメーターを切り替えます。
1. **オプション：**&#x200B;非表示パラメーターの名前を変更します。
1. 非表示パラメーターの名前をコピーします。
1. キャンバスから他のレイヤーを選択して、そのレイヤーのパラメーターパネルに移動し、パラメーター化されていない場合は、**[!UICONTROL 非表示]**&#x200B;パラメーターを切り替えます。
1. **[!UICONTROL 非表示パラメーター]**&#x200B;の名前を、コピーした名前に置き換えます。
1. 「**[!UICONTROL 保存]**」をクリックして、レイヤーをグループ化します。
1. [**[!UICONTROL プレビューと公開]**](#preview-and-publish-template-and-copy-template-deliver-url)の節の手順 3 と 4 を実行して、変更を確認します。

## テンプレートをプレビューおよび公開し、配信 URL をコピー{#preview-and-publish-template-and-copy-template-deliver-url}

テンプレートをプレビューおよび公開し、配信 URL をコピーするには、次の手順を実行します。

1. キャンバスページで、「**[!UICONTROL プレビュー]**」をクリックします。また、**[!UICONTROL Assets Essentials]**&#x200B;**>**&#x200B;**[!UICONTROL Dynamic Media Assets]**&#x200B;**> に移動して、テンプレートを見つけて選択します** **>** 「**[!UICONTROL テンプレートを編集]**&#x200B;**>** 「**[!UICONTROL プレビュー]**」をクリックします。 プレビューページには、テンプレート、そのパラメーター（パラメーター化されたレイヤとプロパティ）、公開ステータスおよび「**[!UICONTROL 公開]**」オプションが表示されます。
1. **[!UICONTROL テンプレートパラメーター]**&#x200B;パネルからパラメーターを選択して値を編集すると、プレビューの対応するテンプレートレイヤーのコンテンツ、サイズ、位置、またはテキストの書式設定が即座に更新されます。例：
   1. テキストレイヤーを選択してテキストを編集するか、
   1. 画像レイヤーを選択し、「![その場でコンテンツを作成](/help/using/assets/add-image.svg)」をクリックし、アセットセレクターから画像を選択して、「**[!UICONTROL 更新]**」をクリックします。

   テンプレートはすぐに更新され、編集されたテキストが表示され、以前の画像が新しい画像に置き換えられます。また、画像パラメーターの値には、新しい画像のパスが反映されます。同様に、レイヤーの値を調整してサイズ変更すると、その変更がリアルタイムでテンプレートに適用されます。
1. リストから[グループ化されたレイヤー](#group-layers)の非表示パラメーターを選択して、テンプレート内でまとめて表示または非表示にします。
1. **オプション：**&#x200B;**[!UICONTROL 非表示]**&#x200B;パラメーターの値を 0 と 1 の間で変更し、「**[!UICONTROL 更新]**」をクリックして変更を確認します。同じ非表示パラメーターを持つレイヤーは、まとめて非表示または表示されます。同様に、URL からレイヤーの表示をコントロールできます。

   ![その場でのコンテンツの作成](/help/using/assets/dm-templates-publish-status.png)
また、**[!UICONTROL すべてのパラメーターを含める]**&#x200B;を切り替えて、表示されているすべてのパラメーター値を編集し、テンプレートのプレビューで更新を確認することもできます。
   <br>
1. プレビューページでテンプレートを公開するには、「**[!UICONTROL 公開]**」をクリックして公開を確定します。公開完了メッセージが表示され、公開ステータスが公開済みに更新されます。

>[!NOTE]
>
>テンプレートを公開するには、まずテンプレート画像を公開する必要があります。

### 配信 URL をコピー

**[!UICONTROL プレビュー]**&#x200B;ページで選択したパラメーターは、テンプレートの URL の URL パラメーターになります。

プレビューに表示されている公開済みテンプレートの URL をコピーするには：

1. 「**[!UICONTROL URL をコピー]**」をクリックします。**[!UICONTROL URL をコピー]**&#x200B;ダイアログボックスが表示されます。表示されている URL を選択してコピーします。URL の最初のパラメーターが疑問符&#x200B;**（?）**&#x200B;の後から始まり、キーと値のペアが **$** で始まり **&amp;** で終わることを確認します。キーと値は等号&#x200B;**（=）**&#x200B;で区切られ、キーが左側、値が右側になります。
1. この URL をブラウザーのタブにペーストして、ライブテンプレートを表示します。**プレビューと公開**&#x200B;の節の[手順 2](#preview-and-publish-template-and-copy-template-deliver-url) の説明に従って、URL の必要なパラメーターの値（キーの値）を直接更新して、テンプレートをリアルタイムでカスタマイズします。
1. 製品やサービスの迅速なマーチャンダイジングには、この URL を使用します。この URL を顧客と共有することや、web サイトやダウンストリームのサードパーティアプリケーションに統合してバナーを表示することや、継続的なオファーを反映するようにリアルタイムで更新することができます。

このビデオでは、Dynamic Media テンプレートを段階的に作成する方法について説明します。
>[!VIDEO](https://video.tv.adobe.com/v/3443281)

## URL からテンプレートをリアルタイムで更新{#update-the-template-from-the-url}

URL 内でパラメーターを直接編集するのは面倒な場合があります。簡素化するには：

1. URL をコピーして、メモ帳にペーストします。
1. Cmd + F キー（Mac）または Ctrl + F キー（Windows）を使用して、パラメーター値を見つけて編集します。例：
   * 画像レイヤーの画像パスを置き換えます。
   * レイヤーの寸法と位置を調整します（[パラメーター化](#parameterise-a-layer)されている場合）。
   * テキストレイヤーのテキスト、フォント、カラー、サイズ、位置を編集します。
   * 表示値を 0 と 1 の間で変更します。

この更新された URL をブラウザーにペーストして、変更を表示します。

## テンプレートを編集{#edit-the-template}

テンプレートを編集するには、次の手順に従います。

1. 「Assets Essentials」で、「**[!UICONTROL Dynamic Media Assets]**」をクリックします。
2. テンプレートの場所に移動します。
3. テンプレートを選択します。
4. 「**[!UICONTROL テンプレートを編集]**」をクリックします。テンプレートキャンバスには、テンプレートと、レイヤーパネル内のすべてのレイヤーのリストが表示されます。必要に応じて、テンプレートの編集を開始します。

## 重要な注意点 {#important-points-to-note}

* 動的更新用にパラメーター化された画像レイヤーを含むテンプレートを作成したら、今後の更新を予定している画像がパラメーター化された画像と同じ寸法を共有していることを確認します。これにより、画像がオーバーフローしたり、空のスペースが残ったりすることなく、レイヤー内に完全に収まります。現在、テンプレートは、画像をレイヤーに収める自動寸法調整をサポートしていません。
* テキストレイヤーでは、部分文字列はサポートされません。ユーザーは、テキストレイヤーの部分文字列に異なるフォントプロパティを適用できません。
* 現在、Dynamic Media テンプレートでは複数の Dynamic Media 会社のサポートを使用できません。
* コピーまたは移動の場合、宛先セレクターにはすべてのフォルダー（Dynamic Media 以外の同期フォルダーを含む）が表示されます。また、現在、Dynamic Media テンプレートアセットは表示されません（これらは両方とも宛先セレクターの制限です）。
* 「アセット」セクションからのフォルダーに対する更新操作（公開や削除など）は、そのフォルダー内で使用可能な Dynamic Media テンプレートに影響を与えます。
* ごみ箱は、Dynamic Media テンプレートでは機能しません。アセットをごみ箱に移動してから復元すると、アセットは AEM では復元されますが、Dynamic Media では復元されません。Dynamic Media テンプレートも同様です。

## 関連トピック

1. [Dynamic Media とその機能](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media)の探索
1. [OpenAPI 機能を備えた Dynamic Media](https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview) の探索
