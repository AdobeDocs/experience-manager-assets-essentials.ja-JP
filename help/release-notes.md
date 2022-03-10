---
title: リリースノート
description: ' [!DNL Assets Essentials] のリリースノートと既知の問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 211233202b667f9d25713491c8ae59e002139777
workflow-type: tm+mt
source-wordcount: '549'
ht-degree: 65%

---

# [!DNL Assets Essentials] のリリースノート  {#release-notes}

の現在のリリース [!DNL Assets Essentials] は 2022 年 3 月 3 日にリリースされました。 このリリースでは、次の機能が提供されます。

* [!DNL Assets Essentials] 次に、 [リンクを生成し、外部の関係者とアセットを共有する](share-links-for-assets.md)（にアクセスできない） [!DNL Assets Essentials] アプリケーション。 リンクの有効期限を定義し、電子メールやメッセージングサービスなどの好みの通信方法を使用して、他のユーザーとリンクを共有できます。 リンクの受信者は、アセットをプレビューし、ダウンロードできます。

* この [!DNL Assets Essentials] 次を含む [管理者製品プロファイル](deploy-administer.md#add-users-to-essentials) 既存の通常および消費者のユーザー製品プロファイルに加えて、Admin Consoleに関する情報。 管理者は、他のユーザーを管理者製品プロファイルに割り当てることができるようになりました。

* Assets Essentialsでは、管理者が次の操作を実行できるようになりました。 [リポジトリで使用可能なフォルダのアクセスレベルを管理します](manage-permissions.md). 管理者は、ユーザーグループを作成し、それらのグループに権限を割り当てて、アクセスレベルを管理できます。 また、フォルダーレベルでユーザーグループに権限管理権限を委任することもできます。

* お客様のご意見に基づく機能強化およびバグ修正。

さらに、 [!DNL Adobe Asset Link] Creative Cloud(Photoshop、IllustratorおよびInDesign) 用の拡張機能がリリースされました。 [新しいバージョン 3.2.0](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)パネルの起動時間とダウンロード速度のパフォーマンスが向上しました。


## 既知の問題 {#known-issues}

[!DNL Assets Essentials] ソリューションに関する既知の問題のリストは、継続的に改訂され、更新されています。

* なし

問題が発生した場合や機能強化のご要望については、サポートチームに[フィードバックを送付](#provide-feedback)してください。

## 過去のリリース {#past-release}

### 2022.1.0 リリース {#january-2022}

[!DNL Assets Essentials] は 2022 年 2 月 3 日にリリースされ、以下の更新がおこなわれました。

* 「[!UICONTROL フォルダーを作成]」操作のパフォーマンスの向上。<!-- CQ-4338818 -->

### 2021.11.0 リリース {#november-2021}

[!DNL Assets Essentials] は 2021年12月16日（PT）にリリースされ、次の更新が行われました。

* Adobe は、プロビジョニングプロセスの完了後、自動的に Assets Essentials をデプロイします。管理者は、[!DNL Cloud Manager] ユーザーインターフェイスを使用して Assets Essentials をデプロイするために、追加の手順を実行する必要はありません。この自動デプロイメントは、2022 年 1 月 6 日以降にプロビジョニングされた環境で使用できるようになります。
* Assets Essentials で動作する Creative Cloud プラグインの新しいバージョンを Adobe Exchange で利用できます。「[Adobe XD v 2.1.0 用の Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)」および「[Photoshop / InDesign / Illustrator v 3.1.65 用の Adobe Asset Link](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)」を参照してください。
* バグ修正および製品の機能強化。以前の既知の問題への対応含んでいます（アップロード後、左側のナビゲーションツリーにフォルダーが正しく表示されるようになり<!-- CQ-4337638 -->、ドラッグ＆ドロップでアップロードする際、現在のフォルダーまたは任意のサブフォルダーを選択できるようになりました<!-- CQ-4327753 -->）。

### 2021.8.0 リリース {#august2021}

[!DNL Assets Essentials] 2021.8.0 は 2021 年 8 月 30 日（PT）にリリースされ、次の更新が行われました。

* [!DNL Adobe Workfront] との統合により、[!DNL Workfront] ユーザーは、自分の作業を管理する中で、自分のデジタルアセットを管理することができます。詳しくは、[他のアドビソリューションとの統合](/help/integration.md)を参照してください。

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
