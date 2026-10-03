---
title: "CadDocumentInfo"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "包含 Cad 文档元数据"
type: docs
weight: 110
url: /zh/net/groupdocs.conversion.contracts/caddocumentinfo/
---
## CadDocumentInfo class

包含 Cad 文档元数据

```csharp
public class CadDocumentInfo : DocumentInfo
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [CreationDate](../../groupdocs.conversion.contracts/documentinfo/creationdate) { get; } | 实现 [`CreationDate`](../idocumentinfo/creationdate) |
| [Format](../../groupdocs.conversion.contracts/documentinfo/format) { get; } | 实现 [`Format`](../idocumentinfo/format) |
| [Height](../../groupdocs.conversion.contracts/caddocumentinfo/height) { get; } | 高度 |
| [Item](../../groupdocs.conversion.contracts/documentinfo/item) { get; } | 实现 [`Item`](../idocumentinfo/item) |
| [Layers](../../groupdocs.conversion.contracts/caddocumentinfo/layers) { get; } | 文档中的图层 |
| [Layouts](../../groupdocs.conversion.contracts/caddocumentinfo/layouts) { get; } | 文档中的布局 |
| [PagesCount](../../groupdocs.conversion.contracts/documentinfo/pagescount) { get; } | 实现 [`PagesCount`](../idocumentinfo/pagescount) |
| [PropertyNames](../../groupdocs.conversion.contracts/documentinfo/propertynames) { get; } | 实现 [`PropertyNames`](../idocumentinfo/propertynames) |
| [Size](../../groupdocs.conversion.contracts/documentinfo/size) { get; } | 实现 [`Size`](../idocumentinfo/size) |
| [Width](../../groupdocs.conversion.contracts/caddocumentinfo/width) { get; } | 宽度 |

### 备注

[`PagesCount`](../documentinfo/pagescount) counts the sheets the drawing offers under the load options it was read with. Without explicit [`LayoutNames`](../../groupdocs.conversion.options.load/cadloadoptions/layoutnames) those sheets are model space, which is always plottable and therefore always a sheet, plus every paper-space layout whose stored page setup has a positive width and height, narrowed by [`LayoutScope`](../../groupdocs.conversion.options.load/cadloadoptions/layoutscope). Explicit layout names win outright instead: the sheets are then the supplied names the drawing carries, matched ordinally, with neither the scope nor the page setup screening them. For a DWF the published page set is reported. The one count below one is zero, reported when the requested scope matches no sheet of a drawing that offers one: the metadata still describes the drawing, and zero says the scope selects nothing rather than failing the caller who asked what the drawing holds. A conversion under those same load options does fail. The count is therefore not the size of [`Layouts`](./layouts), which lists every plot configuration the drawing carries including those no sheet can be published from, and it does not predict how many pages a particular conversion emits.

### 另见

* class [DocumentInfo](../documentinfo)
* namespace [GroupDocs.Conversion.Contracts](../../groupdocs.conversion.contracts)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
