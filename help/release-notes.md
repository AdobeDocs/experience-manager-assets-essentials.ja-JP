---
title: リリースノート
description: ' [!DNL Assets Essentials] のリリースノートと既知の問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 4cced7aba92fd0f041842e5ef78d02f0a4f7ffe0
workflow-type: ht
source-wordcount: '549'
ht-degree: 100%

---

# [!DNL Assets Essentials] のリリースノート  {#release-notes}

[!DNL Assets Essentials] の最新リリースは 2022年3月9日（PT）にリリースされました。このリリースでは、次の機能が提供されます。

* [!DNL Assets Essentials] では、[!DNL Assets Essentials] アプリケーションへのアクセス権を持たない[外部の関係者とリンクを生成し、アセットを共有](share-links-for-assets.md)できるようになりました。リンクの有効期限を定義し、電子メールやメッセージングサービスなどの好みの通信方法を使用して、他のユーザーとリンクを共有できます。リンクの受信者は、アセットをプレビューし、ダウンロードできます。

* [!DNL Assets Essentials] では、既存の通常および消費者ユーザー製品プロファイルに加えて、Admin Console の[管理者製品プロファイル](deploy-administer.md#add-users-to-essentials)を構成できるようになりました。管理者は、他のユーザーを管理者製品プロファイルに割り当てることができるようになりました。

* Assets Essentials では、管理者が[リポジトリで使用可能なフォルダーのアクセスレベルを管理](manage-permissions.md)できるようになりました。管理者は、ユーザーグループを作成し、それらのグループに権限を割り当てて、アクセスレベルを管理できます。また、フォルダーレベルでユーザーグループに権限管理の権限をデリゲートすることもできます。

* 顧客のフィードバックに基づく機能強化およびバグ修正。

さらに、Creative Cloud 用の [!DNL Adobe Asset Link] 拡張機能（Photoshop、Illustrator および InDesign）では、パネルの起動時間とダウンロード速度のパフォーマンスが向上した[新しいバージョン 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html) をリリースしました。


## 既知の問題 {#known-issues}

[!DNL Assets Essentials] ソリューションに関する既知の問題のリストは、継続的に改訂され、更新されています。

* なし

問題が発生した場合や機能強化のご要望については、サポートチームに[フィードバックを送付](#provide-feedback)してください。

## 過去のリリース {#past-release}

### 2022.1.0 リリース {#january-2022}

[!DNL Assets Essentials] は 2022年3月3日（PT）にリリースされ、次の更新が行われました。

* 「[!UICONTROL フォルダーを作成]」操作のパフォーマンスの向上。<!-- CQ-4338818 -->

### 2021.11.0 リリース {#november-2021}

[!DNL Assets Essentials] は 2021年12月16日（PT）にリリースされ、次の更新が行われました。

* Adobe は、プロビジョニングプロセスの完了後、自動的に Assets Essentials をデプロイします。管理者は、[!DNL Cloud Manager] ユーザーインターフェイスを使用して Assets Essentials をデプロイするために、追加の手順を実行する必要はありません。この自動デプロイメントは、2022年1月6日（PT）以降にプロビジョニングされた環境で使用できるようになります。
* Assets Essentials で動作する Creative Cloud プラグインの新しいバージョンを Adobe Exchange で利用できます。「[Adobe XD v 2.1.0 用の Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)」および「[Photoshop / InDesign / Illustrator v 3.1.65 用の Adobe Asset Link](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)」を参照してください。
* バグ修正および製品の機能強化。以前の既知の問題への対応含んでいます（アップロード後、左側のナビゲーションツリーにフォルダーが正しく表示されるようになり<!-- CQ-4337638 -->、ドラッグ＆ドロップでアップロードする際、現在のフォルダーまたは任意のサブフォルダーを選択できるようになりました<!-- CQ-4327753 -->）。

### 2021.8.0 リリース {#august2021}

[!DNL Assets Essentials] 2021.8.0 は 2021年8月30日（PT）にリリースされ、次の更新が行われました。

* [!DNL Adobe Workfront] との統合により、[!DNL Workfront] ユーザーは、自分の作業を管理する中で、自分のデジタルアセットを管理することができます。詳しくは、[他のアドビソリューションとの統合](/help/integration.md)を参照してください。

### 2021.7.0 リリース {#july2021}

[!DNL Assets Essentials] 2021.7.0 は 2021年7月29日（PT）にリリースされ、次の更新が行われました。

* カスタマイズされたメタデータフォームを作成および管理して、アセットの詳細画面の [!DNL Settings]／[!UICONTROL メタデータフォーム]でユーザーにメタデータプロパティを表示するために使用できます。[メタデータフォーム](metadata.md#metadata-forms)を参照してください。
* 多数のサブフォルダーを含むネストされたフォルダーをアップロードする際のパフォーマンスの向上など、様々なバグ修正と製品の改善が行われました。

### 2021.6.0 リリース {#june2021}

[!DNL Assets Essentials] の最初のリリースは 2021年6月21日（PT）に公開され、軽量のアセット管理機能を提供しています。次の主要機能と CRUD（作成、読み取り、更新、削除）操作をサポートしています。

* アセット（ネストしたフォルダーを含む）のアップロードと追加。アセットとバージョンのプレビュー。
* フルテキスト検索、詳細検索フィルター、迅速にアセットを検出できる保存済みの検索。
* 基本的なアセット管理操作（更新、削除、ダウンロード、メタデータ管理など）。
* [!DNL Assets Essentials] は、[!DNL Adobe Journey Optimizer] ユーザーがメッセージの作成時にアセットを管理するために利用できます。詳しくは、[他のアドビソリューションとの統合](/help/integration.md)を参照してください。
