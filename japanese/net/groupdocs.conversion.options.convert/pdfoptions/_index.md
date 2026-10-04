---
title: "PdfOptions"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "PDFファイルタイプへの変換オプション。"
type: docs
weight: 2130
url: /ja/net/groupdocs.conversion.options.convert/pdfoptions/
---
## PdfOptions class

PDFファイルタイプへの変換オプション。

```csharp
public sealed class PdfOptions : ValueObject, IZoomConvertOptions
```

## Constructors

| 名前 | 説明 |
| --- | --- |
| [PdfOptions](pdfoptions)() | [`PdfOptions`](../pdfoptions) クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DocumentInfo](../../groupdocs.conversion.options.convert/pdfoptions/documentinfo) { get; set; } | PDF 文書のメタ情報。 |
| [FormattingOptions](../../groupdocs.conversion.options.convert/pdfoptions/formattingoptions) { get; set; } | PDF フォーマットオプション |
| [Grayscale](../../groupdocs.conversion.options.convert/pdfoptions/grayscale) { get; set; } | PDF を RGB カラースペースからグレースケールに変換する |
| [Linearize](../../groupdocs.conversion.options.convert/pdfoptions/linearize) { get; set; } | Web 用に PDF 文書をリニアライズする |
| [OptimizationOptions](../../groupdocs.conversion.options.convert/pdfoptions/optimizationoptions) { get; set; } | PDF 最適化オプション |
| [PdfFormat](../../groupdocs.conversion.options.convert/pdfoptions/pdfformat) { get; set; } | 変換された文書の PDF 形式を設定します。 |
| [RemovePdfACompliance](../../groupdocs.conversion.options.convert/pdfoptions/removepdfacompliance) { get; set; } | Pdf-A 準拠を削除する |
| [Zoom](../../groupdocs.conversion.options.convert/pdfoptions/zoom) { get; set; } | ズームレベルをパーセンテージで指定します。デフォルトは 100 です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2つのオブジェクトインスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* interface [IZoomConvertOptions](../izoomconvertoptions)
* namespace [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* assembly [GroupDocs.Conversion](../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
