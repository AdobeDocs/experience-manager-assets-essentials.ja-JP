---
title: Assets Essentials と Adobe Workfront の統合
description: Assets Essentials を Adobe Workfront アプリケーションと統合して、Workfront アプリケーション内で Assets Essentials リポジトリにアクセスできるようにします。
exl-id: 9605fa3a-d454-48b5-9f84-b384eb1ad493
source-git-commit: 6194a778133842d40c4ef2bc257eec8a34b0a481
workflow-type: ht
source-wordcount: '569'
ht-degree: 100%

---

# Assets Essentials と Adobe Workfront の統合 {#integrate-assets-essentials-workfront}

[[!DNL Adobe Workfront]](https://www.workfront.com/) は作業管理アプリケーションで、作業のライフサイクル全体を一元的に管理するのに役立ちます。[!DNL Adobe Workfront] と [!DNL Assets Essentials] のネイティブ統合により、組織は、作業とアセット管理を本質的に関連付けることで、コンテンツベロシティを向上させ市場投入までの時間を短縮することができます。ユーザーは、自分の作業を管理するという観点で、同じソリューション内の必要なドキュメントや画像にアクセスできます。

Workfront を Experience Manager Assets Essentials と統合するには、次のタスクを実行します。

* [Workfront 製品プロファイルへのユーザーの追加](#add-users-to-product-profiles)

* [Assets Essentials 製品プロファイルへのユーザーの追加](#add-workfront-users-assets-essentials-product-profiles)

* [Experience Manager Assets Essentials 統合の設定](#configure-assets-essentials-integration)

## Workfront 製品プロファイルへのユーザーの追加 {#add-users-to-product-profiles}

ユーザーを Workfront 製品プロファイルに追加するには：

1. 組織の [Admin Console](https://adminconsole.adobe.com) にアクセスし、上部バーの「**[!UICONTROL 製品]**」をクリックし、「**[!UICONTROL Workfront]**」をクリックして、リストの先頭のインスタンスをクリックします。 リストの 2 番目と 3 番目のインスタンスはクリックしないでください。

   ![Admin Console 管理プロファイル](assets/workfront-instances.png)

   Admin Console には、使用可能な製品プロファイルのみが表示されます。

1. 製品プロファイルにユーザーを追加するには、該当するプロファイルをクリックし、「**[!UICONTROL ユーザーを追加]**」をクリックし、ユーザーの詳細を入力して、「**[!UICONTROL 保存]**」をクリックします。

   ![ユーザー管理プロファイルの追加](assets/add-users-workfront.png)

   ユーザーを追加すると、使用を開始するための招待メールがそのユーザーに届きます。招待メールは、[!DNL Admin Console] の製品プロファイル設定で無効にすることができます。

1. ユーザーをグループから削除するには、該当するグループをクリックし、既存のユーザーを選択して、「**[!UICONTROL ユーザーを削除]**」を選択します。

Adobe Admin Console を使用して Workfront にユーザーやシステム管理者を作成する方法について詳しくは、 [Adobe Admin Console でのユーザーの管理](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FAdministration_and_Setup%2FAdd_users%2FCreate_and_manage_users%2Fadmin-console.htm&amp;_LANG=jajp)を参照してください。

## Assets Essentials 製品プロファイルへのユーザーの追加 {#add-workfront-users-assets-essentials-product-profiles}

Workfront ユーザーを次の Assets Essentials 製品プロファイルのいずれかに割り当てます。

* **[!DNL Assets Essentials] ユーザー**：完全な Assets Essentials ユーザーインターフェイスにアクセスできます。これらのユーザーは、Assets Essentials アプリケーションでデジタルアセットのアップロード、整理、タグ付けおよび検索を行えます。 さらに、[!DNL Adobe Workfront] アプリケーションの埋め込みアセット選択エクスペリエンスにもアクセスできます。
* **[!DNL Assets Essentials] 消費者ユーザー**：[!DNL Adobe Workfront] アプリケーションの埋め込みアセット選択エクスペリエンスにアクセスできます。

さらに、アプリケーションへの管理者アクセス権を提供する **[!DNL Assets Essentials] 管理者**&#x200B;製品プロファイルもあります。

ユーザーを Assets Essentials 製品プロファイルに割り当てる方法について詳しくは、 [Assets Essentials 製品プロファイルへのユーザーの割り当て](deploy-administer.md#add-users-to-product-profiles)を参照してください。

## Experience Manager Assets Essentials 統合の設定 {#configure-assets-essentials-integration}

Admin Console を使用して Workfront および Assets Essentials 製品プロファイルにユーザーを追加したら、[Experience Manager Assets Essentials と Adobe Workfront の統合を設定](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2F_workfront-for-aem-asset-essentials.htm)できます。

統合の設定後、以下を行えます。

* [Experience Manager Assets Essentials からのアセットおよびフォルダーのリンク](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Flink-to-aem.htm&amp;_LANG=jajp)

* [Experience Manager Assets Essentials へのドキュメントの送信](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fsend-to-aem.htm&amp;_LANG=jajp)

* [Experience Manager Assets Essentials のリンク先アセットのプルーフ](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fproof-linked-asset-aem.htm)

* [Experience Manager Assets Essentials からのリンク先アセットの表示またはダウンロード](https://one.workfront.com/s/document-item?bundleId=the-new-workfront-experience&amp;topicId=Content%2FDocuments%2FAdobe_Workfront_for_Experience_Manager_Assets_Essentials%2Fview-download-asset.htm)
