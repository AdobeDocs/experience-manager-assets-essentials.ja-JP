---
title: Assets Essentials と Creative Cloud アプリケーションの統合
description: Assets Essentials を Creative Cloud アプリケーションと統合して、Adobe Asset Link のアプリ内パネルを使用して、サポート対象の [!DNL Adobe Creative Cloud] デスクトップアプリケーション内から [!DNL Assets Essentials] リポジトリに接続できるようにします。
exl-id: 611fd958-3fd3-4c46-bee9-8b866b7dc208
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: ht
source-wordcount: '854'
ht-degree: 100%

---

# Assets Essentials と Creative Cloud アプリケーションの統合 {#integrate-assets-essentials-creative-cloud-applications}

![暗いテーマと明るいテーマを切り替えるための環境設定](assets/cce-creative-cloud.png)

## これまでの説明内容

このチュートリアルで [Experience Manager Assets Essentials を設定](adminster-aem-assets-essentials.md)したら、エクスペリエンスに基づいて、Creative Cloud アプリケーションを Assets Essentials と統合できます。

## 目的

* **対象読者**：Creative Cloud 管理者

* **目的**：Assets Essentials を Creative Cloud アプリケーションと統合して、クリエイティブユーザーが Adobe Asset Link のアプリ内パネルを使用して、サポート対象の [!DNL Adobe Creative Cloud] デスクトップアプリケーション内から [!DNL Assets Essentials] リポジトリに接続できるようにします。

## 概要

[Adobe Asset Link のアプリ内パネル](https://www.adobe.com/jp/creativecloud/business/enterprise/adobe-asset-link.html)を使用すると、クリエイティブプロフェッショナルは、サポート対象の [!DNL Adobe Creative Cloud] デスクトップアプリケーション内から [!DNL Assets Essentials] リポジトリに接続できます。このパネルは、[!DNL Adobe Photoshop]、[!DNL Adobe Illustrator]、[!DNL Adobe InDesign] および [!DNL Adobe XD] で使用できます。これにより、アセットへのアクセスが効率化され、結果としてコンテンツベロシティ（コンテンツ創出速度）が向上します。

Creative Cloud アプリケーションのユーザーは、Creative Cloud アプリケーションを Experience Manager Assets Essentials リポジトリと統合した場合にのみ、Adobe Asset Link のアプリ内パネルを使用できます。

Assets Essentials を Creative Cloud アプリケーションと統合するには、次のタスクを実行します。

* [Creative Cloud と Experience Cloud の Admin Console 間のディレクトリトラストの作成](#directory-trusting-cc-assets-essentials-consoles)

* [Assets Essentials 製品プロファイルへの Creative Cloud ユーザーの追加](#add-cc-users-assets-essentials-product-profiles)

* [Adobe Asset Link のインストール](#install-asset-link)

* [Adobe Asset Link の使用](#use-asset-link)

## Creative Cloud と Experience Cloud の Admin Console 間のディレクトリトラストの作成 {#directory-trusting-cc-assets-essentials-consoles}

Creative Cloud が Assets Essentials（Experience Cloud ソリューション）の Adobe Admin Console とは別の Admin Console にデプロイされている場合は、2 つのコンソール間に信頼関係を追加する必要があります。

Creative Cloud と Assets Essentials のアプリケーションを統合するには、Creative Cloud の Admin Console で使用できるユーザーを、Experience Cloud の Admin Console でも使用できるようにする必要があります。Creative Cloud と Assets Essentials が別々の Admin Console にデプロイされている場合、これを可能にするには、両者間の信頼関係が必要です。

Experience Cloud Admin Console で「**[!UICONTROL 設定]**」をクリックし、「**[!UICONTROL ディレクトリ]**」タブを使用して、2 つの Admin Console 間に[ディレクトリトラスト](https://helpx.adobe.com/jp/enterprise/using/set-up-identity.html#directory-trusting)を確立するためのディレクトリを作成します。

## Assets Essentials 製品プロファイルへの Creative Cloud ユーザーの追加 {#add-cc-users-assets-essentials-product-profiles}

Creative Cloud の Admin Console と Experience Cloud の Admin Console の間にディレクトリトラストを確立したら、Experience Cloud Admin Console の [!DNL Assets Essentials] 製品カードで Creative Cloud ユーザーを **[!DNL Assets Essentials]ユーザー**&#x200B;製品プロファイルに割り当てます。これで、Creative Cloud ユーザーは、Adobe Asset Link プラグインパネルから Assets Essentials にアクセスできるようになります。さらに、web ブラウザーを使用してデジタルアセットをアップロード、整理、タグ付けおよび検索するための、Assets Essentials web ユーザーインターフェイス全体へのアクセス権もユーザーに付与されます。

他の Assets Essentials 製品プロファイル（**[!DNL Assets Essentials]管理者**&#x200B;および **[!DNL Assets Essentials]消費者ユーザー**）は、別のユーザー使用権限（Experience Cloud 統合を通じて Assets Essentials にアクセスするアプリケーション管理者およびユーザー）に使用されます。

ユーザーを Assets Essentials 製品プロファイルに割り当てる方法について詳しくは、[Assets Essentials 製品プロファイルへのユーザーの割り当て](adminster-aem-assets-essentials.md#add-users-to-product-profiles)を参照してください。

## Adobe Asset Link のインストール {#install-asset-link}

[!DNL Adobe Asset Link] プラグインは、次の 2 とおりの方法でインストールしてクリエイティブユーザーから利用できます。

* クリエイティブユーザーが自分の [!DNL Creative Cloud Desktop] アプリケーションからプラグインをインストールできます
* Creative Cloud 管理者が Admin Console で Creative Cloud パッケージに Asset Link プラグインを追加できます

どちらを選択するかは組織の IT ポリシーによって異なります。

**[!DNL Creative Cloud Desktop] アプリケーションを使用したインストール**&#x200B;については、[こちら](https://helpx.adobe.com/jp/creative-cloud/kb/installingextensionsandaddons.html)を参照してください。Creative Cloud アプリケーションによっては、2 つのプラグインが使用可能で、[Adobe Exchange](https://exchange.adobe.com/) Marketplace でホストされています。

* [!DNL Adobe Photoshop]、[!DNL Adobe Illustrator] および [!DNL Adobe InDesign] の場合：[Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* [!DNL Adobe XD] の場合：[Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Creative Cloud パッケージを使用したインストール**&#x200B;は、Creative Cloud 管理者が Admin Console でデプロイメントパッケージのビルド時に Asset Link プラグインを組み込むことで行います。このパッケージは後でユーザーのマシンにデプロイできます。管理されているプラグインを選択画面の「**注目のビジネスプラグイン**」セクションで、**Adobe Asset Link** を検索します。詳しくは、[Admin Console でのアプリのパッケージ化](https://helpx.adobe.com/jp/enterprise/using/package-apps-admin-console.html)を参照してください。

## Adobe Asset Link の使用 {#use-asset-link}

クリエイティブユーザーは、Adobe Asset Link を Photoshop、Illustrator、InDesign または XD で使用できるようになりました。パネルを InDesign または Illustrator で開くには、ウィンドウ／エクステンション／Adobe Asset Link に移動します。 Photoshop では、ウィンドウ／エクステンション（従来）／Adobe Asset Link に移動します。

Adobe XD 用に Adobe Asset Link を設定する方法については、[ここ](https://helpx.adobe.com/jp/enterprise/using/adobe-asset-link-for-xd.html)をクリックしてください。

>[!NOTE]
>
>Apple シリコン／M1 ハードウェアを使用する場合は、クリエイティブユーザーが Adobe Asset Link パネルに確実にアクセスできるように、Adobe Photoshop を Rosetta 互換モードで起動する必要があります。パネルが CEP エクステンションテクノロジーを使用してビルドされているからです。詳しくは、[Apple Silicon での Photoshop の使用](https://helpx.adobe.com/jp/photoshop/kb/photoshop-for-apple-silicon.html)を参照してください。


Adobe Asset Link を使用して、Assets Essentials リポジトリに保存されているアセットを操作および変更します。次のような様々なタスクを実行できます。

* アセットの検索と参照

* アセットのアップロード

* アセットの並べ替えとフィルタリング

* アセットの配置、ダウンロードおよびドラッグ

* アセットのチェックアウトとチェックイン

* バージョン履歴とファイル詳細の表示

これらのタスクの実行方法については、[Adobe Asset Link を使用したアセットの管理](https://helpx.adobe.com/jp/enterprise/using/manage-assets-using-adobe-asset-link.html)を参照してください。

## 次のステップ

これで、Creative Cloud アプリケーションと Assets Essentials の統合が完了したので、[Adobe Workfront と Experience Manager Assets Essentials の統合](integrate-assets-essentials-workfront.md)を行います。
