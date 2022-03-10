---
title: フォルダー権限を効果的に管理する方法を教えてください。
description: 効果的な権限管理のベストプラクティス
source-git-commit: fe716385939d18aa23d01dac5fe5f041541d2b31
workflow-type: tm+mt
source-wordcount: '398'
ht-degree: 0%

---

# 効果的な権限管理のベストプラクティス {#best-practices-permissions-management}

管理者は、Assets Essentialsリポジトリのフォルダー権限の管理を開始する前に、操作を管理しながら管理者とエンドユーザーに対してインフラストラクチャを直感的にさせる様々なベストプラクティスを実装できます。

以下の場合に、これらのベストプラクティスを取り入れることができます。

* [Admin Consoleでのユーザーグループの作成](#admin-console-best-practices)

* [Assets Essentialsリポジトリでのフォルダー構造の作成](#folder-structure-assets-essentials)

* [Assets Essentialsリポジトリでの権限の管理](#folder-permissions)

## Admin Console {#admin-console-best-practices}

組織内のユーザーグループに基づいて、アクセスニーズを特定します。 組織のユーザーグループを計画および作成し、それらのユーザーグループにユーザーを追加します。 個々のユーザーではなく、ユーザーグループに基づいてフォルダー権限を管理するほうが簡単です。

## Assets Essentialsリポジトリのフォルダー構造 {#folder-structure-assets-essentials}

Assets Essentialsリポジトリでのフォルダー構造の作成を計画する際は、次の点を考慮してください。

* 今後のガバナンス：管理者が管理するフォルダーと、管理者が管理するフォルダー [所有者として他のユーザーに権限を委任しました](manage-permissions.md##manage-permissions-folders).

* スケーラブル：フォルダー構造は、組織の将来のニーズに準拠し、容易に拡張できる必要があります。

* サイズ：1 つのフォルダーに含めるアセットの数が多すぎてはなりません。 操作性の問題を引き起こし、管理が困難になる可能性があります。

* 直感的：フォルダー構造は、参照が容易で、エンドユーザーにとって直感的なものにする必要があります。 フォルダー構造内の新しいアセットをアップロードする場所を簡単に識別できるようにする必要があります。

組織で使用できる様々なフォルダー構造タイプがあります。 一般的なフォルダー構造の例を以下に示します。

* 機能と分類に基づく

   ![関数と分類](assets/function-categorization.png)

* キャンペーンベース

   ![キャンペーンベース](assets/campaign-based.png)

* オファーの場所（またはチャネル）ベース

   ![オファーの場所ベース](assets/offer-location.png)


## フォルダー権限 {#folder-permissions}

組織のユーザーグループを作成し、それらのユーザーグループにユーザーを追加し、組織のニーズに合ったAssets Essentialsリポジトリでフォルダー構造を選択して作成したら、組織のフォルダー権限の管理を開始できます。 フォルダー権限の管理を開始する際は、次の点を考慮します。

* 個々のユーザーではなく、ユーザーグループに権限を適用します。 これにより、よりシンプルで効率的な権限構造が得られます。

* 運用効率を高めるために、許可構造をできるだけシンプルにします。

* 拒否アクセス権限は慎重に使用し、フォルダー構造に正の権限（編集、表示、所有者）を適用することを好みます。

効率的でシンプルなフォルダー構造を実現する方法の例については、 [フォルダーに対する権限の管理](manage-permissions.md##manage-permissions-folders).

