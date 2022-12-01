---
title: リリースノート
description: ' [!DNL Assets Essentials] のリリースノートと既知の問題'
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: fbbd982e36f2b0d126c01f71afed8da984320523
workflow-type: tm+mt
source-wordcount: '1401'
ht-degree: 94%

---

# [!DNL Assets Essentials] のリリースノート {#release-notes}

Assets Essentialsの現在のリリースは 2022 年 11 月 17 日にリリースされました。

このリリースの特長は次のとおりです。

**ドキュメントビューアを使用したDocument Cloudのプレビュー**

Assets Essentialsで、サポートされる他の形式のドキュメントをアップロードし、付属のDocument Cloudビューアを使用してプレビューできるようになりました。 サポートされる形式の種類には、TXT、RTF、DOC、DOCX、PPT、PPTX、XLS、XLSX が含まれます。

<!--

**View Smart Tags moderation reports**

Asset reporting now provides administrators with visibility into the Smart Tags promoted or deleted for an asset. You can specify a folder path and the report lists the Smart Tags promoted or deleted for all assets available at the folder path.

-->

<!--
**Read-only access to large number of users**

Assets Essentials allows administrators to provide read-only access to a large number of users for selected assets or folders in the repository. 
You can easily synchronize the user groups available on the external identity management of an organization with Adobe Admin Console and then manage permissions in Admin Console and Assets Essentials to provide the users with read-only access for selected assets or folders.

-->


**新しい「メタデータを保存」オプション**

Assets Essentialsユーザーインターフェイスで新しい「メタデータを保存」オプションを使用して、メタデータガバナンスを改善できました。

**お客様からのフィードバックに基づく改善**

お客様からのフィードバックに基づく機能強化およびバグ修正。

## 既知の問題 {#known-issues}

[!DNL Assets Essentials] ソリューションに関する既知の問題のリストは、継続的に改訂され、更新されています。

<!--

* Assets Essentials does not support creating Private collections.

-->


* 非公開コレクションは、作成者および管理者権限を持つユーザーが使用できます。管理者は、コレクションへのアクセス権を他のユーザーに委任することはできません。

問題が発生した場合や機能強化のご要望については、サポートチームに[フィードバックを送付](#provide-feedback)してください。

## 過去のリリース {#past-releases}

### 2022.8.0 {#august-2022}

の 8 月リリース [!DNL Assets Essentials] は 2022 年 8 月 23 日にリリースされました。

このリリースの特長は次のとおりです。

**コレクションの通知**

Assets Essentials 通知を使用すると、リポジトリで使用可能なコレクションで実行した操作を監視できます。通知を送信するコレクションを選択し、購読する必要があります。また、コレクションに対して実行される削除、リンクの共有、移動、名前の変更、更新など、通知の送信する操作を設定できます。

**スマートコレクションを編集**

Assets Essentials では、スマートコレクションの作成時に使用する検索条件を編集する機能も提供するようになりました。新しい検索条件を保存して、コレクションのコンテンツを動的に更新します。

**ストレージアカウントのライブ統計の表示**

Assets Essentials を使用すると、Assets Essentials 環境のリアルタイムのストレージアカウントデータをライブ統計ダッシュボードでも表示できるようになりました。過去 30 日間または過去 12 か月間のリアルタイムイベント指標を表示できます。

**アップロードレポートの表示**

アセットレポートで、管理者が Adobe Experience Manager Assets Essentials デプロイメントにアップロードされたアセットを表示できるようになりました。管理者は、既に Assets Essentials デプロイメントからダウンロードしたアセットのレポートを生成できます。このデータは、ユーザーがコンテンツや製品とどのようにやり取りするかについての有用な情報を提供します。

**お客様からのフィードバックに基づく改善**

お客様からのフィードバックに基づく機能強化およびバグ修正。

### 2022.6.0 {#june-2022}

[!DNL Assets Essentials] の 6月リリースは 2022年7月14日（PT）にリリースされました。

このリリースの特長は次のとおりです。

**スマートコレクション**

検索結果をスマートコレクションとして保存して、コレクションのコンテンツを動的に更新します。[スマートコレクションの作成](manage-collections.md#create-smart-collection)時に定義した検索条件に適合するアセットが Assets Essentials リポジトリに追加されている場合、スマートコレクションのコンテンツは自動的に更新されます。

**通知**

Assets Essentials 通知を使用すると、[リポジトリで使用可能なアセットやフォルダーで実行した操作を監視できます](manage-notifications.md)。通知を送信するコンテンツを選択し、購読する必要があります。また、通知を受け取るカテゴリを設定することもできます。

**レポート**

アセットレポートを使用すると、管理者は Adobe Experience Manager Assets Essentials 内のユーザーアクティビティを評価できます。レポートとライブ統計ダッシュボードでは、ユーザーがデプロイメントで利用可能なアセットをどのように操作するかについての有用な情報を提供します。[レポートの情報を使用して](manage-reports.md)重要な成功指標を導き出し、自社やお客様の Assets の採用状況を測定することができます。

アセットダウンロードレポートとライブ統計ダッシュボードモジュールを表示して、ダウンロードされているアセットとダウンロードの頻度を確認します。

### 2022.5.0 {#may-2022}

[!DNL Assets Essentials] の5月リリースは 2022年6月16日（PT）にリリースされました。

このリリースの特長は次のとおりです。

**アセットステータスの機能強化**

* Assets Essentials で[アセットの有効期限の設定](manage-organize.md#set-asset-status)が可能になりました。さらに、アセットの `Expired` ステータスと有効期限の日付範囲を基に、[アセットをフィルタリング](search.md#refine-search-results)できます。

* ごみ箱に入っているすべてのアセットのアセットステータスインジケーターを表示できるようになりました。 これにより、アセットのステータスに基づいてアセットを復元するかどうかを決定できます。

**検索フィルターの機能強化**

* Assets Essentials では、アセットの `No Status` ステータスを使用して[アセットをフィルタリング](search.md#refine-search-results)できるようになりました。

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**コレクションの機能強化**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials では、[コレクションのダウンロード](manage-collections.md)をサポートするようになりました。

* コレクションの「説明」メタデータフィールドを編集できるようになりました。

**ドキュメントの改善**

* [Assets Essentials 概要ドキュメント](introduction.md)の新しいバージョンが利用できるようになりました。

**お客様からのフィードバックに基づく改善**

* お客様からのフィードバックに基づく機能強化およびバグ修正。

### 2022.4.0 {#april-2022}

[!DNL Assets Essentials] の最新リリースは 2022年5月12日（PT）にリリースされました。このリリースでは、次の機能が提供されます。

* [!DNL Assets Essentials] で、[コレクションの作成](manage-collections.md)がサポートされるようになりました。コレクションとは、Experience Manager Assets Essentials 内の一連のアセットのことです。コレクションを使用して、ユーザー間でアセットを共有します。フォルダーとは異なり、1 つのコレクションに異なる複数の場所のアセットを含めることができます。

* また、Assets Essentials で、ユーザーインターフェイスに[カスタムフィルターを追加](search.md#custom-filters)できるようになりました。標準フィルターに加えて、カスタムフィルターを適用し、検索結果を絞り込むことができます。

* Assets Essentials で、リポジトリで使用可能なアセットの[ステータスを設定](manage-organize.md#set-asset-status)できるようになりました。デジタルアセットのダウンストリーム使用をより適切に制御および管理するためのアセットステータスを設定します。

* 顧客のフィードバックに基づく機能強化およびバグ修正。

#### Chrome のシークレットモード {#incognito-mode}

このリリースでは、UI 配信と Assets Essentials の特定の機能（アセットと画像編集に関するコメント）のパフォーマンスを最適化しています。これは、ブラウザーのローカルストレージとサードパーティ cookie が有効かどうかに依存します。Chrome web ブラウザーのシークレットモードは、デフォルトでサードパーティ cookie をブロックします。ユーザーは、すべての機能に引き続きアクセスするための多くのオプションを利用できます。

* ブラウザーセッションを分離する必要がある場合、シークレットモードではなく Chrome プロファイルを使用する

* Chrome のシークレットモード画面で `Block third-party cookies` をオフにする

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] は 2022年3月9日（PT）にリリースされ、次の更新が行われました。

* [!DNL Assets Essentials] では、[!DNL Assets Essentials] アプリケーションへのアクセス権を持たない[外部の関係者とリンクを生成し、アセットを共有](share-links-for-assets.md)できるようになりました。リンクの有効期限を定義し、電子メールやメッセージングサービスなどの好みの通信方法を使用して、他のユーザーとリンクを共有できます。リンクの受信者は、アセットをプレビューし、ダウンロードできます。

* [!DNL Assets Essentials] では、既存の通常および消費者ユーザー製品プロファイルに加えて、Admin Console の[管理者製品プロファイル](deploy-administer.md#add-users-to-essentials)を構成できるようになりました。管理者は、他のユーザーを管理者製品プロファイルに割り当てることができるようになりました。

* Assets Essentials では、管理者が[リポジトリで使用可能なフォルダーのアクセスレベルを管理](manage-permissions.md)できるようになりました。管理者は、ユーザーグループを作成し、それらのグループに権限を割り当てて、アクセスレベルを管理できます。また、フォルダーレベルでユーザーグループに権限管理の権限をデリゲートすることもできます。

* 顧客のフィードバックに基づく機能強化およびバグ修正。

さらに、Creative Cloud 用の [!DNL Adobe Asset Link] 拡張機能（Photoshop、Illustrator および InDesign）では、パネルの起動時間とダウンロード速度のパフォーマンスが向上した[新しいバージョン 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html) をリリースしました。


### 2022.1.0 リリース {#january-2022}

[!DNL Assets Essentials] は 2022年2月3日（PT）にリリースされ、次の更新が行われました。

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
