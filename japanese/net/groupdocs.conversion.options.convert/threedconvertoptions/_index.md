---
title: "ThreeDConvertOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "3Dタイプへの変換オプション。"
type: docs
weight: 2250
url: /ja/net/groupdocs.conversion.options.convert/threedconvertoptions/
---
## ThreeDConvertOptions class

3Dタイプへの変換オプション。

```csharp
public class ThreeDConvertOptions : ConvertOptions<ThreeDFileType>, IPagedConvertOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [ThreeDConvertOptions](threedconvertoptions)() | 新しいインスタンスを初期化します [`ThreeDConvertOptions`](../threedconvertoptions) クラス。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する際の希望ファイルタイプ |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | [`Format`](../iconvertoptions/format) を実装します |
| [PageNumber](../../groupdocs.conversion.options.convert/threedconvertoptions/pagenumber) { get; set; } | [`PageNumber`](../ipagedconvertoptions/pagenumber) を実装します |
| [PagesCount](../../groupdocs.conversion.options.convert/threedconvertoptions/pagescount) { get; set; } | [`PagesCount`](../ipagedconvertoptions/pagescount) を実装します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプションインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [ThreeDFileType](../../groupdocs.conversion.filetypes/threedfiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
