---
title: "EBookConvertOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "EBook ファイルタイプへの変換オプションです。"
type: docs
weight: 1790
url: /ja/net/groupdocs.conversion.options.convert/ebookconvertoptions/
---
## EBookConvertOptions class

EBook ファイルタイプへの変換オプションです。

```csharp
public class EBookConvertOptions : CommonConvertOptions<EBookFileType>, IPageOrientationOptions, 
    IPageSizeOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [EBookConvertOptions](ebookconvertoptions)() | 新しいインスタンスを初期化します [`EBookConvertOptions`](../ebookconvertoptions) クラス。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [FallbackPageSize](../../groupdocs.conversion.options.convert/ebookconvertoptions/fallbackpagesize) { get; set; } | フォールバックページサイズ |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する際の希望ファイルタイプ |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | [`Format`](../iconvertoptions/format) を実装します |
| [OrientationSettings](../../groupdocs.conversion.options.convert/ebookconvertoptions/orientationsettings) { get; set; } | ページの向き設定 |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | [`PageNumber`](../ipagedconvertoptions/pagenumber) を実装します |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | [`Pages`](../ipagerangedconvertoptions/pages) を実装します |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | [`PagesCount`](../ipagedconvertoptions/pagescount) を実装します |
| [SizeSettings](../../groupdocs.conversion.options.convert/ebookconvertoptions/sizesettings) { get; set; } | ページサイズ設定 |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | [`Watermark`](../iwatermarkedconvertoptions/watermark) を実装します |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプションインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [EBookFileType](../../groupdocs.conversion.filetypes/ebookfiletype)
* interface [IPageOrientationOptions](../../groupdocs.conversion.options/ipageorientationoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
