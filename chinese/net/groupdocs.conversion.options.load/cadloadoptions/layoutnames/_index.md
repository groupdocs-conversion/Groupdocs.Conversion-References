---
title: "LayoutNames"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "指定要转换的 CAD 布局。"
type: docs
weight: 70
url: /zh/net/groupdocs.conversion.options.load/cadloadoptions/layoutnames/
---
## CadLoadOptions.LayoutNames property

指定要转换的 CAD 布局。

```csharp
public string[] LayoutNames { get; set; }
```

### 备注

在转换为 PDF/UA-1 时不予尊重。该目标将图形渲染为单个标记页面，无法为每个选定布局携带单独的页，因此整个图形会被转换，而此处的设置不适用。其他所有目标（包括 PDF）都会尊重该选择。在这些目标上，名称会严格匹配图形所包含的布局，因此仅大小写不同的名称被视为不同名称。与任何布局都不匹配的名称会被丢弃，仅导致调用方失去该页；如果列表中所有名称均未匹配，转换将因 [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) 而失败，异常会列出未匹配的名称以及图形实际包含的布局，而不是渲染调用方未请求的页。完全不包含任何布局的图形除外：因为没有名称可匹配，所以不会被拒绝。

### 另见

* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
