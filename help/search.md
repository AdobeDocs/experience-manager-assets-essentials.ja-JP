---
title: ' [!DNL Assets Essentials] でのアセットの検索と検出'
description: ' [!DNL Assets Essentials] でのアセットの検索と検出について説明します。'
role: User
exl-id: be9597a3-056c-436c-a09e-15a03567c85a
source-git-commit: cfe72bb73493c84dc57a0438817e3868d8a1ed14
workflow-type: ht
source-wordcount: '802'
ht-degree: 100%

---

# [!DNL Assets Essentials] でのアセットの検索  {#search-assets}

[!DNL Assets Essentials] では効果的な検索が可能です。この検索はデフォルトで機能します。フルテキスト検索なので、網羅的に検索できます。この強力な検索機能を使用すると、適切なアセットをすばやく発見できるので、コンテンツベロシティ（コンテンツ創出の速度）の向上に役立ちます。[!DNL Assets Essentials] では、フルテキスト検索を行えるほか、スマートタグ、タイトル、作成日、著作権などのメタデータを検索することもできます。

アセットを検索するには、

* ページ上部の検索ボックスをクリックします。デフォルトでは、現在参照しているフォルダー内を検索します。次のいずれかの操作を行います。

   ![検索ボックス](assets/search-box.png)

   * キーワードを使用して検索します。オプションで、フォルダーを変更することもできます。Return キーを押します。

   * 最近表示されたアセットを直接検索して、操作を開始します。検索ボックス内をクリックし、最近表示されたアセットを候補から選択します。

## 検索結果のフィルタリング {#refine-search-results}

以下のパラメーターに基づいて検索結果をフィルタリングできます。

![検索フィルター](assets/filters1.png)

*図：検索したアセットを様々なパラメーターに基づいてフィルタリング*

* アセットステータス：`Approved`、`Rejected`、または `No Status` アセットステータスを使用した検索結果のフィルタリング。

* ファイルタイプ：サポートされているファイルタイプ（`Images`、`Documents`、`Videos`）で検索結果をフィルタリングします。
* MIME タイプ：サポートされている 1 つ以上のファイル形式でフィルタリングします。<!-- TBD:  [supported file formats](/help/supported-file-formats.md). -->
* 画像サイズ：画像をフィルタリングするための最小サイズと最大サイズのどちらか一方または両方を指定します。サイズはピクセル単位で指定され、画像のファイルサイズではありません。
* 作成日：アセットの作成日（メタデータで指定されたもの）。標準の日付形式は `yyyy-mm-dd` です。
* 変更日：アセットの最終変更日。標準の日付形式は `yyyy-mm-dd` です。

* 有効期限：アセットの `Expired` ステータスに基づいて検索結果をフィルタリングできます。また、アセットの有効期限の日付範囲を指定して、検索結果をさらにフィルタリングすることもできます。

* カスタムフィルター：Assets Essentials ユーザーインターフェイスに[カスタムフィルターを追加](#custom-filters)できます。 標準フィルターに加えて、カスタムフィルターを適用し、検索結果を絞り込むことができます。

検索したアセットを、`Name`、`Relevancy`、`Size`、`Modified` および `Created` の昇順または降順に並べ替えることができます。

## カスタムフィルターの管理 {#custom-filters}

**必要な権限：** `Can Edit`、`Owner` または管理者。

また、Assets Essentials で、ユーザーインターフェイスにカスタムフィルターを追加できます。[標準フィルター](#refine-search-results)に加えて、カスタムフィルターを適用し、検索結果を絞り込むことができます。

Assets Essentials が提供するカスタムフィルターは次のとおりです。

<table>
    <tbody>
     <tr>
      <th><strong>カスタムフィルター名</strong></th>
      <th><strong>説明</strong></th>
     </tr>
     <tr>
      <td>タイトル</td>
      <td>アセットタイトルを使用してアセットをフィルタリングします。大文字と小文字を区別する検索条件で指定するタイトルは、結果に表示されるアセットの正確なタイトルと一致する必要があります。</td>
     </tr>
     <tr>
      <td>名前</td>
      <td>アセットファイル名を使用してアセットをフィルタリングします。大文字と小文字を区別する検索条件で指定する名前は、結果に表示されるアセットの正確なファイル名と一致する必要があります。</td>
     </tr>
     <tr>
      <td>アセットサイズ</td>
      <td>アセットをフィルタリングするには、検索条件でアセットに表示するサイズ範囲をバイト単位で指定します。</td>
     </tr>
     <tr>
      <td>予測されるタグ</td>
      <td>アセットスマートタグを使用してアセットをフィルタリングします。大文字と小文字を区別する検索条件で指定するスマートタグ名は、結果に表示されるアセットの正確なスマートタグ名と一致する必要があります。検索条件に複数のスマートタグを指定することはできません。</td>
     </tr>    
    </tbody>
   </table>

<!--
   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria. For example, if you define <b>ma*</b> as the search criteria, Assets Essentials displays assets with title, such as, market, marketing, man, manchester, and so on in the results.

   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria.

   You can use a wildcard operator (*) to enable Assets Essentials to display assets in the results that partially match the search criteria. You can specify multiple smart tags separated by a comma in the search criteria.

   -->

### カスタムフィルターの追加 {#add-custom-filters}

カスタムプロパティを追加する手順は次のとおりです。

1. 「**[!UICONTROL フィルター]**」をクリックします。

1. 「**[!UICONTROL カスタムフィルター]**」セクションで、「**[!UICONTROL 編集]**」または「**[!UICONTROL フィルターを追加]**」をクリックします。

   ![カスタムフィルターの追加](assets/add-custom-filters.png)

1. **[!UICONTROL カスタムフィルター管理]**&#x200B;ダイアログボックスで、既存のフィルターのリストに追加するフィルターを選択します。「**[!UICONTROL カスタムフィルター]**」を選択して、すべてのフィルターを選択します。

1. 「**[!UICONTROL 確認]**」をクリックして、ユーザーインターフェイスにフィルターを追加します。

### カスタムフィルターの削除 {#remove-custom-filters}

カスタムフィルターを削除する手順は次のとおりです。

1. 「**[!UICONTROL フィルター]**」をクリックします。

1. 「**[!UICONTROL カスタムフィルター]**」セクションで、「**[!UICONTROL 編集]**」をクリックします。

1. **[!UICONTROL カスタムフィルター管理]**&#x200B;ダイアログボックスで、既存のフィルターのリストから削除するフィルターを選択解除します。

1. 「**[!UICONTROL 確認]**」をクリックして、ユーザーインターフェイスからフィルターを削除します。


## 保存済みの検索 {#saved-search}

[!DNL Assets Essentials] の検索機能は非常に使いやすくなっています。検索ボックス内に、キーワードを入力し、Return キーを押せば結果を表示できるだけでなく、最近検索したキーワードを 1 回クリックするだけですばやく再検索することもできます。

また、アセットのメタデータやタイプに関する特定の条件に基づいて検索結果をフィルタリングすることもできます。特定のフィルターを頻繁に使用する場合、[!DNL Assets Essentials] では、検索性を向上させるために、検索パラメーターを保存できます。その場合、保存済みの検索を選択し、1 回クリックするだけで検索してフィルターを適用することができます。

保存済みの検索を作成するには、アセットを検索し、1 つ以上のフィルターを適用して、[!UICONTROL フィルター]パネルの「[!UICONTROL 検索結果を保存]」をクリックします。

![フィルターパネルに表示される保存済みの検索](assets/saved-search.png)

<!-- TBD: Search behavior. Full-text search. Ranking and rank boosts. Hidden assets.
Report poor UX that users can only save a filtered search and not a simple search.
.
Are other supported files fully indexed and support full-text search? Eg. audio/videos files can at best have metadata indexed.
Anything about ranking of assets displayed in search results?

What about temporarily hiding an asset (suspending search on it) from the search results? If an asset is undergoing review collaboration, should it be used by others? Should it be hidden in search?

When userA is searching and userB add an asset that matches search results, will the asset display in search as soon as userA refreshes the page? Assuming indexing is near real-time. May not be so for bulk uploads.
-->

## 次の手順 {#next-steps}

* [ビデオを試聴して Assets Essentials でのアセットの検索を学ぶ](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/basics/using.html?lang=ja)

* Assets Essentials ユーザーインターフェイスの「[!UICONTROL フィードバック]」オプションを使用して製品に関するフィードバックを提供する

* 右側のサイドバーにある「[!UICONTROL このページを編集]」（![ページを編集](assets/do-not-localize/edit-page.png)）または「[!UICONTROL 問題を記録] 」（![GitHub イシューを作成](assets/do-not-localize/github-issue.png)）を使用してドキュメントに関するフィードバックを提供する

* [カスタマーケア](https://experienceleague.adobe.com/?support-solution=General&amp;lang=ja#support)に問い合わせる
