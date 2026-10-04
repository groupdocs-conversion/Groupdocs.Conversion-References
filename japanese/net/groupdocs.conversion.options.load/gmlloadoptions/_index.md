---
title: "GmlLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "GML ドキュメントの読み込みオプション。"
type: docs
weight: 2550
url: /ja/net/groupdocs.conversion.options.load/gmlloadoptions/
---
## GmlLoadOptions class

GML ドキュメントの読み込みオプション。

```csharp
public sealed class GmlLoadOptions : GisLoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [GmlLoadOptions](gmlloadoptions)() | 新しい [`GmlLoadOptions`](../gmlloadoptions) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/gmlloadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [Height](../../groupdocs.conversion.options.load/gisloadoptions/height) { get; set; } | GISドキュメントを変換する際の希望ページ高さを設定します。デフォルトは 1000 です。 |
| [LoadSchemasFromInternet](../../groupdocs.conversion.options.load/gmlloadoptions/loadschemasfrominternet) { get; set; } | Conversion がインターネットから XML スキーマを読み込むことを許可するかどうかを決定します。false に設定すると、‘file://’ で始まらない絶対 URI を持つスキーマは読み込まれません。既定値は false です。 |
| [RestoreSchema](../../groupdocs.conversion.options.load/gmlloadoptions/restoreschema) { get; set; } | XML スキーマが欠落しているかロードできない Gml ファイルの属性を解析することを Conversion が許可するかどうかを決定します。true に設定すると、Conversion リーダーは XML スキーマの存在を必要としません。デフォルトは false です。 |
| [SchemaLocation](../../groupdocs.conversion.options.load/gmlloadoptions/schemalocation) { get; set; } | スペースで区切られた URI ペアのリストです。各ペアの最初の URI は名前空間の URI で、2 番目の URI はその名前空間の XML スキーマへのパスです。null に設定すると、Conversion はドキュメントのルート要素から schemaLocation の読み取りを試みます。デフォルトは null です。 |
| [Width](../../groupdocs.conversion.options.load/gisloadoptions/width) { get; set; } | GISドキュメントを変換する際の希望ページ幅を設定します。デフォルトは 1000 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [GisLoadOptions](../gisloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
