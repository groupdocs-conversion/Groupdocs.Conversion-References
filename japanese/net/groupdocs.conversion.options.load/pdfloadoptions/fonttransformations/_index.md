---
title: "FontTransformations"
second_title: "GroupDocs.Conversion（.NET 用）API リファレンス"
description: "ドキュメントの読み込みとフォント置換が完了した後に既存のフォントを変換します。フォント変換は、正常に読み込まれたフォントを含むドキュメント内のすべてのフォントを変更できる場合があります。"
type: docs
weight: 100
url: /ja/net/groupdocs.conversion.options.load/pdfloadoptions/fonttransformations/
---
## PdfLoadOptions.FontTransformations property

ドキュメントの読み込みとフォント置換が完了した後、既存のフォントを変換します。フォント変換により、ロードに成功したフォントを含むドキュメント内のすべてのフォントを変更できます。

```csharp
public IList<FontTransformation> FontTransformations { get; set; }
```

### 備考

**Note:** Font transformations are applied after all font substitution steps are complete.

変換はリストに表示される順序で処理されます。

使用例: スタイル変更、ブランド要件、アクセシビリティの向上。

### 関連項目

* class [FontTransformation](../../../groupdocs.conversion.contracts/fonttransformation)
* class [PdfLoadOptions](../../pdfloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 編集しないでください: xmldocmd によって GroupDocs.conversion.dll 用に生成されました -->
