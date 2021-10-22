---
title: リリースノート
description: ' [!DNL Assets Essentials] のリリースノートと既知の問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: cd7af0c946a042430e62528fa6aa19bdab139f67
workflow-type: ht
source-wordcount: '303'
ht-degree: 100%

---

# [!DNL Assets Essentials] のリリースノート  {#release-notes}

[!DNL Assets Essentials] の最新リリースは 2021 年 8 月 30 日（PT）にリリースされました。[!DNL Adobe Workfront] との統合により、[!DNL Workfront] ユーザーは、自分の作業を管理するという観点でデジタルアセットを管理できます。詳しくは、[他のアドビソリューションとの統合](/help/integration.md)を参照してください。

このソリューションについて詳しくは、[ [!DNL Assets Essentials]](introduction.md) の概要を参照してください。この機能の使用を開始するには、[Assets Essentials の基本](/help/get-started.md)を参照してください。

## 既知の問題 {#known-issues}

[!DNL Assets Essentials] ソリューションに関する既知の問題のリストは、継続的に改訂され、更新されています。

* 1 つのフォルダーまたは複数のアセットをアップロードする場合、サブフォルダーを含んだリポジトリー内のフォルダーに項目をドラッグすると、いずれかのサブフォルダーに自動的にアップロードされます。これを回避するには、「[!DNL Upload assets]」オプションをクリックし、ダイアログにドラッグします。<!-- CQ-4327753 -->
* フォルダーのアップロード後、新しいフォルダーが、ツリービューではなく、左側のパネルに誤って表示されることがあります。これを回避するには、ブラウザーの表示を更新します。<!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

問題が発生した場合や機能強化のご要望については、サポートチームに[フィードバックを送付](#provide-feedback)してください。

## 過去のリリース {#past-release}

### 2021.7.0 リリース {#july2021}

[!DNL Assets Essentials] 2021.7.0 は 2021 年 7 月 29 日（PT）にリリースされ、次の更新が行われました。

* カスタマイズされたメタデータフォームを作成および管理して、アセットの詳細画面の [!DNL Settings]／[!UICONTROL メタデータフォーム]でユーザーにメタデータプロパティを表示するために使用できます。[メタデータフォーム](metadata.md#metadata-forms)を参照してください。
* 多数のサブフォルダーを含んだネストされたフォルダーをアップロードする際のパフォーマンスの向上など、様々なバグ修正と製品の改善が行われました。

### 2021.6.0 リリース {#june2021}

[!DNL Assets Essentials] の最初のリリースは 2021 年 6 月 21 日（PT）に公開され、軽量のアセット管理機能を提供しています。次の主要機能と CRUD（作成、読み取り、更新、削除）操作をサポートしています。

* アセット（ネストしたフォルダーを含む）のアップロードと追加。アセットとバージョンのプレビュー。
* フルテキスト検索、詳細検索フィルター、迅速にアセットを検出できる保存済みの検索。
* 基本的なアセット管理操作（更新、削除、ダウンロード、メタデータ管理など）。
* [!DNL Assets Essentials] は、[!DNL Adobe Journey Optimizer] ユーザーがメッセージの作成時にアセットを管理するために利用できます。詳しくは、[他のアドビソリューションとの統合](/help/integration.md)を参照してください。
