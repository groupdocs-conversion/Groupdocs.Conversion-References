---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "PDFの最適化オプションを定義します。"
type: docs
weight: 2120
url: /ja/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

PDFの最適化オプションを定義します。

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | 新しいインスタンスを初期化します [`PdfOptimizationOptions`](../pdfoptimizationoptions) クラス。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | CompressImages が `true` に設定されている場合、ドキュメント内のすべての画像が再圧縮されます。圧縮は ImageQuality プロパティで定義されます。 |
| [FontSubsetStrategy](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/fontsubsetstrategy) { get; set; } | フォントサブセット戦略を設定する |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | 100% が品質と画像サイズが変更されないことを示すパーセンテージ値です。画像サイズを小さくするには、このプロパティを 100 未満に設定します。 |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | 重複ストリームをリンクする |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | 未使用オブジェクトを削除する |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | 未使用ストリームを削除する |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | true に設定された場合、フォントを埋め込まないようにします |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
