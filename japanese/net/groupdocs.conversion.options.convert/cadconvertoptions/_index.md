---
title: "CadConvertOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Cad タイプへの変換オプションです。"
type: docs
weight: 1730
url: /ja/net/groupdocs.conversion.options.convert/cadconvertoptions/
---
## CadConvertOptions class

Cad タイプへの変換オプションです。

```csharp
public class CadConvertOptions : ConvertOptions<CadFileType>, IPagedConvertOptions, IPageSizeOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [CadConvertOptions](cadconvertoptions)() | 新しいインスタンスを初期化します [`CadConvertOptions`](../cadconvertoptions) クラス。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する際の希望ファイルタイプ |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | [`Format`](../iconvertoptions/format) を実装します |
| [PageNumber](../../groupdocs.conversion.options.convert/cadconvertoptions/pagenumber) { get; set; } | [`PageNumber`](../ipagedconvertoptions/pagenumber) を実装します |
| [PagesCount](../../groupdocs.conversion.options.convert/cadconvertoptions/pagescount) { get; set; } | [`PagesCount`](../ipagedconvertoptions/pagescount) を実装します |
| [SizeSettings](../../groupdocs.conversion.options.convert/cadconvertoptions/sizesettings) { get; set; } | ページサイズ設定 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプションインスタンスをクローンします。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ConvertOptions&lt;TFileType&gt;](../convertoptions-1)
* class [CadFileType](../../groupdocs.conversion.filetypes/cadfiletype)
* interface [IPagedConvertOptions](../ipagedconvertoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
