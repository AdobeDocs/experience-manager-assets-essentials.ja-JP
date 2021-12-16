---
title: リリースノート
description: ' [!DNL Assets Essentials] のリリースノートと既知の問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 0c849c92562f9102819aaea627f5945030b27a1e
workflow-type: tm+mt
source-wordcount: '382'
ht-degree: 55%

---

# [!DNL Assets Essentials] のリリースノート  {#release-notes}

の現在のリリース [!DNL Assets Essentials] は 2021 年 12 月 16 日にリリースされました。 このリリースでは、

* Adobe：プロビジョニングプロセスの完了後、Assets Essentialsが自動的にデプロイされます。 管理者は、 [!DNL Cloud Manager] ユーザーインターフェイス。 この自動デプロイメントは、2022 年 1 月 6 日以降にプロビジョニングされた環境で使用できるようになります。
* Assets Essentialsで動作するCreative Cloudプラグインの新しいバージョンが、AdobeExchange で利用できます。 [Adobe XD v 2.1.0 のAdobeアセットリンク](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) および [Photoshop /InDesign/ Illustrator v 3.1.65 用のAdobeアセットリンク](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* バグ修正および製品の機能強化（以前の既知の問題を含む）（アップロード後に左側のナビゲーションツリーにフォルダーが正しく表示されるようになりました）<!-- CQ-4337638 -->、ドラッグ&amp;ドロップによるアップロードにより、ユーザーはドロップしてアップロードする際に現在のフォルダーまたは任意のサブフォルダーを選択できます<!-- CQ-4327753 -->) をクリックします。

このソリューションについて詳しくは、[ [!DNL Assets Essentials]](introduction.md) の概要を参照してください。この機能の使用を開始するには、[Assets Essentials の基本](/help/get-started.md)を参照してください。

## 既知の問題 {#known-issues}

[!DNL Assets Essentials] ソリューションに関する既知の問題のリストは、継続的に改訂され、更新されています。

* 個々のアセットは、システム内のどのサブフォルダーにもアップロードできません。 <!-- CQ-4337638 -->

問題が発生した場合や機能強化のご要望については、サポートチームに[フィードバックを送付](#provide-feedback)してください。

## 過去のリリース {#past-release}

### 2021.8.0 リリース {#august2021}

[!DNL Assets Essentials] 2021.8.0 は、2021 年 8 月 30 日にリリースされ、以下の更新がおこなわれました。

* との統合 [!DNL Adobe Workfront] を [!DNL Workfront] ユーザーは、作業を管理するコンテキストでデジタルアセットを管理します。 詳しくは、[他のアドビソリューションとの統合](/help/integration.md)を参照してください。

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
