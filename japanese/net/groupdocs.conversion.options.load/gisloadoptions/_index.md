---
title: "GisLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "GIS ドキュメントの読み込みオプション。"
type: docs
weight: 2540
url: /ja/net/groupdocs.conversion.options.load/gisloadoptions/
---
## GisLoadOptions class

GIS ドキュメントの読み込みオプション。

```csharp
public class GisLoadOptions : LoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [GisLoadOptions](gisloadoptions)() | 新しいインスタンスの [`GisLoadOptions`](../gisloadoptions) クラスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gisloadoptions/format) { get; set; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | GISドキュメントを変換する際の希望ページ高さを設定します。デフォルトは 1000 です。 |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | GISドキュメントを変換する際の希望ページ幅を設定します。デフォルトは 1000 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [LoadOptions](../loadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
