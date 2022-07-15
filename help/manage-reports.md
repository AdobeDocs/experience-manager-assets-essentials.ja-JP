---
title: Assets Essentialsでのレポートの管理
description: Assets Essentialsのレポートの情報を使用して重要な成功指標を導き出し、企業やお客様でのアセットの採用状況を測定することができます。
source-git-commit: 511b7904eca972e76f55e574c7c364dd88fb1721
workflow-type: tm+mt
source-wordcount: '515'
ht-degree: 10%

---

# レポートの管理 {#manage-reports}

アセットレポートを使用すると、管理者はAdobe Experience Manager Assets Essentialsデプロイメントのユーティリティを評価できます。 レポートには、デプロイメントで使用可能なアセットとのユーザーのやり取りに関する有用な情報が表示されます。

レポートの情報を使用して重要な成功指標を導き出し、企業やお客様における Assets の採用状況を測定することができます。

## レポートへのアクセス {#access-reports}

に割り当てられているすべてのユーザー [Assets Essentials Administrators 製品プロファイル](deploy-administer.md) は、Assets Essentialsでライブ統計とレポートにアクセスできます。

## ライブ統計の表示 {#view-live-statistics}

Assets Essentialsを使用すると、Assets Essentialsデプロイメント用に自動生成されたダウンロードデータを表示できます。 過去 30 日間または過去 12 ヶ月間に実行されたアセットのダウンロード数を表示するよう選択できます。

![アセット選択時のツールバーオプション](assets/asset-reports-live-statistics.png)

に移動します。 **[!UICONTROL 設定]** > **[!UICONTROL ライブ統計]** 自動生成されたダウンロードデータを表示する。

## レポートの作成 {#create-report}

レポートを作成するには：

1. に移動します。 **[!UICONTROL 設定]** > **[!UICONTROL レポート]** をクリックし、 **[!UICONTROL レポートを作成]**.

1. 内 [!UICONTROL 設定] タブで、レポートのタイトルと説明（オプション）を指定します。

1. レポートを実行するアセットを含むフォルダーパスを、 **[!UICONTROL フォルダーパスを選択]** フィールドに入力します。

1. レポートの日付間隔を選択します。

1. 内 [!UICONTROL 列] タブで、レポートに表示する列名を選択します。

1. 「**[!UICONTROL 作成]**」をクリックします。

   ![レポートをダウンロード](assets/download-reports-config.png)

次の表に、レポートに追加できるすべての列の使用方法を示します。

<table>
    <tbody>
     <tr>
      <th><strong>列名</strong></th>
      <th><strong>説明</strong></th>
     </tr>
     <tr>
      <td>タイトル</td>
      <td>アセットのタイトル。</td>
     </tr>
     <tr>
      <td>パス</td>
      <td>Assets Essentialsでアセットを使用できるフォルダーパス。</td>
     </tr>
     <tr>
      <td>タイプ</td>
      <td>アセットの MIME タイプ。</td>
     </tr>
     <tr>
      <td>サイズ</td>
      <td>アセットのサイズ。</td>
     </tr>
     <tr>
      <td>ダウンロードしたユーザー</td>
      <td>アセットをダウンロードしたユーザーの電子メール ID。</td>
     </tr>
     <tr>
      <td>ダウンロード日</td>
      <td>アセットのダウンロードアクションが実行された日付。</td>
     </tr>
     <tr>
      <td>作成者</td>
      <td>アセットの作成者。</td>
     </tr>
     <tr>
      <td>作成日時</td>
      <td>アセットがAssets Essentialsにアップロードされた日付。</td>
     </tr>
     <tr>
      <td>変更日</td>
      <td>アセットが最後に変更された日付。</td>
     </tr>
     <tr>
      <td>期限切れ</td>
      <td>アセットの有効期限切れのステータス。</td>
     </tr>
     <tr>
      <td>ユーザー名別にダウンロード済み</td>
      <td>アセットをダウンロードしたユーザーの名前。</td>
     </tr>           
    </tbody>
   </table>

## レポートのリストを表示 {#view-report-list}

後 [レポートの作成](#create-report)を使用すると、レポートのリストを表示し、CSV 形式でダウンロードしたり削除したりすることができます。

レポートのリストを表示するには、に移動します。 **[!UICONTROL 設定]** > **[!UICONTROL レポート]**.

各レポートには、レポートのタイトル、レポートのタイプ、レポートの作成時に指定した説明、レポートのステータス、レポートを作成した作成者の電子メール ID、レポートの作成日を確認できます。

`Completed ` レポートのステータスは、レポートのダウンロード準備ができたことを表します。

![レポートのリスト](assets/list-of-reports.png)


## CSV レポートのダウンロード {#download-csv-report}

レポートを CSV 形式でダウンロードするには：

1. に移動します。 **[!UICONTROL 設定]** > **[!UICONTROL レポート]**.

1. レポートを選択し、 **[!UICONTROL CSV をダウンロード]**.

選択したレポートは CSV 形式でダウンロードされます。 CSV レポートに表示される列は、 [レポートの作成](#create-report).

## レポートの削除 {#delete-report}

レポートを削除するには：

1. に移動します。 **[!UICONTROL 設定]** > **[!UICONTROL レポート]**.

1. レポートを選択し、 **[!UICONTROL 削除]**.
