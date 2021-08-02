---
title: リリースノート
description: ' [!DNL Assets Essentials] のリリースノートと既知の問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: cbeb6f6f59da164115af52dfdbb97023b84bc1d1
workflow-type: tm+mt
source-wordcount: '280'
ht-degree: 13%

---


# [!DNL Assets Essentials] のリリースノート  {#release-notes}

現在のリリースは、2021年6月21日に公開された[!DNL Assets Essentials]の最初の公開リリースです。 [!DNL Assets Essentials] は、軽量なアセット管理機能とその最初のバージョンで、次の主な機能とCRUD（作成、読み取り、更新、削除）操作をサポートしています。

* アセット（ネストしたフォルダーを含む）をアップロードし追加する。アセットとバージョンをプレビューします。
* フルテキスト検索、詳細検索フィルター、迅速にアセットを検出できる保存済みの検索。
* メタデータの更新、削除、ダウンロード、管理など、基本的なアセット管理操作。
* [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html?lang=ja)との統合。

現在、[!DNL Assets Essentials]は[[!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer.html)のお客様が利用できます。

このソリューションの詳細については、[の [!DNL Assets Essentials]](introduction.md)の紹介を参照してください。 この機能の使用を開始するには、[get started](/help/get-started.md)を参照してください。

## 現在のリリース {#release-notes-current}

Assets Essentialsの現在のリリースは2021.7.0（2021年7月30日にリリース）で、以下のアップデートがおこなわれました。

* カスタマイズされたメタデータフォームを作成および管理して、[!DNL Settings]の下の「メタデータForms] 」オプションのアセットの詳細画面で、ユーザーにメタデータのプロパティを表示するのに使用できます。 [!UICONTROL [メタデータフォーム](metadata.md#metadata-forms)を参照してください。
* 多数のサブフォルダーを含むネストされたフォルダーをアップロードする際のパフォーマンスの向上など、様々なバグ修正と製品の改善がおこなわれました。

## 既知の問題 {#known-issues}

[!DNL Assets Essentials]製品の既知の問題のリストは、継続的に改訂および更新されます。

* 1つ以上のフォルダーをアップロードするには、リポジトリ内のサブフォルダーを持つフォルダーに項目をドラッグすると、アップロードは自動的に1つのサブフォルダーに移動します。 回避策は、[!DNL Upload assets]オプションをクリックして、ダイアログにドラッグします。<!-- CQ-4327753 -->
* フォルダーをアップロードした後、左側のレールに新しいフォルダーが正しく表示されず、ツリービューに表示されないことがあります。 回避策は、ブラウザーを更新することです。<!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

問題や拡張リクエストが発生した場合は、[チームにフィードバック](#provide-feedback)を提供してください。
