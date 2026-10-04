---
title: "PageDescriptionLanguageConvertOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ページ記述言語ファイルタイプへの変換オプション。"
type: docs
weight: 2030
url: /ja/net/groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/
---
## PageDescriptionLanguageConvertOptions class

ページ記述言語ファイルタイプへの変換オプション。

```csharp
public class PageDescriptionLanguageConvertOptions : 
    CommonConvertOptions<PageDescriptionLanguageFileType>
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [PageDescriptionLanguageConvertOptions](pagedescriptionlanguageconvertoptions)() | `[`PageDescriptionLanguageConvertOptions`](../pagedescriptionlanguageconvertoptions)` の新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する際の希望ファイルタイプ |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | [`Format`](../iconvertoptions/format) を実装します |
| [Height](../../groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/height) { get; set; } | 変換後のページ高さ（デバイス非依存ピクセル（1/96インチ）単位）。0 のままにすると、対象が自動的に導出したページ高さを保持します。 |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | [`PageNumber`](../ipagedconvertoptions/pagenumber) を実装します |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | [`Pages`](../ipagerangedconvertoptions/pages) を実装します |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | [`PagesCount`](../ipagedconvertoptions/pagescount) を実装します |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | [`Watermark`](../iwatermarkedconvertoptions/watermark) を実装します |
| [Width](../../groupdocs.conversion.options.convert/pagedescriptionlanguageconvertoptions/width) { get; set; } | 変換後のページ幅（デバイス非依存ピクセル（1/96インチ）単位）。0 のままにすると、対象が自動的に導出したページ幅を保持します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプションインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PageDescriptionLanguageFileType](../../groupdocs.conversion.filetypes/pagedescriptionlanguagefiletype)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
