---
title: Experience Manager Assets Essentials の管理
description: Admin Consoleを使用してAssets Essentialsアプリケーションへのアクセスを設定し、Assets Essentialsアプリケーションへのログイン後に実行できるタスクを管理します。
source-git-commit: 1f01dd340f79d1c2d9748232c2b1a589ae7f8545
workflow-type: tm+mt
source-wordcount: '1399'
ht-degree: 53%

---


# Experience Manager Assets Essentials の管理 {#administer-assets-essentials}

![暗いテーマと明るいテーマを切り替えるための環境設定](assets/cce-assets.png)

## 目的

* **対象ユーザ**:Assets Essentials管理者

* **目的**:Admin Consoleを使用してAssets Essentialsアプリケーションへのアクセスを設定し、Assets Essentialsアプリケーションへのログイン後に実行できるタスクを管理します。

## 概要 {#overview}


[!DNL Adobe Experience Manager Assets Essentials] は、アドビのお客様向けにアドビによってプロビジョニングされます。プロビジョニングの一環として、[!DNL Adobe Admin Console] でお客様の組織に [!DNL Assets Essentials] が追加されます。管理者は [!DNL Admin Console] ユーザーの使用権限を管理するには [!DNL Assets Essentials] ソリューションを使用し、アプリケーション管理者に権限とメタデータフォームを設定する権限を割り当てます。 [!DNL Assets Essentials].

次のデータフロー図は、管理者がAssets Essentialsの設定と管理をおこなうために実行する必要がある一連のタスクを示しています。

![Assets Essentials管理フロー](assets/permissions-management-cce-next.svg)

## Admin Console {#access-admin-console}

Assets Essentials ソリューションがプロビジョニングされると、管理者にアドビから電子メールが届きます。この電子メールには、歓迎メッセージと使用を開始するためのリンクが含まれています。さらに、アドビは、Assets Essentials を自動的にデプロイするプロセスを開始します。デプロイメントプロセスが完了するまでに 1 時間ほどかかります。

電子メールに記載されたリンクから、[Admin Console](https://adminconsole.adobe.com) にアクセスしてログインします。複数の組織アカウントに対する管理者アクセス権を持っている場合は、適切な組織を選択するか、 [組織セレクター](https://helpx.adobe.com/jp/enterprise/using/admin-console.html). 自動デプロイメントプロセスが完了すると、[!DNL AEM Assets Essentials] の製品カードが [!DNL Admin Console] に表示されます。

![Assets Essentials のデプロイメント](assets/admin-console-cards.png)

## Admin Consoleタスク {#manage-admin-console-tasks}

次のタスクをAdmin Console:

* [製品プロファイルへのユーザーの追加](#add-users-to-product-profiles)

* [ユーザーグループを追加](#add-user-groups)

* [グループにユーザーを追加](#add-users-to-user-groups)

### 製品プロファイルへのユーザーの追加 {#add-users-to-product-profiles}

製品プロファイルにユーザーを追加して、Assets Essentialsアプリケーションにアクセスできるようにします。

製品プロファイルにユーザーを追加するには：

1. アクセス [Admin Console](https://adminconsole.adobe.com) 組織の場合は、 **[!UICONTROL 製品]** 上部のバーで、 **[!UICONTROL AEM Assets Essentials]**&#x200B;をクリックし、次に、 [!DNL Assets Essentials]. インスタンスの名前は、以下のスクリーンショットに示す名前とは異なる場合があります。
   >[!NOTE]
   >
   >[!DNL Cloud Manager] インスタンスは、サービスステータスの確認やサービスログへのアクセスの取得など、特別な管理者向けのもので、ユーザーを製品に追加する際には使用できません。 詳しくは、 [管理ガイド](deploy-administer.md#view-service-status-and-access-logs-view-logs).

   ![Admin Console 管理プロファイル](assets/assets-essentials-instance.png)

   [!DNL Assets Essentials] には、管理者、通常のユーザーおよび消費者ユーザー用のアクセスを表す 3 つの製品プロファイルがあります。

   ![Admin Console 管理プロファイル](assets/admin-console-admin-profile.png)

1. 製品にユーザーを追加するには、3 つのAssets Essentials製品プロファイルのいずれかをクリックし、 **[!UICONTROL ユーザーを追加]**、ユーザーの詳細を入力し、 **[!UICONTROL 保存]**.

   ![ユーザー管理プロファイルの追加](assets/add-users-admin-profile.png)

   ユーザーを追加すると、使用を開始するための招待メールがそのユーザーに届きます。招待メールは、[!DNL Admin Console] の製品プロファイル設定で無効にすることができます。

1. ユーザーをグループから削除するには、該当するグループをクリックし、既存のユーザーを選択して、「**[!UICONTROL ユーザーを削除]**」を選択します。

   >[!NOTE]
   >
   >ユーザーがAssets Essentialsアプリケーションで管理タスクを実行するには、Admin Consoleの Administrator Assets Essentials製品プロファイルにユーザーを追加する必要があります。 次のタスクが含まれます。 [フォルダー構造を作成](#create-folder-structure), [フォルダーの権限の管理](#manage-permissions-for-folders)、および [メタデータFormsを設定](#metadata-forms).

### ユーザーグループを追加 {#add-user-groups}

ユーザーグループを作成し、そのユーザーグループにユーザーを割り当てます。 これらのユーザーグループは、Assets Essentialsアプリケーションで、フォルダーに対する権限を設定するために使用できます。

ユーザーをユーザーグループ（1）に追加し、[ユーザーを Assets Essentials 製品プロファイル（2）に](#add-admin-users)追加することはできます。ただし、ユーザーグループを Assets Essentials 製品プロファイル（3）に直接追加することはできません。

![グループおよび製品プロファイルへのユーザーの追加](assets/user-groups-product-profiles.svg)

ユーザーグループの管理方法については、[ユーザーグループの管理](https://helpx.adobe.com/jp/enterprise/using/user-groups.html)の `Create user groups` および `Edit user groups` を参照してください。 

>[!NOTE]
>
>Admin Console が、Azure や Google コネクタ、ユーザー同期ツール、User Management Rest API など、ユーザー／グループの割り当てを管理する外部システムを活用するように設定されている場合、グループとユーザーの割り当ては自動的に設定されます。詳しくは、[Adobe Admin Consoleユーザー](https://helpx.adobe.com/jp/enterprise/using/users.html)を参照してください。


### グループにユーザーを追加 {#add-users-to-user-groups}

ユーザーグループを作成した後、ユーザーグループへのユーザーの追加を開始できます。

ユーザーグループへのユーザーの追加を管理する方法については、[ユーザーグループの管理](https://helpx.adobe.com/jp/enterprise/using/user-groups.html#add-users-to-groups)の `Add users to groups` を参照してください。

## Assets Essentials管理タスクの管理 {#manage-assets-essentials-tasks}

Admin Consoleタスクを実行した後、Assets Essentialsアプリケーションで次の管理タスクを実行できるようになりました。

* [フォルダー構造を作成](#create-folder-structure)

* [フォルダーの権限の管理](#manage-permissions-for-folders)

* [メタデータFormsを設定](#metadata-forms)

>[!NOTE]
>
>これらのタスク（特に権限の管理）を管理するには、ユーザーにアプリケーション管理権限が必要です。この権限を [管理者Assets Essentials製品プロファイル](#add-users-to-product-profiles).


### フォルダー構造を作成 {#create-folder-structure}

次の方法を使用して、Assets Essentials リポジトリにフォルダー構造を作成できます。

* ツールバーにある「**[!UICONTROL フォルダーを作成]**」オプションをクリックし、空のフォルダーを作成します。

* ツールバーにある「**[!UICONTROL アセットを追加]**」オプションをクリックし、[ローカルマシンで使用可能なフォルダー構造をアップロード](add-delete.md)します。

組織のビジネス目標に適したフォルダー構造を作成します。既存のフォルダー構造を Assets Essentials リポジトリにアップロードする場合は、構造を確認する必要があります。詳しくは、[効果的な権限管理のベストプラクティス](permission-management-best-practices.md)を参照してください。

Assets Essentials リポジトリでフォルダー構造を作成する計画を開始する際は、次の点を考慮してください。

* 今後のガバナンス：管理者が管理するフォルダーと、[所有者として他のユーザーに権限をデリゲート](manage-permissions.md##manage-permissions-folders)するフォルダー。

* スケーラブル：フォルダー構造は、組織の今後のニーズに準拠し、容易に拡張可能にする必要があります。

* サイズ：1 つのフォルダーに含めるアセットの数が多くなりすぎないようにします。ファイルの数が多すぎると、操作性の問題を引き起こし、管理が困難になる可能性があります。

* 直感的：フォルダー構造は、参照が容易で、エンドユーザーにとって直感的なものにする必要があります。 フォルダー構造内の新しいアセットをアップロードする場所を容易に識別できるようにする必要があります。

組織で使用できるフォルダー構造タイプには様々なものがあります。一般的なフォルダー構造の例を以下に示します。

![一般的なフォルダー構造](assets/folder-structure.svg)

### フォルダーの権限の管理 {#manage-permissions-for-folders}

Assets Essentials では、管理者は、リポジトリで使用可能なフォルダーのアクセスレベルを管理できます。管理者は、ユーザーグループを作成し、それらのグループに権限を割り当てて、アクセスレベルを管理できます。また、フォルダーレベルでユーザーグループに権限管理権限を委任することもできます。

>[!VIDEO](https://video.tv.adobe.com/v/341104)

詳しくは、 [フォルダーの権限の管理](manage-permissions.md).

### メタデータFormsを設定 {#metadata-forms}

Assets Essentials には、多数の標準メタデータフィールドがデフォルトで用意されています。組織には、追加のメタデータニーズがあり、ビジネス固有のメタデータを追加するために、さらに多くのメタデータフィールドが必要です。メタデータフォームを使用すると、ビジネスごとにアセットの[!UICONTROL 詳細] ページにカスタムメタデータフィールドを追加できます。ビジネス固有のメタデータにより、アセットのガバナンスと検出が向上します。フォームは、ゼロから作成することも、既存のフォームを再利用することもできます。

各種アセット（様々な MIME タイプ）のメタデータフォームを設定できます。ファイルの MIME タイプと同じフォーム名を使用します。Essentials は、アップロードされたアセットの MIME タイプをフォーム名に自動的に一致させ、フォームフィールドに基づいて、アップロードされたアセットのメタデータを更新します。

例えば、 `PDF` または `pdf` が存在する場合、アップロードされたPDFドキュメントには、フォームで定義されたメタデータフィールドが含まれます。

Assets Essentialsでは、次の順序に従って、既存のメタデータフォーム名を検索し、特定のタイプのアップロードされたアセットにメタデータフィールドを適用します。

MIME サブタイプ/MIME タイプ > `default` フォーム/標準フォーム

例えば、`PDF` または `pdf` という名前のメタデータフォームが存在する場合、アップロードされた PDF ドキュメントには、そのフォームで定義されたメタデータフィールドが含まれています。メタデータフォームが `PDF` または `pdf` 存在しない場合、名前のメタデータフォームがあるとAssets Essentialsは一致します `application`. 名前のメタデータフォームがある場合 `application`を指定した場合、アップロードされたPDFドキュメントには、フォームで定義されたメタデータフィールドが含まれます。 一致するメタデータフォームがAssets Essentialsでまだ見つからない場合は、 `default` フォームで定義されたメタデータフィールドをアップロードされたPDFドキュメントに適用するメタデータフォーム。 これらの手順がいずれも機能しない場合、Assets Essentialsは標準フォームで定義されたメタデータフィールドを、アップロードされたすべてのPDFドキュメントに適用します。

>[!IMPORTANT]
>
>特定のファイルタイプの新しいメタデータフォームは、[!DNL Assets Essentials] に用意されているデフォルトのメタデータフォームを完全に置き換えます。メタデータフォームを削除または名前変更すると、新しいアセットに対して、デフォルトのメタデータフィールドが再び使用可能になります。

>[!VIDEO](https://video.tv.adobe.com/v/341275)

メタデータFormsについて詳しくは、 [Assets EssentialsのメタデータForms](metadata.md#metadata-forms).

## 次の手順

これで、Assets Essentialsアプリケーションを設定および管理しました。 [Creative CloudアプリケーションとExperience Manager Assets Essentials アプリケーションの統合](integrate-assets-essentials-creative-cloud.md).

