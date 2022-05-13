---
title: コレクションの管理
description: コレクションは、Experience Manager Assets Essentials 内のアセットのセットです。 コレクションを使用して、ユーザー間でアセットを共有します。
source-git-commit: 6e86dc11e953423c156c3c06cb20c1700afdd59b
workflow-type: tm+mt
source-wordcount: '473'
ht-degree: 27%

---

# コレクションの管理 {#manage-collections}

コレクションは、Experience Manager Assets Essentials 内のアセットのセットです。 コレクションを使用して、ユーザー間でアセットを共有します。

フォルダーとは異なり、1 つのコレクションに異なる複数の場所のアセットを含めることができます。

<!--
You can share collections with various users that are assigned different levels of privileges, including viewing, editing, and so on.
-->

1 人のユーザーと複数のコレクションを共有できます。各コレクションには、アセットへの参照が含まれます。アセットの参照整合性はコレクション間で維持されます。

コレクションを管理および使用するには、次のタスクを実行します。

* [コレクションを作成](#create-collection)

* [コレクションへのアセットの追加](#add-assets-to-collection)

* [コレクションへのアセットの削除](#remove-assets-from-collection)

* [コレクションのメタデータの表示と編集](#view-edit-collection-metadata)

* [コレクション要素のダウンロード](#download-collection-elements)

* [コレクションの削除](#delete-collection)

## コレクションを作成 {#create-collection}

コレクションを作成するには：

1. クリック **[!UICONTROL コレクション]** をクリックし、 **[!UICONTROL コレクションを作成]**.

1. コレクションのタイトルと説明（オプション）を指定します。

1. クリック **[!UICONTROL 保存]** コレクションを作成します。

## コレクションへのアセットの追加 {#add-assets-to-collection}

コレクションにアセットを追加するには：

1. クリック **[!UICONTROL Assets]** 左側のレールで、アセットを選択します。

1. クリック **[!UICONTROL コレクションに追加]**.

1. の [!UICONTROL コレクション] ダイアログボックスで、選択したアセットを追加するコレクションを選択します。

1. クリック **[!UICONTROL 追加]** をクリックして、選択したコレクションにアセットを追加します。

コレクションにアセットを追加する場合は、 **[!UICONTROL コレクション]** 左側のレールで、アセットを追加するコレクションをクリックし、 **[!UICONTROL コレクションに追加]**、アセットを選択し、 **[!UICONTROL 選択]**.

## コレクションからのアセットの削除 {#remove-assets-from-collection}

コレクションからアセットを削除するには：

1. クリック **[!UICONTROL コレクション]** （左側のレール）を使用して、コレクションのリストを表示します。

1. コレクションをクリックし、コレクションから削除する必要があるアセットを選択します。

1. 「**[!UICONTROL 削除]**」をクリックします。

<!--

## Manage access to a collection {#manage-collection-access}

The permission management for collections function in the same manner as folders in [!DNL Assets Essentials]. Administrators can manage the access levels for collections available in the repository. As an administrator, you can create user groups and assign permissions to those groups to manage access levels. You can also delegate the permission management privileges to user groups at the collection-level.

For more information, see [Manage permissions for folders and collections](manage-permissions.md).

## Search a collection {#search-collections}

Click **[!UICONTROL Collections]** in the left rail and use the Search box to specify a text as the criteria to search for a collection. [!DNL Assets Essentials] uses the specified text to search collection names, metadata including tags defined for a collection and returns appropriate results.

>[!NOTE]
>
>Assets Essentials performs search in collections available at the root level. It does not perform search in assets and folders available in collections.

-->

## コレクションのメタデータの表示と編集 {#view-edit-collection-metadata}

コレクションのメタデータは、タイトルや説明など、コレクションに関するデータで構成されます。

コレクションのメタデータを表示および編集するには：

1. クリック **[!UICONTROL コレクション]** 左側のレールでコレクションを選択し、 **[!UICONTROL 詳細]**.
1. を使用してコレクションのメタデータを表示する **[!UICONTROL 基本]** タブをクリックします。
1. 必要に応じて、メタデータフィールドを変更します。 次の項目を変更できます。 [!UICONTROL タイトル], [!UICONTROL 説明]、および [!UICONTROL 作成者] フィールド。

## コレクションのリンクの共有 {#share-collection-links}

[!DNL Assets Essentials] を使用すると、リンクを生成し、コレクション内のコレクションおよびアセットを、アクセス権のない外部の関係者と共有できます [!DNL Assets Essentials] アプリケーション。 リンクの有効期限を定義し、電子メールやメッセージングサービスなどの好みの通信方法を使用して、他のユーザーとリンクを共有できます。リンクの受信者は、アセットをプレビューし、ダウンロードできます。

外部の関係者とコレクションのリンクを共有する方法について詳しくは、 [アセットのリンクを共有](share-links-for-assets.md).

## コレクション要素のダウンロード {#download-collection-elements}

コレクション要素をダウンロードするには：

1. クリック **[!UICONTROL コレクション]** をクリックします。

1. コレクションをクリックし、ダウンロードする必要がある要素を選択します。

1. 「**[!UICONTROL ダウンロード]**」をクリックします。

1. の [!UICONTROL アセットをダウンロード] ダイアログボックスで、 **[!UICONTROL OK]**.

選択したコレクション要素は、ローカルマシン上に.ZIP ファイルとしてダウンロードされます。

## コレクションの削除 {#delete-collection}

コレクションを削除するには：

1. クリック **[!UICONTROL コレクション]** をクリックします。

1. 削除するコレクションを選択します。

1. 「**[!UICONTROL 削除]**」をクリックします。
