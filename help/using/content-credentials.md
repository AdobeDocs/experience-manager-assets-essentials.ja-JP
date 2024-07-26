---
title: Content credentialsの統合
description: AEM Assetsに統合され、AEM Assets Essentials UI で機能するContent credentialsを使用すると、アセットの作成方法や誰がアセットの作成に関与したかなど、アセットの履歴にコンテキストを提供できます。 デジタルコンテンツの栄養ラベルと同様、Content credentialsは透明性を高め、オーディエンスとの信頼を構築するのに役立ちます。
role: User
source-git-commit: bb7a86c737f862411e2f06997d8b4d720d55a3c5
workflow-type: tm+mt
source-wordcount: '463'
ht-degree: 0%

---


# コンテンツ資格情報 {#content-credentials}

ブランドは、コンテンツの透明性、AI の開示、アセットの改ざんの防止にこれまで以上に関心を寄せています。 Adobeの Content Authenticity Initiative （CAI）は、[Coalition for Content Provenance and Authenticity](https://c2pa.org/specifications/specifications/1.1/specs/C2PA_Specification.html#_trust_model) （C2PA）技術標準に準拠したツールを構築しています。 Content credentialsは、新しい種類の暗号化された改ざん防止メタデータで、コンテンツの系列を理解し、ブランドアセットの整合性を確保するのに役立ちます。 これには、デジタルアセットの履歴に関するインサイトを提供する様々な来歴データが含まれます。

この情報には、次のものが含まれます。

* **発行者または署名者：** アセットを認証または署名するためにデジタル署名を発行したエンティティまたは会社に関する情報。
* **発行日：** コンテンツ資格情報がアセットに適用された日付
* **クレジットと使用状況：** 名前、ソーシャルメディアハンドル、その他の ID 関連情報など、アセットのプロデューサーに関する情報。
* **プロセス：** アセットに対して行われた編集や変更の記録。
* **デバイスの詳細：** アセットの作成または編集に使用されたアプリまたはデバイスに関する情報。
* **使用する AI ツール：** 生成 AI を使用してアセットを編集または作成した場合は、使用するモデルの名前を含めることができます。
* **その他の関連情報：** 追加データは、アセットの履歴に関するより多くのコンテキストを提供するために含めることもできます。

[ 検証 ](https://contentcredentials.org/verify) を使用すると、アセット履歴に関するより包括的なインサイトを得て、完全な表示を行うことができます。

Adobe Experience Manager AssetsでContent credentialsがサポートされるようになり、AEMのAssets EssentialsUI 内でContent credentialsを直接確認できるようになりました。 アセットの詳細を見ると、Content credentialsを含むすべての画像（GenAI サービスで作成された画像など）は、マニフェストの詳細を専用パネルに表示します。 アセットをダウンロード、公開、共有しても、資格情報はアセットとまったく同じままです。

![assetss](/help/using/assets/content-credentials.png)

## content credentialsへのアクセス {#access-content-credentials}

1. Assets EssentialsUI に移動し、左側のパネルから **Assets** をクリックします。
1. フォルダーに移動して、目的のアセットを選択します。
1. **詳細** をクリックし、右側のパネルから「`Cr pin`」を選択します。 「Content credentials」タブには、アセットに関する次の情報が表示されます。
   1. **生成された画像：** Content credentialsが適用された日時。
   1. **コンテンツ概要：** アセットが AI によって部分的に生成されたか、完全に生成されたか、またはアセットの編集方法を示します。
      ![ コンテンツの概要 ](/help/using/assets/content-credentials1.png)
   1. **プロセス：** アセットの生成に使用されるアプリケーション、デバイス、AI ツール（Adobe Fireflyなど）の詳細と、その後の変更。
      ![ プロセス ](/help/using/assets/CR-Process.png)
   1. **本Content credentialsについて：** 発行者名、発行日時。
      ![ 発行者 ](/help/using/assets/CR-issuer.png)