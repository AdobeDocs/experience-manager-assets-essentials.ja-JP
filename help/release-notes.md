---
title: リリースノート
description: ' [!DNL Assets Essentials] のリリースノートと既知の問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 4fcac20c15ebabcafe851ce207bd937c8a7f6b03
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---

# [!DNL Assets Essentials] のリリースノート  {#release-notes}

の現在のリリース [!DNL Assets Essentials] は 2022 年 5 月 13 日にリリースされました。 このリリースでは、次の機能が提供されます。

* [!DNL Assets Essentials] がサポートされるようになりました [コレクションの作成](manage-collections.md). コレクションは、Experience Manager Assets Essentials 内のアセットのセットです。 コレクションを使用して、ユーザー間でアセットを共有します。フォルダーとは異なり、1 つのコレクションに異なる複数の場所のアセットを含めることができます。

* また、 [カスタムフィルターの追加](search.md#custom-filters) をユーザーインターフェイスに追加します。 その後、標準フィルターに加えて、これらのカスタムフィルターを適用し、検索結果を絞り込むことができます。

* Assets Essentialsで次の操作を実行できます。 [ステータスを設定](manage-organize.md#set-asset-status) リポジトリで使用可能なアセットの デジタルアセットのダウンストリーム消費をより適切に管理および管理するためのアセットステータスを設定します。

* 顧客のフィードバックに基づく機能強化およびバグ修正。

## Chrome の匿名モード {#incognito-mode}

このリリースでは、UI 配信とAssets Essentialsの特定の機能（アセットと画像編集に関するコメント）のパフォーマンスを最適化しています。これは、ブラウザーのローカルストレージとサードパーティ cookie が有効になっているかどうかに依存します。 Chrome Web ブラウザーの匿名モードは、デフォルトでサードパーティ cookie をブロックします。ユーザーは、すべての機能に引き続きアクセスするための多くのオプションを利用できます。

* ユーザーがブラウザーセッションを分離する必要がある場合、匿名モードではなく Chrome プロファイルを使用します

* をオフにする `Block third-party cookies` Chrome の匿名モード画面で

## 既知の問題 {#known-issues}

[!DNL Assets Essentials] ソリューションに関する既知の問題のリストは、継続的に改訂され、更新されています。

* アセットをフィルタリングするには、 `No Status` アセットのステータス。

* Assets Essentialsは非公開コレクションの作成をサポートしていません。

問題が発生した場合や機能強化のご要望については、サポートチームに[フィードバックを送付](#provide-feedback)してください。

## 過去のリリース {#past-release}

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] は 2022 年 3 月 10 日にリリースされ、次の更新がおこなわれました。

* [!DNL Assets Essentials] では、[!DNL Assets Essentials] アプリケーションへのアクセス権を持たない[外部の関係者とリンクを生成し、アセットを共有](share-links-for-assets.md)できるようになりました。リンクの有効期限を定義し、電子メールやメッセージングサービスなどの好みの通信方法を使用して、他のユーザーとリンクを共有できます。リンクの受信者は、アセットをプレビューし、ダウンロードできます。

* [!DNL Assets Essentials] では、既存の通常および消費者ユーザー製品プロファイルに加えて、Admin Console の[管理者製品プロファイル](deploy-administer.md#add-users-to-essentials)を構成できるようになりました。管理者は、他のユーザーを管理者製品プロファイルに割り当てることができるようになりました。

* Assets Essentials では、管理者が[リポジトリで使用可能なフォルダーのアクセスレベルを管理](manage-permissions.md)できるようになりました。管理者は、ユーザーグループを作成し、それらのグループに権限を割り当てて、アクセスレベルを管理できます。また、フォルダーレベルでユーザーグループに権限管理の権限をデリゲートすることもできます。

* 顧客のフィードバックに基づく機能強化およびバグ修正。

さらに、Creative Cloud 用の [!DNL Adobe Asset Link] 拡張機能（Photoshop、Illustrator および InDesign）では、パネルの起動時間とダウンロード速度のパフォーマンスが向上した[新しいバージョン 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html) をリリースしました。


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
