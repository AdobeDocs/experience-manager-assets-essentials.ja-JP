---
title: Assets Essentialsでのメタデータの一括編集
description: Assets Essentialsで同時に使用できる複数のアセットに対して、事前定義された標準メタデータフィールドのセットを更新する方法について説明します。
exl-id: 17185160-6c51-4581-a716-77b365ef3dd9
TQID: https://experienceleague.adobe.com/zfRAzwQWEhdCwSVuWKDz-ndudFtv-mIhmjzyNkg8sOQ
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: a01bfd36-4ab8-4bf8-9dc0-5b45b890552e
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554id: f8a45b24-4be7-4f1b-909b-60d06b483a20
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 649
ht-degree: 52%

---

<table>
    <tr>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新規">
            <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dm-prime-ultimate"><b>Dynamic Media Prime と Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新規">
            <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/assets-ultimate-overview"><b>AEM Assets Ultimate</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新規">
            <a href="http://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/integrate-aem-assets-edge-delivery-services"><b>AEM Assets と Edge Delivery Services の統合</b></a>
        </td>
        <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新規">
            <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/assets-view/aem-assets-view-ui-extensibility"><b>UI 拡張機能</b></a>
        </td>
          <td>
            <img src="assets/new2.gif" width="20px" height="25px" alt="新規">
            <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-assets-essentials/help/custom-search-filters"><b>カスタム検索フィルター</b></a>
        </td>
    </tr>
    <tr>
        <td>
            <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/best-practices/search-best-practices"><b>検索のベストプラクティス</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/best-practices/metadata-best-practices"><b>メタデータのベストプラクティス</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/content-hub/product-overview"><b>コンテンツハブ</b></a>
        </td>
        <td>
            <a href="https://experienceleague.adobe.com/ja/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/dynamic-media-open-apis-overview"><b>OpenAPI 機能を備えた Dynamic Media</b></a>
        </td>
        <td>
            <a href="https://developer.adobe.com/experience-cloud/experience-manager-apis/"><b>AEM Assets 開発者向けドキュメント</b></a>
        </td>
    </tr>
</table>

# Assets Essentialsでのメタデータの一括編集{#how-to-edit-the-metadata-of-multiple-assets-simultaneously}

Assets Essentials内の&#x200B;**一括メタデータ編集**&#x200B;機能を使用すると、複数のアセットファイルに対して、事前定義された標準メタデータフィールドのセットを同時に編集できます。 複数のアセットを選択し、各アセットの標準メタデータを個別に更新するのではなく、事前定義済みの標準メタデータのセットを一度に一括更新します。 この機能は、大規模なアセット全体で標準メタデータプロパティの効率性、一貫性、精度を向上させ、アセットの検索性と組織性を向上させます。

## アセットメタデータを一括編集 {#how-to-bulk-edit-the-metadata-of-multiple-assets-on-assets-essentials}

複数のアセットメタデータを一度に一括編集するには、次の手順を実行します。

1. Assets Essentialsで、**Assets**&#x200B;をクリックします。
1. 特定のアセットを参照するか、検索バーのキーワードを使用して検索します。
1. アセットを選択し、上部のメニューから「**メタデータを一括編集**」をクリックします。
   ![bulk-metadata-edit](/help/using/assets/bulk-metadata-edit1.png)
1. メタデータを編集ページで、**プロパティ** パネルの次のフィールドを編集します。
   * **ステータス：**&#x200B;選択したアセットのステータスを選択します。
   * **有効期限：** アセットが有効でなくなったり、不要になったりする日付を設定します。
   * **作成者：**&#x200B;作成者の名前を指定します。
   * **キーワード：** アセットに関する詳細な情報を提供する特定の用語またはテキスト文字列を追加して、見つけやすさを向上させます。 キーワードを追加し、Enter キーまたはreturn キーを押して、別のキーワードをリストに追加します。
   * **タグ：** ![ タグアイコン ](/help/using/assets/tags-icon.svg)をクリックして、使用可能なオプションからタグを選択します。 タグによりアセットに関するより具体的な情報が得られ、検出性が向上します。 選択したアセットに既に適用されているタグが、**プロパティ**&#x200B;パネルに表示されます。 関連するタグが見つからない場合は、作成し、選択したアセットに割り当てます。 アセットの作成とタグの割り当てについて詳しくは、[Assets Essentialsでのタグの管理](/help/using/tagging-management.md)を参照してください。
   * 「**保存**」をクリックして、選択したアセットに上記のメタデータの更新を適用します。 保存すると、ステータス、有効期限、作成者の更新された詳細が既存の詳細を上書きする間、キーワードとタグが追加されます。
     ![save-bulk-metadata-edit-properties](/help/using/assets/save-bulk-metadata-edit-properties2.png)

     >[!NOTE]
     >
     >一度に 100 個のアセットのメタデータを編集できます。

アセットに適用されたメタデータの更新を確認するには、アセットの詳細ページに移動し（「**詳細**」）、「![](/help/using/assets/info-icon-solid-black.svg)」をクリックして、**情報** パネルにアセットのメタデータを表示します。

>[!NOTE]
>
>**ステータス**、**有効期限日**、**作成者**、**キーワード**&#x200B;および&#x200B;**タグ**&#x200B;は、フォルダー固有のメタデータにかかわらず、メタデータを一括編集で使用できる標準メタデータプロパティです。 これらのメタデータプロパティは、アセットのフォルダーに適用されるメタデータフォームに含まれている場合にのみ、アセットの詳細ページに表示されます。 アセットの詳細ページでこれらの標準メタデータプロパティが見つからない場合は、アセットフォルダーのメタデータフォームを編集して含めます。 メタデータフォームを作成または編集してフォルダーに適用する方法については、「[Assets Essentials](/help/using/metadata.md)」のメタデータを参照してください。
