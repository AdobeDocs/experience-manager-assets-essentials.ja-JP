---
title: Assets EssentialsとAdobe Workfrontの統合
description: Assets EssentialsをAdobe Workfrontアプリケーションと統合して、Workfrontアプリケーション内のAssets Essentialsリポジトリにアクセスできるようにします。
exl-id: 47c2963d-57f0-463e-8d5b-5e5af9928f77
source-git-commit: 1bb5f1aa1bb03b38964f13f40dc2d2d675a0480f
workflow-type: tm+mt
source-wordcount: '634'
ht-degree: 18%

---

# Assets EssentialsとAdobe Workfrontの統合 {#integrate-assets-essentials-workfront}

![暗いテーマと明るいテーマを切り替えるための環境設定](assets/cce-workfront.png)

## 今までの話

後 [Experience Manager Assets Essentials の設定](adminster-aem-assets-essentials.md) および [Assets EssentialsとのCreative Cloudアプリの統合](integrate-assets-essentials-creative-cloud.md)を使用する場合、をに基づいてAdobe WorkfrontアプリケーションをAssets Essentialsと統合できます。

## 目的

* **対象ユーザ**:Adobe Workfront管理者

* **目的**:Assets EssentialsをAdobe Workfrontアプリケーションと統合して、Workfrontアプリケーション内のAssets Essentialsリポジトリにアクセスできるようにします。

## 概要

[[!DNL Adobe Workfront]](https://www.workfront.com/) は作業管理アプリケーションで、作業のライフサイクル全体を一元的に管理するのに役立ちます。次の間のネイティブ統合： [!DNL Adobe Workfront] および [!DNL Assets Essentials] 組織は、業務とアセット管理を本質的に結び付けることで、コンテンツの速度と市場投入までの時間を改善できます。 ユーザーは、自分の作業を管理するという観点で、同じソリューション内の必要なドキュメントや画像にアクセスできます。

WorkfrontをExperience Manager Assets Essentials と統合するには、次のタスクを実行します。

* [Workfront製品プロファイルへのユーザーの追加](#add-users-to-product-profiles)

* [Assets Essentials製品プロファイルへのユーザーの追加](#add-workfront-users-assets-essentials-product-profiles)

* [Experience Manager Assets Essentials 統合の設定](#configure-assets-essentials-integration)

## Workfront製品プロファイルへのユーザーの追加 {#add-users-to-product-profiles}

ユーザーをWorkfront製品プロファイルに追加するには：

1. アクセス [Admin Console](https://adminconsole.adobe.com) 組織の場合は、 **[!UICONTROL 製品]** 上部のバーで、 **[!UICONTROL Workfront]**&#x200B;をクリックし、リストの最初のインスタンスをクリックします。 リスト内の 2 番目と 3 番目のインスタンスをクリックしないでください。

   ![Admin Console 管理プロファイル](assets/workfront-instances.png)

   Admin Consoleには、利用可能な製品プロファイルのみが表示されます。

1. 製品プロファイルにユーザーを追加するには、プロファイルをクリックし、 **[!UICONTROL ユーザーを追加]**、ユーザーの詳細を入力し、 **[!UICONTROL 保存]**.

   ![ユーザー管理プロファイルの追加](assets/add-users-workfront.png)

   ユーザーを追加すると、使用を開始するための招待メールがそのユーザーに届きます。招待メールは、[!DNL Admin Console] の製品プロファイル設定で無効にすることができます。

1. ユーザーをグループから削除するには、該当するグループをクリックし、既存のユーザーを選択して、「**[!UICONTROL ユーザーを削除]**」を選択します。

Adobe Admin Consoleを使用してWorkfrontでユーザーとシステム管理者を作成する方法について詳しくは、 [Adobe Admin Consoleでのユーザー管理](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=enus).

## Assets Essentials製品プロファイルへのユーザーの追加 {#add-workfront-users-assets-essentials-product-profiles}

Workfrontユーザーを次のAssets Essentials製品プロファイルのいずれかに割り当てます。

* **[!DNL Assets Essentials]ユーザー** 完全なAssets Essentialsユーザーインターフェイスにアクセスできます。 これらのユーザーは、Assets Essentialsアプリケーションでデジタルアセットをアップロード、整理、タグ付け、検索できます。 また、ユーザーは、 [!DNL Adobe Workfront] アプリケーション。
* **[!DNL Assets Essentials]消費者ユーザー**:の埋め込みアセット選択エクスペリエンスにアクセスできる [!DNL Adobe Workfront] アプリケーション。

また、 **[!DNL Assets Essentials]管理者** アプリケーションへの管理者アクセスを提供する製品プロファイル。

ユーザーをAssets Essentials製品プロファイルに割り当てる方法について詳しくは、 [ユーザーをAssets Essentials製品プロファイルに割り当てる](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Experience Manager Assets Essentials 統合の設定 {#configure-assets-essentials-integration}

Admin Consoleを使用してWorkfrontおよびAssets Essentials製品プロファイルにユーザーを追加すると、次のことができます。 [Adobe WorkfrontとのExperience Manager Assets Essentials 統合の設定](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm).

統合を設定すると、次の操作を実行できます。

* [Experience Manager Assets Essentials からのアセットおよびフォルダーのリンク](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=enus)

* [Experience Manager Assets Essentials へのドキュメントの送信](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=enus)

* [リンクされたアセットのExperience Manager Assets Essentials の配達確認](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Experience Manager Assets Essentials からのリンクされたアセットの表示またはダウンロード](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
