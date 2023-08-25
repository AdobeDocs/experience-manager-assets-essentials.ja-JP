---
title: Assets ビューを使用したアセットの一括読み込み
description: null
source-git-commit: 1db631a927e806d4b8ed83b1e0fc4a1e4f5bef71
workflow-type: tm+mt
source-wordcount: '200'
ht-degree: 16%

---

# Assets ビューを使用したアセットの一括読み込み  {#bulk-import-assets-view}

AEM Assets表示での一括読み込みを使用すると、管理者は、データソースからAEM Assetsに大量のアセットを読み込むことができます。 管理者は、個々のアセットやフォルダーをAEM Assetsにアップロードする必要はありません。

次のデータソースからアセットを読み込むことができます。

* Azure
* AWS
* Google Cloud
* Dropbox

## 前提条件 {#prerequisites}

| データソース | 前提条件 |
|-----|------|
| Azure | <ul> <li>Azure ストレージアカウント </li> <li> Azure ブロブコンテナ <li> 認証モードに基づく Azure Access Key または SAS トークン </li></ul> |
| AWS | <ul> <li>AWS 地域 </li> <li> AWS バケット <li> AWS アクセスキー </li><li> AWS アクセスシークレット </li></ul> |
| Google Cloud | <ul> <li>GCP バケット </li> <li> GCP サービスアカウントメール <li> GCP サービスアカウントの秘密キー</li></ul> |
| Dropbox | <ul> <li>Dropboxクライアント ID </li> <li> Dropboxクライアント秘密鍵</li></ul> |

データソースに基づく前述の前提条件に加えて、AEM Assetsに読み込む必要のあるすべてのアセットが含まれる、データソースで使用可能なソースフォルダー名を把握しておく必要があります。

## 一括読み込みを作成 {#create-bulk-import}

## インポートを表示 {#view-imports}

## インポートを編集 {#edit-imports}

## 1 回限りのインポートまたは定期的なインポートのスケジュール設定 {#schedule-imports}

## インポートヘルスチェックを実行する {#import-health-check}

## インポートを実行する前にドライランを実行する {#dry-run-bulk-import}

## 一括インポートの実行 {#run-bulk-import}

## 進行中のインポートを停止またはスケジュール {#schedule-stop-ongoing-report}

## 一括インポートの削除 {#delete-bulk-import}

## 一括読み込みの実行後にアセットに移動する {#view-assets-after-bulk-import}

