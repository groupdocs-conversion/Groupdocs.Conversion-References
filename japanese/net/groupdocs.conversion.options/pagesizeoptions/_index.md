---
title: "PageSizeOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ページサイズをサポートするオプションを表します"
type: docs
weight: 2990
url: /ja/net/groupdocs.conversion.options/pagesizeoptions/
---
## PageSizeOptions class

ページサイズをサポートするオプションを表します

```csharp
public sealed class PageSizeOptions : ValueObject
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [PageSizeOptions](pagesizeoptions)() | デフォルトコンストラクタ。[`PageSize`](./pagesize) を [`Unset`](../pagesize/unset) に初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [PageHeight](../../groupdocs.conversion.options/pagesizeoptions/pageheight) { get; set; } | 変換前に適用されるページの高さ（ポイント）。設定すると、[`PageSize`](./pagesize) は自動的に [`Custom`](../pagesize/custom) に変更されます。 |
| [PageSize](../../groupdocs.conversion.options/pagesizeoptions/pagesize) { get; set; } | [`PageSize`](../pagesize) を実装します。 |
| [PageWidth](../../groupdocs.conversion.options/pagesizeoptions/pagewidth) { get; set; } | 変換前に適用されるページの幅（ポイント）。設定すると、[`PageSize`](./pagesize) は自動的に [`Custom`](../pagesize/custom) に変更されます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options](../../groupdocs.conversion.options)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
