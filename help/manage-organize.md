---
title: デジタルアセットの管理
description: ' [!DNL Assets Essentials]内のアセットを移動、削除、コピー、名前変更、更新、バージョン化します。'
role: User,Leader
contentOwner: AG
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '595'
ht-degree: 0%

---


# アセットの管理 {#manage-assets}

[!DNL Assets Essentials]の使いやすいインターフェイスを使用して、様々なデジタルアセット管理(DAM)タスクを簡単に実行できます。 アセットを追加した後は、アセットの検索、ダウンロード、移動、コピー、名前変更、削除、更新および編集をおこなうことができます。

[!DNL Assets Essentials]を使用して、次のアセット管理タスクを実行します。 アセットを選択すると、上部のツールバーに次のオプションが表示されます。

![アセットを選択したときのツールバーオプション](assets/toolbar-image-selected.png)

*図：選択した画像のツールバーで使用できるオプション。*

* ![選択を解](assets/do-not-localize/close-icon.png) 除アイコン選択を解除します。
* ![詳細アイ](assets/do-not-localize/edit-in-icon.png) コンをクリックして、アセットをプレビューし、詳細なメタデータを表示します。プレビュー時に、バージョンを表示して画像を編集できます。
* ![ダウンロ](assets/do-not-localize/download-icon.png) ードアイコン選択したアセットをローカルファイルシステムにダウンロードします。
* ![削除アイ](assets/do-not-localize/delete-icon.png) コン選択したアセットまたはフォルダーを削除します。
* 

   <!-- ![checkout icon](assets/do-not-localize/checkout-icon.png) --> Checkout an asset.
* ![copy icon選択](assets/do-not-localize/copy-icon.png) したファイルまたはフォルダーをコピーします。
* ![移動アイ](assets/do-not-localize/move-icon.png) コン選択したアセットまたはフォルダーをリポジトリ階層内の別の場所に移動します。
* ![名前を変](assets/do-not-localize/rename-icon.png) 更アイコン選択したアセットまたはフォルダーの名前を変更します。一意の名前を使用しないと、名前を変更しても警告が表示されて失敗します。 新しい名前でもう一度やり直すことができます。
* 
   <!-- ![assign task icon](assets/do-not-localize/assign-task-icon.png) --> Assign tasks to other users to collaborate on an asset.

アセットのサムネールにも同じオプションを表示できます。

![アセットを管理するためのアセットサムネールのオプション](assets/options-on-thumbnail.png)

[!DNL Assets Essentials] は、選択したアセットのタイプに応じた関連オプションのみをツールバーに表示します。

![アセットを選択したときのツールバーオプション](assets/toolbar-folder-selected.png)

*図：選択したフォルダーのツールバーで使用できるオプション。*

![アセットを選択したときのツールバーオプション](assets/toolbar-pdf-selected.png)

*図：選択したPDFファイルのツールバーで使用できるオプション。*

## アセットのダウンロードと配布 {#download}

1つ以上のアセットまたはフォルダー、またはその両方を選択し、選択内容をローカルファイルシステムにダウンロードできます。 アセットを編集して再度アップロードするか、[!DNL Assets Essentials]の外部にアセットを配布することができます。 また、アセットのレンディション](/help/add-delete.md#renditions)を[ダウンロードすることもできます。

## アセットのバージョン管理 {#versions-of-assets}

<!-- 
TBD: query for engineering: How many versions are maintained. What happens when we reach that limit? Are old versions automatically removed? -->

[!DNL Assets Essentials] のバージョン：アセットが再度アップロードされたときに更新または編集されるアセット。必要に応じて、バージョン履歴や過去のバージョンを表示したり、過去のバージョンのアセットを最新のバージョンとして復元したりできます。以前のバージョンは必要に応じて以前のバージョンに戻ります。 アセットのバージョンは、次のシナリオで作成します。

* 既存のアセットと同じファイル名を持つ新しいアセットを、既存のアセットと同じフォルダーにアップロードします。 [!DNL Assets Essentials] 前のアセットを上書きするか、新しいアセットをバージョンとして保存するかを尋ねるプロンプトが表示されます。[重複するアセットのアップロード](/help/add-delete.md#resolve-upload-fails)を参照してください。

   ![アップロード時にバージョンを作成](assets/uploads-manage-duplicates.png)

   *図：同じ名前のアセットを既存のアセットとしてアップロードする場合、そのアセットのバージョンを作成できます。*

* 画像を編集し、「**[!UICONTROL バージョンとして保存]**」をクリックします。 [画像の編集](/help/edit-images.md)を参照してください。

   ![編集した画像をバージョンとして保存](assets/edit-image2.png)

   *図：編集した画像をバージョンとして保存します。*

* 既存のアセットのバージョンを開きます。 「**[!UICONTROL 新しいバージョン]**」をクリックし、リポジトリーに新しいバージョンのアセットをアップロードします。

   ![バージョン履歴から新しいバージョンのアセットをアップロードするオプション](assets/view-asset-versions2.png)

### アセットのバージョンの表示 {#view-versions}

重複したコピーやアセットの変更済みコピーをアップロードする際に、そのバージョンを作成できます。 バージョン管理を使用すると、履歴アセットを確認し、必要に応じて以前のバージョンに戻すことができます。

バージョンを表示するには、アセットのプレビューを開き、右側のサイドバーにある&#x200B;**[!UICONTROL バージョン]** ![バージョンアイコン](assets/do-not-localize/versions-clock-icon.png)をクリックします。 特定のバージョンをプレビューするには、目的のバージョンを選択します。 元に戻すには、「**[!UICONTROL 最新にする]**」をクリックします。

バージョンタイムラインからバージョンを作成することもできます。 最新バージョンを選択し、「**[!UICONTROL 新しいバージョン]**」をクリックして、ローカルファイルシステムからアセットの新しいコピーをアップロードします。

![アセットのバージョンの表示](assets/view-asset-versions1.png)

*図：アセットのバージョンを表示、以前のバージョンに戻す、または別の新しいバージョンをアップロードします。*
