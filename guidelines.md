---
source-git-commit: 15070ea99308741242b43206ed69cf1dbddca890
workflow-type: tm+mt
source-wordcount: '733'
ht-degree: 3%
---
# [!DNL Adobe Experience Manager] ドキュメントへの投稿に関するガイドライン

## 文書哲学

[!DNL Adobe Experience Manager]人のユーザーが非常に競争的な環境で作業しており、競合他社と差別化するデジタル体験の構築に努めていることがわかります。 したがって、Adobeが[!DNL Experience Manager]で高度な新しいツールを提供する際には、これらのツールを正確かつ明確なドキュメントで補完し、お客様が[!DNL Experience Manager]への投資をすぐに活用してROIを最大化できるようにすることが重要です。

[!DNL Experience Manager] ドキュメントの目標は、できるだけ早く[!DNL Experience Manager]人のユーザーにドキュメントを渡すことです。 そのため、正確で使いやすい文書を優先し、継続的な更新と改善に努めています。

## ドキュメントの貢献

[!DNL Experience Manager]のドキュメントを継続的に改善するため、[!DNL Experience Manager]人のユーザーのコミュニティ全員がドキュメントに参加することを歓迎します。 プルリクエストや問題を通じて、ドキュメントを改善することは、修正、明確化、拡張、その他の例になります。

## Documentation Standards

私たちのドキュメントへの貢献を歓迎しますが、[!DNL Experience Manager] ドキュメントへの貢献は、プルリクエストまたは問題の形式で、私たちの貢献とドキュメントの基準に準拠する必要があります。

これらの基準を満たさない寄付は拒否される場合があります。

### 標準的なユースケースを文書化し

[!DNL Experience Manager]のドキュメントでは、標準的なユースケースについて説明しています。 標準インストールの範囲を超えたユースケースと製品の使用は、[!DNL Experience Manager] ドキュメントには含まれません。

### 通常、バグやその回避策を文書化することはありません

[!DNL Experience Manager]のドキュメントでは、標準的なユースケースについて説明しています。 このため、バグ、バグによる影響、バグの回避策は一般的には文書化されていません。

このルールの例外は、既知の問題を[!DNL Experience Manager]製品管理によって承認された可能性のある解決策と共に一覧表示できるリリースノートに適用されます。

### ドキュメントへの投稿は、技術的な質問に答えるためのものではありません

[!DNL Experience Manager]のドキュメントを改善するために必要なアイデアは、寄付として歓迎されます。 ただし、コメント、イシュー、およびプルリクエストは、*寄付*&#x200B;のみを対象としています。 これらは、[!DNL Experience Manager]の使用方法、[!DNL Experience Manager] プロジェクトの実装、技術的な問題の解決に関する質問への回答を目的としたものではありません。

[!DNL Experience Manager]の使用状況や技術的なエラーに関する質問は、[[!DNL Experience Manager]  サポートポータル &#x200B;](https://experienceleague.adobe.com/ja?support-solution=Experience+Manager&lang=ja#support)を通じて通常のサポートプロセスを通じて報告するか、[Experience Manager コミュニティ &#x200B;](https://experienceleaguecommunities.adobe.com/t5/adobe-experience-manager/ct-p/adobe-experience-manager-community?profile.language=ja)で相談する必要があります。

***[!DNL Experience Manager]件のドキュメントへの投稿は、Adobe カスタマーサポート***&#x200B;の代替となるものではなく、サポート関連の質問に対する回答を求めるそのような投稿は拒否されます。

### 投稿では、影響を受けるドキュメントページを明確に参照する必要があります。

ドキュメントの改善を提案する問題を作成する場合は、影響を受けるページへのリンクを含める必要があります。 ドキュメント ページの&#x200B;**このページを編集** リンクを使用してイシューを作成すると、そのイシューは自動的にページへのリンクとともに作成されます。

これは、プルリクエストが影響を受けるページを参照するため、プルリクエストには適用されません。

## ドキュメントのガイドライン

ドキュメントへの貢献は、特定のスタイルガイドラインに従うように求めます。

これらのガイドラインに従うことで、貢献度のレビューが簡単になり、ドキュメントへの統合がより迅速になります。

### 言語とスタイル

#### 言語

* [!DNL Experience Manager]件のドキュメントは米国英語で作成および管理されています。
* 文章はできるだけシンプルにする：
* 言語を明確かつ簡潔にする：

[!DNL Experience Manager]のドキュメントの読者は世界中に広がっており、ネイティブまたは流暢な英語を話す人とは期待できません。 口語体を避け、できるだけ明確でシンプルな言葉を守りましょう。

#### Microsoftのスタイルマニュアルに従う

[Microsoftのスタイルのマニュアル &#x200B;](https://docs.microsoft.com/en-us/style-guide/welcome/)は、ソフトウェアのドキュメントに焦点を当てた無料で利用できるドキュメントのスタイルガイドです。また、[!DNL Experience Manager]のドキュメントは、可能な限りこのガイドに従います。

### 書式設定

| 項目 | スタイル |
|---|---|
| UI要素またはオプション | **太字** |
| Filename, path, user-input, parameter-values | `monospaced` |
| コード、コマンドライン | ```Code Block``` |

### スクリーンショット

スクリーンショットは慎重に使用し、テキストの説明が不十分な場合にのみ使用します。

スクリーンショット内のマーカーやその他の注釈（赤いフレーム、矢印、テキストなど）は使用しないでください。 これにより、スクリーンショットは、ローカライズされたバージョンのドキュメントで再利用したり、複製したりしやすくなります。

### バージョン固有の参照

可能な限り、ドキュメントコンテンツ全体で特定のバージョンへの直接参照を避けるようにしてください。 これにより、将来のバージョンに備えて、ドキュメントの柔軟性と拡張性が向上します。

### Day、[!DNL Experience Manager]、CQ、CRXの使用状況

記事の最初の使用については、フルネーム **Adobe Experience Manager**&#x200B;で製品を参照し、**Experience Manager**&#x200B;と呼んでください。

クラス名や[!DNL Experience Manager]の履歴を参照するなどの避けられない場合を除き、Day、Day Software、CQ、CRXの用語は使用しないでください。
