---
title: "AutoDetectRtlDirection"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "当设置为 true 时，默认段落和文本主要为 righttoleft 的运行将在转换前修复其 bidi 标志。这与 Microsoft Word 和 LibreOffice 使用的启发式方法相匹配，并修复了由生成器（尤其是 Google Docs）产生的阿拉伯语/希伯来语文档的渲染问题，这些文档在仅包含 RTL 脚本的运行上会发出缺少 ltwbidi/gt 且带有 ltwrtl wval0/gt 的 OOXML。将其设置为 false 可保留对源标记的严格 OOXML 解释。"
type: docs
weight: 20
url: /zh/net/groupdocs.conversion.options.load/wordprocessingloadoptions/autodetectrtldirection/
---
## WordProcessingLoadOptions.AutoDetectRtlDirection property

当为 true（默认）时，文本主要为从右到左的段落和运行将在转换前修复其 bidi 标志。这与 Microsoft Word 和 LibreOffice 使用的启发式方法相匹配，并修复了由生成器（尤其是 Google Docs）生成的阿拉伯语/希伯来语文档的渲染问题，这些文档在仅包含 RTL 脚本的运行中未包含 &lt;w:bidi/&gt; 且使用 &lt;w:rtl w:val="0"/&gt;。将其设为 false 可保留对源标记的严格 OOXML 解释。

```csharp
public bool AutoDetectRtlDirection { get; set; }
```

### 另见

* class [WordProcessingLoadOptions](../../wordprocessingloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
