---
title: サポートされているファイル形式
description: サポートされているファイル形式  [!DNL Assets Essentials]の様々な使用例
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: c63e9ab1054398dc055643f0dca6631bae881047
workflow-type: tm+mt
source-wordcount: '206'
ht-degree: 34%

---


# [!DNL Assets Essentials]でサポートされるファイル形式 {#file-format-support}

[!DNL Assets Essentials] は様々なファイル形式をサポートし、各機能は様々なファイルタイプをサポートしています。

* ![iconImagesの画像ファ](assets/do-not-localize/image-icon.png) イルタイプ：GIF、JPG、PNGおよびTIFF
* ![ドキュメントファイルタ](assets/do-not-localize/document-icon.png) イプiconDocuments:DOCX、PDF、PPTXおよびXLSX
* ![ビデオファイルタ](assets/do-not-localize/video-icon.png) イプiconVideos:MP4

以下に示すように、様々なファイルタイプの使用例や機能に対するサポートの度合いは異なります。 凡例を使用して、サポートレベルについて理解します。

| サポートレベル | 説明 |
|-------------------|-------------------------|
| ✓ | サポート対象 |
| ✓ ‡ | 条件付きでサポート |
| - | 適用なし |

## アセットの追加、アップロード、表示 {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| アセットタイプ | [参照](/help/navigate-view.md) | コピー | [アップロード](/help/add-delete.md) | 作成 | [削除](/help/add-delete.md#delete-assets) | 詳細 | 画像ズーム | [最近表示された項目](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| ラスターイメージ | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| フォルダー | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| MP4ビデオ | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD、AI、INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## アセットの検索、使用、編集 {#support-to-search-use-edit}

| アセットタイプ | [ダウンロード](/help/manage-organize.md#download) | ドラッグ＆ドロップ | [画像エディター](/help/edit-images.md) | [検索](/help/search.md) | [スマートタグ](/help/metadata.md#tags) | [名前を変更](/help/manage-organize.md) | [バージョン](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| ラスターイメージ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| フォルダー | ✓ | ✓ | - | ✓ | - | ✓ | - |
| ビデオ | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| CCライブラリ | - | - | - | - | - | ✓ | - |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| PSD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| AI | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |
| INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | - |

## アセットのレビューと共同作業 {#support-to-review-collaborate}

| アセットタイプ | 注釈 | コメント | タスクの作成とレビュー |
|---------------|----------|----------|-------------------------|
| ラスターイメージ | ✓ | ✓ | ✓ |
| フォルダー | - | - | - |
| ビデオ | - | ✓ | ✓ |
| CCライブラリ | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD | - | ✓ | ✓ |
| AI | - | ✓ | ✓ |
| INDD | - | ✓ | ✓ |

## その他のアセット管理タスク {#support-to-manage-assets}

| アセットタイプ | [メタデータ](/help/metadata.md) | [レンディション](/help/add-delete.md#renditions) | [ごみ箱](/help/add-delete.md#delete-assets) | コピー | 移動 |
|---------------|-------------------|------------|----------|----------|----------|
| ラスターイメージ | ✓ | ✓ | ✓ | ✓ | ✓ |
| フォルダー | ✓ | - | ✓ | ✓ | ✓ |
| ビデオ | ✓ | - | ✓ | ✓ | ✓ |
| CCライブラリ | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD | ✓ | - | ✓ | ✓ | ✓ |
| AI | ✓ | - | ✓ | ✓ | ✓ |
| INDD | ✓ | - | ✓ | ✓ | ✓ |

[!DNL Adobe Asset Link]のユーザーは、サポートされている[!DNL Adobe Creative Cloud]デスクトップアプリケーションからラスター画像を[!DNL Assets Essentials]リポジトリにチェックインできます。

<!-- TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->
