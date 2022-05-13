---
title: Assets EssentialsとCreative Cloudアプリケーションの統合
description: Assets EssentialsをCreative Cloudアプリケーションと統合して、アプリ内パネルでAdobeアセットリンクを使用してに接続できるようにします。 [!DNL Assets Essentials] サポート対象内からのリポジトリ [!DNL Adobe Creative Cloud] デスクトップアプリケーション。
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '854'
ht-degree: 5%

---


# Assets EssentialsとCreative Cloudアプリケーションの統合 {#integrate-assets-essentials-creative-cloud-applications}

![暗いテーマと明るいテーマを切り替えるための環境設定](assets/cce-creative-cloud.png)

## 今までの話

後 [Experience Manager Assets Essentials の設定](adminster-aem-assets-essentials.md) このチュートリアルでは、エクスペリエンスに基づいてを構築し、Creative CloudアプリケーションをAssets Essentialsと統合できます。

## 目的

* **対象ユーザ**:Creative Cloud管理者

* **目的**:Assets EssentialsをCreative Cloudアプリケーションと統合して、クリエイティブユーザーがアプリ内パネルでAdobeアセットリンクを使用して、に接続できるようにします。 [!DNL Assets Essentials] サポート対象内からのリポジトリ [!DNL Adobe Creative Cloud] デスクトップアプリケーション。

## 概要

[AdobeAsset Link のアプリ内パネル](https://www.adobe.com/jp/creativecloud/business/enterprise/adobe-asset-link.html) クリエイティブプロフェッショナルが [!DNL Assets Essentials] サポート対象内からのリポジトリ [!DNL Adobe Creative Cloud] デスクトップアプリケーション このパネルは、[!DNL Adobe Photoshop]、[!DNL Adobe Illustrator]、[!DNL Adobe InDesign] および [!DNL Adobe XD] で使用できます。これにより、アセットへのアクセスが合理化され、コンテンツの速度が向上します。

Creative Cloudアプリケーションのユーザーは、AdobeアプリケーションをExperience Manager Assets Essentials リポジトリーと統合する場合にのみ、Creative Cloudアプリケーション Asset Link のアプリ内パネルを使用できます。

Assets EssentialsをCreative Cloudアプリケーションと統合するには、次のタスクを実行します。

* [ディレクトリとCreative Cloudの間のExperience Cloud信頼を作成](#directory-trusting-cc-assets-essentials-consoles)

* [Assets Essentials製品プロファイルへのCreative Cloudユーザーの追加](#add-cc-users-assets-essentials-product-profiles)

* [AdobeAsset Link のインストール](#install-asset-link)

* [Adobe Asset Link の使用](#use-asset-link)

## ディレクトリとExperience CloudのCreative CloudAdmin Console {#directory-trusting-cc-assets-essentials-consoles}

Creative CloudがAssets Essentials(Experience Cloudソリューション ) とは別のAdobe管理コンソールにデプロイされている場合、2 つのコンソール間に信頼関係を追加する必要があります。

Creative CloudとAssets Essentialsアプリケーションを統合するには、Admin ConsoleでCreative Cloudに使用できるユーザーが、Experience CloudにAdmin Consoleして使用できるようにする必要があります。 Creative CloudとAssets Essentialsが別々のAdmin Consoleにデプロイされている場合、これを有効にするには、それらの間の信頼関係が必要です。

Experience CloudAdmin Consoleで、 **[!UICONTROL 設定]** また、 **[!UICONTROL ディレクトリ]** タブを使用して、設定するディレクトリを作成します。 [ディレクトリ信頼](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) 2 つのAdmin Consoleの

## Assets Essentials製品プロファイルへのCreative Cloudユーザーの追加 {#add-cc-users-assets-essentials-product-profiles}

Creative CloudのAdmin ConsoleとExperience CloudのAdmin Consoleの間でディレクトリ信頼を確立した後、Creative Cloudユーザーを **[!DNL Assets Essentials]ユーザー** 下の製品プロファイル [!DNL Assets Essentials] 製品カード (Experience CloudAdmin Console) これにより、Creative Cloudユーザーは、Asset Link プラグインパネルからAssets Essentialsにアクセスできます。さらに、web ブラウザーを使用してデジタルアセットをアップロード、整理、タグ付けおよび検索するための、Assets Essentials web ユーザーインターフェイス全体へのアクセス権もユーザーに付与されます。

その他のAssets Essentials製品プロファイル — **[!DNL Assets Essentials]管理者** および **[!DNL Assets Essentials]消費者ユーザー**  — は、様々なユーザーの使用権限 ( アプリケーション管理者およびExperience Cloudの統合を介してAssets Essentialsにアクセスするユーザー ) に使用されます。

ユーザーをAssets Essentials製品プロファイルに割り当てる方法について詳しくは、 [ユーザーをAssets Essentials製品プロファイルに割り当てる](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## AdobeAsset Link のインストール {#install-asset-link}

[!DNL Adobe Asset Link] プラグインは、次の 2 つの方法でクリエイティブユーザーにインストールして提供できます。

* クリエイティブユーザーは、自分の [!DNL Creative Cloud Desktop] アプリ
* Creative Cloud管理者は、Admin Console内のCreative Cloudパッケージに Asset Link プラグインを追加できます

選択肢は組織の IT ポリシーによって異なります。

**を使用したインストール [!DNL Creative Cloud Desktop] アプリ** が記述されている [ここ](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). 2 つのプラグインが使用可能で、でホストされています。 [Adobe交換](https://exchange.adobe.com/) marketplace に表示される値を、Creative Cloudアプリケーションに応じて次に示します。

* の場合 [!DNL Adobe Photoshop], [!DNL Adobe Illustrator]、および [!DNL Adobe InDesign]: [Adobeアセットリンク CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* の場合 [!DNL Adobe XD]: [Adobeアセットリンク](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**インストールパッケージを使用したCreative Cloud** は、Creative Cloud管理者がAdmin Consoleでおこないます。デプロイメントパッケージの構築時に Asset Link プラグインを含めることでおこなわれ、後でユーザーのマシンにデプロイできます。 管理されるプラグインの選択画面で、を検索します。 **Adobeアセットリンク** 内 **主なビジネスプラグイン** 」セクションに入力します。 詳しくは、 [Admin Console](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## Adobe Asset Link の使用 {#use-asset-link}

クリエイティブユーザーは、AdobeアセットリンクをPhotoshop、Illustrator、InDesign、XDと共に使用できるようになりました。 パネルをInDesignまたはIllustratorで開くには、Windows/拡張機能/Adobeアセットリンクに移動します。 Photoshopで、Window/Extensions (legacy)/Extensions Asset Link に移動します。

Adobe XD用のAdobeAsset Link の設定方法について詳しくは、 [ここ](https://helpx.adobe.com/jp/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>Apple Silicon/M1 ハードウェアを使用する場合、Adobe Photoshopは、CEP 拡張テクノロジーを使用して構築されているので、クリエイティブユーザーがAdobeAsset Link パネルに確実にアクセスできるように、Rosetta 互換モードで開始する必要があります。 詳しくは、 [Photoshop for Apple Silicon](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


Adobeアセットリンクを使用して、Assets Essentialsリポジトリに保存されたアセットを操作および変更します。 次のような様々なタスクを実行できます。

* アセットの検索と参照

* アセットのアップロード

* アセットの並べ替えとフィルタリング

* アセットの配置、ダウンロード、ドラッグ

* アセットのチェックアウトとチェックイン

* バージョン履歴とファイルの詳細を表示

これらのタスクの実行方法については、 [アセットアセットリンクを使用したAdobeの管理](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## 次の手順

これで、Creative CloudアプリケーションがAssets Essentials、 [Adobe WorkfrontとExperience Manager Assets Essentials の統合](integrate-assets-essentials-workfront.md).
