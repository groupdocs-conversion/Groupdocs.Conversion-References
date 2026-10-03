---
title: "FontTransformations"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "在文档加载和字体替换完成后转换现有字体。字体转换可以修改文档中的任何字体，包括已成功加载的字体。"
type: docs
weight: 100
url: /zh/net/groupdocs.conversion.options.load/pdfloadoptions/fonttransformations/
---
## PdfLoadOptions.FontTransformations property

在文档加载和字体替换完成后转换现有字体。字体转换可以修改文档中的任何字体，包括已成功加载的字体。

```csharp
public IList<FontTransformation> FontTransformations { get; set; }
```

### 备注

**Note:** Font transformations are applied after all font substitution steps are complete.

转换按它们在列表中出现的顺序处理。

使用场景：样式更改、品牌需求、可访问性改进。

### 另见

* class [FontTransformation](../../../groupdocs.conversion.contracts/fonttransformation)
* class [PdfLoadOptions](../../pdfloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
