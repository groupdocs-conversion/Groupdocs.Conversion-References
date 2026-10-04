---
title: "FinanceConvertOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "finance タイプへの変換オプションです。"
type: docs
weight: 1810
url: /ja/net/groupdocs.conversion.options.convert/financeconvertoptions/
---
## FinanceConvertOptions class

finance タイプへの変換オプションです。

```csharp
public class FinanceConvertOptions : ConvertOptions<FinanceFileType>, IPagedConvertOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [FinanceConvertOptions](financeconvertoptions)() | [`FinanceConvertOptions`](../financeconvertoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する際の希望ファイルタイプ |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | [`Format`](../iconvertoptions/format) を実装します |
| [PageNumber](../../groupdocs.conversion.options.convert/financeconvertoptions/pagenumber) { get; set; } | [`PageNumber`](../ipagedconvertoptions/pagenumber) を実装します |
| [PagesCount](../../groupdocs.conversion.options.convert/financeconvertoptions/pagescount) { get; set; } | [`PagesCount`](../ipagedconvertoptions/pagescount) を実装します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプションインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [FinanceFileType](../../groupdocs.conversion.filetypes/financefiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
