---
title: PdfOptimizationOptions
second_title: GroupDocs.Conversion for .NET API リファレンス
description: Pdf 最適化オプションを定義します
type: docs
weight: 1780
url: /ja/net/groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
## PdfOptimizationOptions class

Pdf 最適化オプションを定義します。

```csharp
public sealed class PdfOptimizationOptions : ValueObject
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [PdfOptimizationOptions](pdfoptimizationoptions)() | の新しいインスタンスを初期化します[`PdfOptimizationOptions`](../pdfoptimizationoptions)class. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CompressImages](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/compressimages) { get; set; } | CompressImages がに設定されている場合`真実`、ドキュメント内のすべての画像が再圧縮されます。圧縮は、ImageQuality プロパティによって定義されます。 |
| [ImageQuality](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/imagequality) { get; set; } | パーセント値で、100% は品質と画像サイズが変更されていないことを示します。画像サイズを小さくするには、このプロパティを 100 未満に設定します |
| [LinkDuplicateStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/linkduplicatestreams) { get; set; } | リンク重複ストリーム |
| [RemoveUnusedObjects](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedobjects) { get; set; } | 未使用のオブジェクトを削除 |
| [RemoveUnusedStreams](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/removeunusedstreams) { get; set; } | 未使用のストリームを削除します |
| [UnembedFonts](../../groupdocs.conversion.options.convert/pdfoptimizationoptions/unembedfonts) { get; set; } | true に設定するとフォントを埋め込まないようにする |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 2 つのオブジェクト インスタンスが等しいかどうかを判断します。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | デフォルトのハッシュ関数として機能します。 |

### 関連項目

* class [ValueObject](../../groupdocs.conversion.contracts/valueobject)
* 名前空間 [GroupDocs.Conversion.Options.Convert](../../groupdocs.conversion.options.convert)
* 組み立て [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
