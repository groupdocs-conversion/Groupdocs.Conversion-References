---
title: "LayoutScope"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "获取或设置要转换的绘图空间。默认值为 Bothgroupdocs.conversion.options.load/cadlayoutscope/both，表示不限制转换。当提供 LayoutNamesgroupdocs.conversion.options.load/cadloadoptions/layoutnames 时会被忽略，因为显式布局名称始终优先。null 值会被视为 Bothgroupdocs.conversion.options.load/cadlayoutscope/both。"
type: docs
weight: 80
url: /zh/net/groupdocs.conversion.options.load/cadloadoptions/layoutscope/
---
## CadLoadOptions.LayoutScope property

获取或设置要转换的绘图空间。默认值为 [`Both`](../../cadlayoutscope/both)，表示不限制转换。当提供 [`LayoutNames`](../layoutnames) 时会被忽略，因为显式布局名称始终优先。`null` 值会被视为 [`Both`](../../cadlayoutscope/both)。

```csharp
public CadLayoutScope LayoutScope { get; set; }
```

### 备注

如果作用域未选择图形提供的任何页，则转换会因 [`InvalidLoadOptionsException`](../../../groupdocs.conversion.exceptions/invalidloadoptionsexception) 而失败，异常会列出该作用域以及现有的页，而不是渲染被作用域排除的空间。完全不提供任何页的图形不受影响，仍会作为单一单元进行转换。在转换为 PDF/UA-1 时不予尊重，原因如 [`LayoutNames`](../layoutnames) 所述。

### 另见

* class [CadLayoutScope](../../cadlayoutscope)
* class [CadLoadOptions](../../cadloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
