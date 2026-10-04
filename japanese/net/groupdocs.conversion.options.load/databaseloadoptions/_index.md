---
title: "DatabaseLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "データベースドキュメントの読み込みオプション。"
type: docs
weight: 2460
url: /ja/net/groupdocs.conversion.options.load/databaseloadoptions/
---
## DatabaseLoadOptions class

データベースドキュメントの読み込みオプション。

```csharp
public sealed class DatabaseLoadOptions : LoadOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [DatabaseLoadOptions](databaseloadoptions)() | 新しいインスタンスの [`DatabaseLoadOptions`](../databaseloadoptions) クラスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.load/databaseloadoptions/format) { get; set; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
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
