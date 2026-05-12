---
title: サポートされているファイル形式
description: ' [!DNL Assets Essentials] の様々なユースケースでサポートされているファイル形式'
role: User,Leader,Admin,Developer
contentOwner: AG
exl-id: bc44e98d-446e-41ff-b5b4-9dc324834630
TQID: https://experienceleague.adobe.com/0hWe6e61MkYR2MMF-AWn-ywVZXCIetXer5Mlq3B98jI
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554id: c66ffd68-0f65-42bb-aa23-b4020f12e0bdid: f8a45b24-4be7-4f1b-909b-60d06b483a20id: ff6a42d2-313e-452e-93a6-792e4fad9ff8
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dcid: bce87dde-a4ab-44c9-8a18-ad66e4ddb377
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 372
ht-degree: 100%

---

# [!DNL Assets Essentials] でサポートされているファイル形式 {#file-format-support}

[!DNL Assets Essentials] では幅広いファイル形式をサポートしており、各機能は各種ファイルタイプに対応しています。

* ![画像ファイルタイプのアイコン](assets/image-icon.svg) 画像：JPG、PNG、GIF、TIFF およびその他
* ![Creative Cloud タイプのアイコン](assets/creative-cloud-files.svg) Creative Cloud ファイル：PSD、PSB、AI および INDD
* ![カメラタイプのアイコン](assets/camera-icon.svg) Camera Raw ファイル：CR2/CR3、NEF、SRW/SRF およびその他
* ![ドキュメントファイルタタイプのアイコン](assets/document-icon.svg) ドキュメント：DOCX、PDF、PPTX および XLSX
* ![ビデオファイルタイプのアイコン](assets/video-icon.svg) ビデオ：MP4

[!DNL Assets Essentials] は、メタデータのストレージ、アップロード、コピー、移動、削除、追加など、基本サービスを備えた任意のバイナリファイル形式をサポートしています。

[!DNL Assets Essentials] は Adobe Camera Raw を活用し、キヤノン（CR2/CR3）、ニコン（NEF）、ソニー（SRW/SRF）、富士フイルム（RAF）、オリンパス（ORF）など、幅広い大手カメラメーカーの Camera Raw ファイルもサポートしています。

以下に示すように、ユースケースや機能に対する各種ファイルタイプのサポートレベルは異なります。 凡例を使用すると、サポートレベルがわかります。

| サポートレベル | 説明 |
|-------------------|-------------------------|
| ✓ | サポート対象 |
| ✓ ‡ | 条件付きでサポート |
| − | 適用なし |

## アセットの追加、アップロード、表示 {#support-to-upload-view}

<!-- 
TBD: For AEM, AI files require the PDF option to be selected when saving the AI file.
-->

| アセットタイプ | [参照](/help/using/navigate-view.md) | コピー | [アップロード](/help/using/add-delete.md) | 作成 | [削除](/help/using/add-delete.md#delete-assets) | 詳細 | 画像のズーム | [最近表示された項目](/help/using/navigate-view.md) |
|-------------------|----------|----------|----------|----------|----------|-------------------|------------|-----------------|
| ラスター画像 | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| RAW ファイル | ✓ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| フォルダー | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | − | − |
| MP4 ビデオ | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| PDF | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |
| PSD、AI、PSB および INDD | ✓ | ✓ | ✓ | − | ✓ | ✓ ‡ | − | ✓ |
| その他のバイナリファイル | ✓ | ✓ | ✓ | − | ✓ | ✓ | − | ✓ |

<!-- 
Hiding CC Libraries (considered beta) as per PM feedback.
| CC Libraries  | &#10003; | &minus;  | &#10003; | &#10003; | &#10003; | &#10003; | &minus;    | &minus;         |
-->

## アセットの検索、使用、編集 {#support-to-search-use-edit}

| アセットタイプ | [ダウンロード](/help/using/manage-organize.md#download) | ドラッグ＆ドロップ | [画像エディター](/help/using/edit-images.md) | [検索](/help/using/search.md) | [スマートタグ](/help/using/metadata.md#tags) | [名前の変更](/help/using/manage-organize.md) | [バージョン](/help/using/manage-organize.md#versions-of-assets) |
|---------------|----------|---------------|--------------|----------|------------|----------|----------|
| ラスター画像 | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW ファイル | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| フォルダー | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| ビデオ | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| CC ライブラリ | − | − | − | − | − | ✓ | ✓ |
| PDF | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| PSD と PSB | ✓ | ✓ | − | ✓ | ✓ | ✓ | ✓ |
| AI と INDD | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |
| その他のバイナリファイル | ✓ | ✓ | − | ✓ | − | ✓ | ✓ |


## アセットの確認と共同作業 {#support-to-review-collaborate}

| アセットタイプ | 注釈 | コメント | タスクの作成と確認 |
|---------------|----------|----------|-------------------------|
| ラスター画像 | ✓ | ✓ | ✓ |
| RAW ファイル | ✓ | ✓ | ✓ |
| フォルダー | − | − | − |
| ビデオ | − | ✓ | ✓ |
| CC ライブラリ | − | − | − |
| PDF | − | ✓ | ✓ |
| PSD、PSB、AI および INDD | − | ✓ | ✓ |
| その他のバイナリファイル | − | ✓ | ✓ |
| DOC | − | ✓ | ✓ |
| DOCX | − | ✓ | ✓ |
| PPT | − | ✓ | ✓ |
| PPTX | − | ✓ | ✓ |
| XLS | − | ✓ | ✓ |
| XLSX | − | ✓ | ✓ |
| TXT | − | ✓ | ✓ |
| RTF | − | ✓ | ✓ |

## その他のアセット管理タスク {#support-to-manage-assets}

| アセットタイプ | [メタデータ](/help/using/metadata.md) | [レンディション](/help/using/add-delete.md#renditions) | [ごみ箱](/help/using/add-delete.md#delete-assets) | コピー | 移動 |
|---------------|-------------------|------------|----------|----------|----------|
| ラスター画像 | ✓ | ✓ | ✓ | ✓ | ✓ |
| RAW ファイル | ✓ | ✓ | ✓ | ✓ | ✓ |
| フォルダー | ✓ | − | ✓ | ✓ | ✓ |
| ビデオ | ✓ | − | ✓ | ✓ | ✓ |
| CC ライブラリ | ✓ | − | − | − | − |
| PDF | ✓ | − | ✓ | ✓ | ✓ |
| AI と INDD | ✓ | − | ✓ | ✓ | ✓ |
| PSD と PSB | ✓ | ✓ | ✓ | ✓ | ✓ |
| その他のバイナリファイル | ✓ | − | ✓ | ✓ | ✓ |

[!DNL Adobe Asset Link] のユーザーは、サポート対象の [!DNL Adobe Creative Cloud] デスクトップアプリケーションから [!DNL Assets Essentials] リポジトリにファイルをアップロードしてチェックイン（新しいバージョンをアップロード）できます。

<!-- 
TBD: Saving the template table separately for later use.
| Asset type    | Features |
|---------------|----------|
| Raster images |          |
| Folders       |          |
| Videos        |          |
| CC Libraries  |          |
| PDF files     |          |
| PSD, PSB           |          |
| AI            |          |
| INDD          |          |

>[!MORELIKETHIS]
>
>* []()
-->

## 次の手順 {#next-steps}

* Assets Essentials ユーザーインターフェイスの「[!UICONTROL フィードバック]」オプションを使用して製品に関するフィードバックを提供する

* 右側のサイドバーにある「[!UICONTROL このページを編集]」（![ページを編集](assets/do-not-localize/edit-page.png)）または「[!UICONTROL 問題を記録] 」（![GitHub イシューを作成](assets/do-not-localize/github-issue.png)）を使用してドキュメントに関するフィードバックを提供する

* [カスタマーケア](https://experienceleague.adobe.com/ja?support-solution=General#support)に問い合わせる
