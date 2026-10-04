---
title: "XmlLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "XML ドキュメントの読み込みオプション。"
type: docs
weight: 2960
url: /ja/net/groupdocs.conversion.options.load/xmlloadoptions/
---
## XmlLoadOptions class

XML ドキュメントの読み込みオプション。

```csharp
public sealed class XmlLoadOptions : WebLoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [XmlLoadOptions](xmlloadoptions)() | 新しいインスタンスの [`XmlLoadOptions`](../xmlloadoptions) クラスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BasePath](../../groupdocs.conversion.options.load/webloadoptions/basepath) { get; set; } | HTML のベースパス/URL |
| [ConfigureHeaders](../../groupdocs.conversion.options.load/webloadoptions/configureheaders) { get; set; } | リクエストヘッダーの構成用アクション。アクションの最初のパラメーターは Uri です。 |
| [CredentialsProvider](../../groupdocs.conversion.options.load/webloadoptions/credentialsprovider) { get; set; } | Uri の認証情報プロバイダーです。 |
| [CustomCssStyle](../../groupdocs.conversion.options.load/webloadoptions/customcssstyle) { get; set; } | [`CustomCssStyle`](../icustomcssstyleoptions/customcssstyle) を実装します。 |
| [Encoding](../../groupdocs.conversion.options.load/webloadoptions/encoding) { get; set; } | Web ドキュメントの読み込み時に使用するエンコーディングを取得または設定します。プロパティが null の場合、エンコーディングはドキュメントの文字セット属性から決定されます。 |
| [Format](../../groupdocs.conversion.options.load/xmlloadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [HtmlRenderingMode](../../groupdocs.conversion.options.load/webloadoptions/htmlrenderingmode) { get; set; } | HTML コンテンツのレンダリング方法を制御します。デフォルト: AbsolutePositioning |
| [MarginSettings](../../groupdocs.conversion.options.load/webloadoptions/marginsettings) { get; set; } | ページ余白設定 |
| [OrientationSettings](../../groupdocs.conversion.options.load/webloadoptions/orientationsettings) { get; set; } | ページの向き設定 |
| [PageLayoutOptions](../../groupdocs.conversion.options.load/webloadoptions/pagelayoutoptions) { get; set; } | Web ドキュメントの読み込み時のページレイアウトオプションを指定します。 |
| [PageNumbering](../../groupdocs.conversion.options.load/webloadoptions/pagenumbering) { get; set; } | 変換されたドキュメントでページ番号の生成を有効または無効にします。既定: false |
| [ResourceLoadingTimeout](../../groupdocs.conversion.options.load/webloadoptions/resourceloadingtimeout) { get; set; } | 外部リソースの読み込みタイムアウト |
| [SizeSettings](../../groupdocs.conversion.options.load/webloadoptions/sizesettings) { get; set; } | ページサイズ設定 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/webloadoptions/skipexternalresources) { get; set; } | 実装: [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [UseAsDataSource](../../groupdocs.conversion.options.load/xmlloadoptions/useasdatasource) { get; set; } | XML ドキュメントをデータ ソースとして使用する |
| [UsePdf](../../groupdocs.conversion.options.load/webloadoptions/usepdf) { get; set; } | 変換に PDF を使用する。デフォルト: false |
| [WhitelistedResources](../../groupdocs.conversion.options.load/webloadoptions/whitelistedresources) { get; set; } | 実装: [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |
| [XslFoFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xslfofactory) { get; set; } | XSL-FO マークアップ ファイルを使用して XML を変換するための XSL-FO ドキュメント ストリーム。 |
| [XsltFactory](../../groupdocs.conversion.options.load/xmlloadoptions/xsltfactory) { get; set; } | XML を変換し、XSL 変換を HTML に実行するための XSLT ドキュメント ストリーム。 |
| [Zoom](../../groupdocs.conversion.options.load/webloadoptions/zoom) { get; set; } | ズームレベルをパーセンテージで指定します。ズームレベルは変換前にドキュメントの <body> タグに適用され、ドキュメントの視覚的外観をスケーリングします。100% の値は元のサイズを表します。デフォルト値は 100 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [WebLoadOptions](../webloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
