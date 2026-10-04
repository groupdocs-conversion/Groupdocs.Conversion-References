---
title: "TxtLoadOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "Txt ドキュメントの読み込みオプション。"
type: docs
weight: 2870
url: /ja/net/groupdocs.conversion.options.load/txtloadoptions/
---
## TxtLoadOptions class

Txt ドキュメントの読み込みオプション。

```csharp
public sealed class TxtLoadOptions : LoadOptions, IPageMarginOptions, IPageSizeOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [TxtLoadOptions](txtloadoptions)() | [`TxtLoadOptions`](../txtloadoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DefaultFont](../../groupdocs.conversion.options.load/txtloadoptions/defaultfont) { get; set; } | 変換中にプレーンテキストコンテンツをレンダリングする際に使用するフォント。TXT ファイルにはフォント情報が含まれないため、このプロパティはテキストコンテンツの表示フォントを指定します。デフォルト: Arial 10pt。 |
| [DetectNumberingWithWhitespaces](../../groupdocs.conversion.options.load/txtloadoptions/detectnumberingwithwhitespaces) { get; set; } | プレーンテキスト文書が変換される際に、番号付きリスト項目がどのように認識されるかを指定できます。デフォルト値は true です。 |
| [Encoding](../../groupdocs.conversion.options.load/txtloadoptions/encoding) { get; set; } | Txt 文書を読み込む際に使用されるエンコーディングを取得または設定します。null にすることも可能です。デフォルトは null です。 |
| [Format](../../groupdocs.conversion.options.load/txtloadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。フォーマットが設定されるまで `null` であり、`null` かどうかをテストしてください。[`Unknown`](../../groupdocs.conversion.filetypes/filetype/unknown) と比較しないでください。これは決して等しくなりません。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 入力ドキュメントのファイルタイプです。 |
| [LeadingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/leadingspacesoptions) { get; set; } | 先頭スペースの処理に関する優先オプションを取得または設定します。デフォルト値は [`ConvertToIndent`](../txtleadingspacesoptions/converttoindent) です。 |
| [MarginSettings](../../groupdocs.conversion.options.load/txtloadoptions/marginsettings) { get; set; } | ページ余白設定 |
| [SizeSettings](../../groupdocs.conversion.options.load/txtloadoptions/sizesettings) { get; set; } | ページサイズ設定 |
| [TrailingSpacesOptions](../../groupdocs.conversion.options.load/txtloadoptions/trailingspacesoptions) { get; set; } | 末尾スペースの処理に関する優先オプションを取得または設定します。デフォルト値は [`Trim`](../txttrailingspacesoptions/trim) です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 備考

**Font Configuration for Plain Text:**

TXT ファイルにはフォント情報が含まれないため、DefaultTextFont を使用して指定します

変換中にプレーンテキストコンテンツをレンダリングするためのフォントです。

### 関連項目

* class [LoadOptions](../loadoptions)
* interface [IPageMarginOptions](../../groupdocs.conversion.options/ipagemarginoptions)
* interface [IPageSizeOptions](../../groupdocs.conversion.options/ipagesizeoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
