---
title: ' [!DNL Assets Essentials]内のアセットの検索と検出'
description: ' [!DNL Assets Essentials]内のアセットを検索および検出します。'
role: User
source-git-commit: 5bae37e18ac587aaacaa004e5ec02775888d7f9a
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 3%

---


# [!DNL Assets Essentials] でのアセットの検索  {#search-assets}

[!DNL Assets Essentials] は、デフォルトで機能する、効果的な検索を提供します。全文検索なので、検索は包括的です。 強力な検索機能を使用すると、適切なアセットをすばやく見つけて、コンテンツの速度を向上できます。 [!DNL Assets Essentials] では、フルテキスト検索を実行したり、スマートタグ、タイトル、作成日、著作権などのメタデータを検索したりできます。

アセットを検索するには

* ページ上部の検索ボックスをクリックします。 デフォルトでは、現在参照しているフォルダー内を検索します。 次のいずれかの操作を行います。

   ![検索ボックス](assets/search-box.png)

   * キーワードを使用して検索し、オプションでフォルダーを変更します。 Return を押します。

   * 最近表示したアセットを直接検索して操作を開始します。 検索ボックス内をクリックし、候補から最近表示したアセットを選択します。

## 検索結果のフィルタリング {#refine-search-results}

次のパラメーターに基づいて検索結果をフィルタリングできます。

![検索フィルター](assets/filters1.png)

*図：様々なパラメーターに基づいて、検索したアセットをフィルタリングします。*

* ファイルタイプ：サポートされているファイルのタイプ(`Images`、`Documents`、`Videos`)で検索結果をフィルタリングします。
* MIMEタイプ：サポートされている1つ以上のファイル形式のフィルター。<!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* 画像サイズ：画像をフィルタリングするための最小サイズと最大サイズのうち1つを指定します。 サイズはピクセル単位で指定され、画像のファイルサイズではありません。
* 作成日：メタデータで指定されたアセットの作成日。 標準の日付形式は`yyyy-mm-dd`です。
* 変更日：アセットの最終変更日。 標準の日付形式は`yyyy-mm-dd`です。

検索したアセットを、`Name`、`Relevancy`、`Size`、`Modified`、`Created`の順序で並べ替えることができます。

## 保存済みの検索結果 {#saved-search}

[!DNL Assets Essentials]では検索機能は非常に簡単に使えます。 検索ボックス内から、単にキーワードを入力し、Returnキーを押して結果を表示するだけでなく、最近検索したキーワードを1回クリックするだけで、すばやく検索することもできます。

また、メタデータやアセットのタイプに関する特定の条件に基づいて検索結果をフィルタリングすることもできます。 頻繁に使用するフィルターでは、検索エクスペリエンスを向上させるために、[!DNL Assets Essentials]を使用して検索パラメーターを保存できます。 その後、保存済みの検索結果を選択し、1回のクリックでフィルターを適用することもできます。

保存済みの検索結果を作成するには、一部のアセットを検索し、1つ以上のフィルターを適用して、[!UICONTROL フィルター]パネルの「検索を保存]」をクリックします。[!UICONTROL 

![フィルターパネルからの保存済みの検索結果](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->
