---
title: Assets Essentials と Creative Cloud Pro および作業管理ソリューションの連携のセットアップ
description: このチュートリアルでは、Assets Essentials アプリケーションを Creative Cloud デスクトップアプリケーションおよび Adobe Workfront アプリケーションと統合できるようにする管理者ジャーニーを紹介します。Creative Cloud デスクトップアプリケーションには、Adobe Photoshop、Adobe Illustrator、Adobe InDesign および Adobe XD が含まれます。
exl-id: a5e9e0c3-35ec-41de-9656-f4f0f88946c7
source-git-commit: b1ae487b4b4e9a88e0d9c39889d3893d92a766c9
workflow-type: tm+mt
source-wordcount: '867'
ht-degree: 100%

---

# Assets Essentials と Creative Cloud Pro および作業管理ソリューションの連携  {#creative-cloud-enterprise-user-journeys}

![暗いテーマと明るいテーマを切り替えるための環境設定](assets/cce-next-banner-landing-page.png)

## はじめに {#introduction}

Creative Cloud Pro エンタープライズ版と作業管理ソリューションを併用すると、クリエイティブツール、コンテンツツールおよび作業管理ツールを統合して、クリエイティブコンテンツの作成能力を高め、ビジネス目標を迅速に達成することができます。このソリューションには、次のコンポーネントが含まれています。

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

このチュートリアルでは、Assets Essentials アプリケーションを Creative Cloud デスクトップアプリケーションおよび Adobe Workfront アプリケーションと統合できるようにする管理者ジャーニーを紹介します。Creative Cloud デスクトップアプリケーションには、Adobe Photoshop、Adobe Illustrator、Adobe InDesign および Adobe XD が含まれます。

## デプロイメントタイプ {#deployment-types}

ソリューションは Creative Cloud と Adobe Experience Cloud から提供されるアプリケーションおよびサービスで構成されているので、会社の 1 つまたは 2 つの Adobe Admin Console にデプロイされる場合があります。

2 つの Admin Console にデプロイする場合は、さらに次の設定手順が必要です。

* Creative Cloud サービスおよびアプリケーション（Creative Cloud エンタープライズ版 Pro とオプションモジュール）は、[Creative Cloud デプロイメントの Adobe Admin Console](https://helpx.adobe.com/jp/enterprise/admin-guide.html) で管理されます。

* Adobe Workfront および Adobe Experience Manager Assets Essentials は、[Experience Cloud ソリューションの Adobe Admin Console](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html?lang=ja) で管理されます。

Creative Cloud と Assets Essentials のアプリケーションを統合するには、Creative Cloud の Admin Console で使用できるユーザーを、Experience Cloud の Admin Console でも使用できるようにする必要があります。ユーザーを Experience Cloud Admin Console で使用できるようにするには、2 つの Admin Console 間で[ディレクトリトラスト](https://helpx.adobe.com/jp/enterprise/using/set-up-identity.html#directory-trusting)を確立するためのディレクトリを作成します。

![Creative Cloud ユーザー](assets/creative-cloud-users.svg)

図に示すように、Creative Cloud ユーザーは、2 つのコンソール間の信頼関係に基づいて、Experience Cloud Admin Console で自動的に使用可能になります。その後、Assets Essentials 製品プロファイルにユーザーを追加できます。その結果、Creative Cloud ユーザーは Assets Essentials リポジトリとやり取りできる Adobe Asset Link アプリケーションにアクセスできます。詳しくは、[Assets Essentials と Creative Cloud アプリケーションの統合](integrate-with-creative-cloud.md)を参照してください。

## Experience Manager ドキュメントジャーニー {#documentation-journeys}

ドキュメントジャーニーでは、Assets Essentials を初めて使用する可能性のある読者が、最小限の事前トピックまたは Assets Essentials の知識を前提として、ビジネス上の問題を包括的に理解し解決するのに役立つ物語を提供することにより、多くの異なる、おそらく複雑なトピックと機能を結び付けます。

ドキュメントジャーニーは、アドビの最新の調査、アドビのコンサルタントによる実装実績、顧客プロジェクトからのフィードバックなどに基づいて、ベストプラクティス原則を軸に設計されています。

## 前提条件

* [Experience Cloud ソリューションの Adobe Admin Console へのアクセス](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html?lang=ja)

* [Creative Cloud エンタープライズ版デプロイメントの Adobe Admin Console へのアクセス](https://helpx.adobe.com/jp/enterprise/admin-guide.html)

## Experience Manager Assets Essentials の管理 {#administer-assets-essentials}

![暗いテーマと明るいテーマを切り替えるための環境設定](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials は、Adobe Experience Manager Assets の新しい軽量版です。 Assets Essentials では、シンプルで一貫性のあるユーザーインターフェイスにより、統一されたアセット管理とコラボレーションを提供します。使いやすいので、より多くのクリエイティブチームやマーケティングチームがデジタルアセットを保存、検出および配布できるようになります。

Adobe Experience Manager Assets Essentials は、アドビがお客様向けにプロビジョニングします。プロビジョニングの一環として、Assets Essentials が Adobe Admin Console のお客様の組織に追加されます。

管理者は、Admin Console を使用して Assets Essentials 製品に対するユーザーの使用権限を管理します。

* ユーザーグループの追加

* ユーザーグループへのユーザーの追加

* Assets Essentials 製品プロファイルへのユーザーの追加

Admin Console でユーザーの使用権限を管理したら、管理者は Assets Essentials アプリケーションを使用して以下を行えます。

* 組織のニーズを最適にサポートするフォルダー構造の作成

* フォルダー構造に対する権限の管理

* メタデータフォームの設定

[![ガイドを参照](assets/see-the-guide-sm.png)](deploy-administer.md)

Assets Essentials アプリケーションを設定および管理したら、[Creative Cloud アプリケーションを Experience Manager Assets Essentials アプリケーションと統合します](integrate-with-creative-cloud.md)。

## Creative Cloud アプリケーションと Experience Manager Assets Essentials の統合 {#administer-creative-cloud-applications}

![暗いテーマと明るいテーマを切り替えるための環境設定](assets/cce-creative-cloud.png)

[Adobe Asset Link のアプリ内パネル](https://www.adobe.com/jp/creativecloud/business/enterprise/adobe-asset-link.html)を使用すると、クリエイティブプロフェッショナルは、サポートされている [!DNL Adobe Creative Cloud] デスクトップアプリ内から [!DNL Assets Essentials] リポジトリに接続できます。このパネルは、[!DNL Adobe Photoshop]、[!DNL Adobe Illustrator]、[!DNL Adobe InDesign] および [!DNL Adobe XD] で使用できます。これにより、アセットへのアクセスが効率化され、その結果、コンテンツベロシティ（コンテンツ創出速度）が向上します。

このチュートリアルでは、[!DNL Adobe Photoshop]、[!DNL Adobe Illustrator]、[!DNL Adobe InDesign] および [!DNL Adobe XD] アプリケーションを Experience Manager Assets Essentials と統合する方法について説明します。

目標：

* Creative Cloud と Experience Cloud の Admin Console 間のディレクトリトラストの作成

* Assets Essentials 製品プロファイルへの Creative Cloud ユーザーの追加

* Adobe Asset Link のインストール

* Adobe Asset Link の使用

[![ガイドを参照](assets/see-the-guide-sm.png)](integrate-with-creative-cloud.md)

これで、Creative Cloud アプリケーションと Assets Essentials の統合が完了したので、[Adobe Workfront と Experience Manager Assets Essentials の統合](integrate-with-workfront.md)を行います。

## Adobe Workfront と Experience Manager Assets Essentials の統合 {#administer-adobe-workfront}

![暗いテーマと明るいテーマを切り替えるための環境設定](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) は作業管理アプリケーションで、作業のライフサイクル全体を一元的に管理するのに役立ちます。[!DNL Adobe Workfront] と [!DNL Assets Essentials] のネイティブ統合により、組織は、作業とアセット管理を本質的に関連付けることで、コンテンツベロシティを向上させ市場投入までの時間を短縮することができます。ユーザーは、自分の作業を管理するという観点で、同じソリューション内の必要なドキュメントや画像にアクセスできます。

このチュートリアルでは、Adobe Workfront の管理と Experience Manager Assets Essentials との統合について説明します。

目標：

* Workfront 製品プロファイルへのユーザーの追加

* Assets Essentials 製品プロファイルへのユーザーの追加

* Experience Manager Assets Essentials 統合の設定

[![ガイドを参照](assets/see-the-guide-sm.png)](integrate-with-workfront.md)
