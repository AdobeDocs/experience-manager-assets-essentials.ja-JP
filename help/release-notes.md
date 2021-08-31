---
title: リリースノート
description: ' [!DNL Assets Essentials] のリリースノートと既知の問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: eda2ba0d271310d0e87f904dc7622583a80d002e
workflow-type: tm+mt
source-wordcount: '290'
ht-degree: 13%

---


# [!DNL Assets Essentials] のリリースノート  {#release-notes}

[!DNL Assets Essentials]の現在のリリースは2021年8月30日にリリースされました。 [!DNL Adobe Workfront]との統合を提供し、[!DNL Workfront]ユーザーは、自分の作業を管理するコンテキストでデジタルアセットを管理できます。 [他のAdobeソリューションとの統合](/help/integration.md)を参照してください。

このソリューションの詳細については、[の [!DNL Assets Essentials]](introduction.md)の紹介を参照してください。 この機能の使用を開始するには、[get started](/help/get-started.md)を参照してください。

## 既知の問題 {#known-issues}

[!DNL Assets Essentials]製品の既知の問題のリストは、継続的に改訂および更新されます。

* 1つ以上のフォルダーをアップロードするには、リポジトリ内のサブフォルダーを持つフォルダーに項目をドラッグすると、アップロードは自動的に1つのサブフォルダーに移動します。 回避策は、[!DNL Upload assets]オプションをクリックして、ダイアログにドラッグします。<!-- CQ-4327753 -->
* フォルダーをアップロードした後、左側のレールに新しいフォルダーが正しく表示されず、ツリービューに表示されないことがあります。 回避策は、ブラウザーを更新することです。<!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

問題や拡張リクエストが発生した場合は、[チームにフィードバック](#provide-feedback)を提供してください。

## 過去のリリース {#past-release}

### 2021.7.0リリース {#july2021}

[!DNL Assets Essentials] 2021.7.0は、2021年7月30日にリリースされ、次の更新がおこなわれました。

* カスタマイズされたメタデータフォームを作成および管理して、[!DNL Settings]の下の「メタデータForms] 」オプションのアセットの詳細画面で、ユーザーにメタデータのプロパティを表示するのに使用できます。 [!UICONTROL [メタデータフォーム](metadata.md#metadata-forms)を参照してください。
* 多数のサブフォルダーを含むネストされたフォルダーをアップロードする際のパフォーマンスの向上など、様々なバグ修正と製品の改善がおこなわれました。

### 2021.6.0リリース {#june2021}

[!DNL Assets Essentials]の最初のリリースは2021年6月22日に公開され、軽量なアセット管理機能を提供します。 主な機能とCRUD（作成、読み取り、更新、削除）操作は次のとおりです。

* アセット（ネストしたフォルダーを含む）をアップロードし追加する。アセットとバージョンをプレビューします。
* フルテキスト検索、詳細検索フィルター、迅速にアセットを検出できる保存済みの検索。
* メタデータの更新、削除、ダウンロード、管理など、基本的なアセット管理操作。
* [!DNL Assets Essentials] はで使用できま [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html?lang=ja)す。
