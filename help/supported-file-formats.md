---
title: サポートされているファイル形式
description: ' [!DNL Assets Essentials] の様々なユースケースでサポートされているファイル形式'
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
source-git-commit: b9d333a862cca6227ef386ae8dadf431c2fb6d71
workflow-type: tm+mt
source-wordcount: '308'
ht-degree: 56%

---

# [!DNL Assets Essentials] でサポートされているファイル形式  {#file-format-support}

[!DNL Assets Essentials] では幅広いファイル形式をサポートしており、各機能は各種ファイルタイプに対応してます。

* ![画像ファイルタイプアイコン](assets/image-icon.svg) 画像：JPG、PNG、GIF、TIFF、その他
* ![creative cloudtype アイコン](assets/creative-cloud-files.svg) Creative Cloudファイル：PSD、AI、INDD
* ![カメラの種類アイコン](assets/camera-icon.svg) Camera Rawファイル：CR2/CR3、NEF、SRW/SRF、その他
* ![ドキュメントファイルタタイプのアイコン](assets/document-icon.svg) ドキュメント：DOCX、PDF、PPTX および XLSX
* ![ビデオファイルタイプのアイコン](assets/video-icon.svg) ビデオ：MP4

[!DNL Assets Essentials] は、ストレージ、アップロード、コピー、移動、削除、メタデータの追加など、基本的なサービスを備えた任意のバイナリファイル形式をサポートしています。

[!DNL Assets Essentials] また、Adobe Camera Rawを利用したキヤノン (CR2/CR3)、ニコン (NEF)、ソニー (SRW/SRF)、富士フイルム (RAF)、オリンパス (ORF) など、幅広い主要なカメラメーカーの camera RAW ファイルもサポートしています。

以下に説明するように、様々なファイルタイプの使用例や機能に対するサポートの度合いが異なります。 凡例を使用すると、サポートレベルがわかります。

| サポートレベル | 説明 |
|-------------------|-------------------------|
| ✓ | サポート対象 |
| ✓ ‡ | 条件付きでサポート |
| − | 適用なし |

## アセットの追加、アップロード、表示 {#support-to-upload-view}

<!-- TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| アセットタイプ | [参照](/help/navigate-view.md) | コピー | [アップロード](/help/add-delete.md) | 作成 | [削除](/help/add-delete.md#delete-assets) | 詳細 | 画像のズーム | [最近表示された項目](/help/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| ラスター画像 | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| RAW 個のファイル | ✓ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| フォルダー | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | - | - |
| MP4 ビデオ | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| PDF | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |
| PSD、AI、INDD | ✓ | ✓ | ✓ | - | ✓ | ✓ ‡ | - | ✓ |
| その他のバイナリファイル | ✓ | ✓ | ✓ | - | ✓ | ✓ | - | ✓ |

<!-- Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## アセットの検索、使用、編集 {#support-to-search-use-edit}

| アセットタイプ | [ダウンロード](/help/manage-organize.md#download) | ドラッグ＆ドロップ | [画像エディター](/help/edit-images.md) | [検索](/help/search.md) | [スマートタグ](/help/metadata.md#tags) | [名前の変更](/help/manage-organize.md) | [バージョン](/help/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| ラスター画像 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW 個のファイル | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ | ✓ |
| フォルダー | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |
| ビデオ | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| CC ライブラリ | - | - | - | - | - | ✓ | ✓ |
| PDF | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| PSD、AI、INDD | ✓ | ✓ | - | ✓ | ✓ | ✓ | ✓ |
| その他のバイナリファイル | ✓ | ✓ | - | ✓ | - | ✓ | ✓ |


## アセットの確認と共同作業 {#support-to-review-collaborate}

| アセットタイプ | 注釈 | コメント | タスクの作成と確認 |
|---------------|----------|----------|-------------------------|
| ラスター画像 | ✓ | ✓ | ✓ |
| RAW 個のファイル | ✓ | ✓ | ✓ |
| フォルダー | - | - | - |
| ビデオ | - | ✓ | ✓ |
| CC ライブラリ | - | - | - |
| PDF | - | ✓ | ✓ |
| PSD、AI、INDD | - | ✓ | ✓ |
| その他のバイナリファイル | - | ✓ | ✓ |

## その他のアセット管理タスク {#support-to-manage-assets}

| アセットタイプ | [メタデータ](/help/metadata.md) | [レンディション](/help/add-delete.md#renditions) | [ごみ箱](/help/add-delete.md#delete-assets) | コピー | 移動 |
|---------------|-------------------|------------|----------|----------|----------|
| ラスター画像 | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW 個のファイル | ✓ | ✓ | ✓ | ✓ | ✓ |
| フォルダー | ✓ | - | ✓ | ✓ | ✓ |
| ビデオ | ✓ | - | ✓ | ✓ | ✓ |
| CC ライブラリ | ✓ | - | - | - | - |
| PDF | ✓ | - | ✓ | ✓ | ✓ |
| PSD、AI、INDD | ✓ | - | ✓ | ✓ | ✓ |
| その他のバイナリファイル | ✓ | - | ✓ | ✓ | ✓ |

のユーザー [!DNL Adobe Asset Link] は、ファイルを [!DNL Assets Essentials] サポート対象のリポジトリ [!DNL Adobe Creative Cloud] デスクトップアプリケーション。

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
