---
title: リリースノート
description: ' [!DNL Assets Essentials] のリリースノートと既知の問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: tm+mt
source-wordcount: '303'
ht-degree: 26%

---

# [!DNL Assets Essentials] のリリースノート  {#release-notes}

[!DNL Assets Essentials] の現在のリリースは 2021 年 8 月 30 日にリリースされました。 [!DNL Adobe Workfront] との統合により、[!DNL Workfront] ユーザーは、自分の作業を管理するコンテキストでデジタルアセットを管理できます。 詳しくは、[ 他のAdobeソリューションとの統合 ](/help/integration.md) を参照してください。

このソリューションについて詳しくは、[ [!DNL Assets Essentials]](introduction.md) の概要を参照してください。この機能の使用を開始するには、[Assets Essentials の基本](/help/get-started.md)を参照してください。

## 既知の問題 {#known-issues}

[!DNL Assets Essentials] の既知の問題のリストは、継続的に改訂され、更新されます。

* 1 つ以上のフォルダーをアップロードする場合、リポジトリーのサブフォルダーを含むフォルダーに項目をドラッグすると、アップロードは自動的に 1 つのサブフォルダーに移動します。 回避策は、[!DNL Upload assets] オプションをクリックし、ダイアログにドラッグします。<!-- CQ-4327753 -->
* フォルダーをアップロードした後、左側のパネルに新しいフォルダーが正しく表示されず、ツリービューに表示されないことがあります。 回避策は、ブラウザーを更新することです。<!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

問題が発生した場合や機能強化のご要望については、サポートチームに[フィードバックを送付](#provide-feedback)してください。

## 過去のリリース {#past-release}

### 2021.7.0 リリース {#july2021}

[!DNL Assets Essentials] 2021.7.0 は 2021 年 7 月 30 日にリリースされ、次の更新がおこなわれました。

* カスタマイズされたメタデータフォームを作成および管理して、ユーザーにメタデータのプロパティを表示する際に使用できます。メタデータの詳細画面の [!UICONTROL 「Forms]」オプション（[!DNL Settings] の下）を参照してください。 [ メタデータフォーム ](metadata.md#metadata-forms) を参照してください。
* 多数のサブフォルダーを含むネストされたフォルダーをアップロードする際のパフォーマンスの向上など、様々なバグ修正と製品の改善がおこなわれました。

### 2021.6.0 リリース {#june2021}

[!DNL Assets Essentials] の最初のリリースは 2021 年 6 月 22 日に公開され、軽量なアセット管理機能を提供します。 次の主な機能と CRUD（作成、読み取り、更新、削除）操作をサポートしています。

* アセット（ネストしたフォルダーを含む）のアップロードと追加。アセットとバージョンのプレビュー。
* フルテキスト検索、詳細検索フィルター、迅速にアセットを検出できる保存済みの検索。
* 基本的なアセット管理操作（更新、削除、ダウンロード、メタデータ管理など）。
* [!DNL Assets Essentials] は、メッセージの作 [!DNL Adobe Journey Optimizer] 成時にアセットを管理するために使用できます。詳しくは、[ 他のAdobeソリューションとの統合 ](/help/integration.md) を参照してください。
