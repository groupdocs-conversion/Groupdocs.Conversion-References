---
title: "VcfLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Vcf ドキュメントの読み込みオプション。"
type: docs
weight: 2890
url: /ja/net/groupdocs.conversion.options.load/vcfloadoptions/
---
## VcfLoadOptions class

Vcf ドキュメントの読み込みオプション。

```csharp
public sealed class VcfLoadOptions : LoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [VcfLoadOptions](vcfloadoptions)() | 新しい [`VcfLoadOptions`](../vcfloadoptions) クラスのインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Encoding](../../groupdocs.conversion.options.load/vcfloadoptions/encoding) { get; set; } | Vcf ドキュメントの読み込み時に使用されるエンコーディングを取得または設定します。デフォルトは Encoding.Default です。 |
| [Format](../../groupdocs.conversion.options.load/vcfloadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |

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
