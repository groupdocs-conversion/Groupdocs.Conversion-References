---
title: PresentationConvertOptions
second_title: GroupDocs.Conversion for .NET API リファレンス
description: プレゼンテーション ファイル タイプへの変換オプションについて説明します
type: docs
weight: 1830
url: /ja/net/groupdocs.conversion.options.convert/presentationconvertoptions/
---
## PresentationConvertOptions class

プレゼンテーション ファイル タイプへの変換オプションについて説明します。

```csharp
public class PresentationConvertOptions : CommonConvertOptions<PresentationFileType>
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PresentationConvertOptions](presentationconvertoptions)() | の新しいインスタンスを初期化します[`PresentationConvertOptions`](../presentationconvertoptions)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Format](../../groupdocs.conversion.options.convert/convertoptions-1/format) { get; set; } | 入力ドキュメントを変換する必要がある目的のファイルの種類. |
| virtual [Format](../../groupdocs.conversion.options.convert/convertoptions/format) { get; set; } | 入力ドキュメントを変換する必要がある目的のファイルの種類. |
| [PageNumber](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagenumber) { get; set; } | 変換を開始するページ番号. |
| [Pages](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pages) { get; set; } | 変換するページ インデックスのリスト。特定のページを変換するために指定する必要があります。 |
| [PagesCount](../../groupdocs.conversion.options.convert/commonconvertoptions-1/pagescount) { get; set; } | から始まる変換するページ数`ページ番号`. |
| [Password](../../groupdocs.conversion.options.convert/presentationconvertoptions/password) { get; set; } | 変換されたドキュメントをパスワードで保護する場合は、このプロパティを設定します。 |
| [Watermark](../../groupdocs.conversion.options.convert/commonconvertoptions-1/watermark) { get; set; } | 透かし固有のオプション |
| [Zoom](../../groupdocs.conversion.options.convert/presentationconvertoptions/zoom) { get; set; } | ズーム レベルをパーセンテージで指定します。デフォルトは 100 です。 デフォルトのズームは、Microsoft Powerpoint 2010 までサポートされています。Microsoft Powerpoint 2013 以降、デフォルトのズームはドキュメントに設定されなくなりました。代わりに、最後に開いたドキュメントのズーム倍率を使用しているように見えます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.convert/convertoptions/clone)() | 現在のオプション インスタンスを複製します。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [CommonConvertOptions&lt;TFileType&gt;](../commonconvertoptions-1)
* class [PresentationFileType](../../groupdocs.conversion.filetypes/presentationfiletype)
* 名前空間 [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
