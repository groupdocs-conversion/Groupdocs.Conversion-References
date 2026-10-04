---
title: "SvgLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Svg ドキュメントの読み込みオプション。"
type: docs
weight: 2830
url: /ja/net/groupdocs.conversion.options.load/svgloadoptions/
---
## SvgLoadOptions class

Svg ドキュメントの読み込みオプション。

```csharp
public class SvgLoadOptions : LoadOptions, IResourceLoadingOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | 新しい [`SvgLoadOptions`](../svgloadoptions) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CropToContentBounds](../../groupdocs.conversion.options.load/svgloadoptions/croptocontentbounds) { get; set; } | 変換前に SVG のバウンディングボックスをコンテンツの境界に合わせて切り取るかどうかを示す値を取得または設定します。既定値は false です。 |
| [Format](../../groupdocs.conversion.options.load/svgloadoptions/format) { get; set; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [MinimumHeight](../../groupdocs.conversion.options.load/svgloadoptions/minimumheight) { get; set; } | SVG ドキュメントを変換する際の最小高さを設定します。ラスタ形式に変換する場合に使用されます。既定値は 600 です。 |
| [MinimumWidth](../../groupdocs.conversion.options.load/svgloadoptions/minimumwidth) { get; set; } | SVG ドキュメントを変換する際の最小幅を設定します。ラスタ形式に変換する場合に使用されます。既定値は 800 です。 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/svgloadoptions/skipexternalresources) { get; set; } | 実装: [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [WhitelistedResources](../../groupdocs.conversion.options.load/svgloadoptions/whitelistedresources) { get; set; } | 常に読み込まれる外部リソース。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [LoadOptions](../loadoptions)
* interface [IResourceLoadingOptions](../iresourceloadingoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
