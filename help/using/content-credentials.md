---
title: Content Credentials の統合
description: Content Credentialsは、AEM Assetsに統合され、AEM Assets Essentials UI内で紹介され、アセットの作成方法や制作に関与したユーザーなど、アセットの履歴に関するコンテキストを提供できます。 デジタルコンテンツの栄養ラベルと同様に、Content Credentials は透明性を高め、オーディエンスとの信頼関係を構築するのに役立ちます。
role: User
exl-id: 703f74a6-24d4-4181-8174-9ff4a90ee7aa
TQID: https://experienceleague.adobe.com/witCqgAh8EKfD-hdn8efjZ-M4sypX44KB2ELs3ECInI
product_v2: id: fd1f54a9-f50c-467d-8956-cebbaf4f3eb8
feature_v2: id: ec4263d9-bf7c-44c7-b3f1-3e664861c8f2
role_v2: id: b69b2659-1057-424e-8fc5-ed9e016dc554
topic_v2: id: a004cc84-67b9-4a33-a3a7-8ec7273ef4dc
source-git-commit: f026b389ce582ece5d2ca8745d291b1ae50d657e
workflow-type: tm+mt
source-wordcount: 474
ht-degree: 81%

---

# Content Credentials {#content-credentials}

ブランドは、コンテンツの透明性、AI の開示、アセットの改ざん防止について、これまで以上に関心を寄せています。 アドビのコンテンツ認証イニシアチブ（CAI）は、[Coalition for Content Provenance and Authenticity](https://c2pa.org/specifications/specifications/1.1/specs/C2PA_Specification.html#_trust_model)（C2PA）技術標準に準拠したツールを作成しています。 新しい種類の暗号化された改ざん防止メタデータである Content Credentials は、閲覧者がコンテンツの系統を理解し、ブランドアセットの整合性を確保するのに役立ちます。 これらには、デジタルアセットの履歴に関するインサイトを提供する様々な来歴データを含めることができます。

この情報には、次のものが含まれます。

* **発行者または署名者：**&#x200B;アセットを認証または署名するためにデジタル署名を発行したエンティティまたは会社に関する情報。
* **発行日：** Content Credentials がアセットに適用された日付。
* **クレジットと使用状況：**&#x200B;名前、ソーシャルメディアのハンドル、その他の ID 関連情報など、アセットのプロデューサーに関する情報。
* **プロセス：**&#x200B;アセットに対して行われた編集または変更の記録。
* **デバイスの詳細：**&#x200B;アセットの作成または編集に使用されたアプリまたはデバイスに関する情報。
* **使用された AI ツール：**&#x200B;アセットの編集または作成に生成 AI を使用した場合、使用されたモデルの名前が含まれることがあります。
* **その他の関連情報：**&#x200B;アセットの履歴に関する詳細なコンテキストを提供するために、追加データも含まれる場合があります。

完全なビューを得るために、[Verify](https://contentcredentials.org/verify) ではアセット履歴に関するより包括的なインサイトを提供できます。

Adobe Experience Manager AssetsでContent Credentialsがサポートされるようになったため、AEMのAssets Essentials UI内でContent Credentialsを直接表示できるようになりました。 アセットの詳細を確認すると、Content Credentials を持つ画像（生成 AI サービスで作成されたイメージなど）では、専用のパネルにマニフェストの詳細が表示されます。 アセットがダウンロード、公開、または共有された場合、資格情報はアセットとそのまま残ります。

![ アセット ](/help/using/assets/content-credentials.png)

## Content Credentials へのアクセス {#access-content-credentials}

1. Assets Essentials UIに移動し、左側のペインから&#x200B;**Assets**&#x200B;をクリックします。
1. フォルダーに移動して、目的のアセットを選択します。
1. 「**詳細**」をクリックして、右端のパネルから「`Cr pin`」を選択します。 「Content Credentials」タブには、アセットに関する次の情報が表示されます。
   1. **生成された画像**：Content Credentials が適用された日時。
   1. **コンテンツの概要：**アセットの一部または全部が AI によって生成されたかどうか、または編集方法を示します。
      ![ コンテンツの概要](/help/using/assets/content-credentials1.png)
   1. **プロセス**：アセットの生成に使用されたアプリケーション、デバイス、AI ツール（Adobe Firefly など）と、その後に行われた変更について詳しく説明します。
      ![プロセス](/help/using/assets/CR-Process.png)
   1. **この Content Credentials について：**発行者の名前と発行日時。
      ![発行者](/help/using/assets/CR-issuer.png)
