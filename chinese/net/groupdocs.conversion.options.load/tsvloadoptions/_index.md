---
title: "TsvLoadOptions"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "加载 Tsv 文档的选项。"
type: docs
weight: 2850
url: /zh/net/groupdocs.conversion.options.load/tsvloadoptions/
---
## TsvLoadOptions class

加载 Tsv 文档的选项。

```csharp
public sealed class TsvLoadOptions : SpreadsheetLoadOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [TsvLoadOptions](tsvloadoptions)() | 初始化 [`TsvLoadOptions`](../tsvloadoptions) 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllColumnsInOnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/allcolumnsinonepagepersheet) { get; set; } | 如果 AllColumnsInOnePagePerSheet 为 true，则一个工作表的所有列内容将输出到结果的唯一一页。pagesetup 的纸张宽度将失效，但 pagesetup 的其他设置仍会生效。 |
| [AutoFitRows](../../groupdocs.conversion.options.load/spreadsheetloadoptions/autofitrows) { get; set; } | 在转换时自动适配所有行。 |
| [CheckExcelRestriction](../../groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction) { get; set; } | 是否在用户修改单元格相关对象时检查 Excel 文件的限制。例如，Excel 不允许输入超过 32K 的字符串值。当您输入的值超过 32K 时，如果此属性为 true，您将收到异常；如果此属性为 false，我们将接受您输入的字符串值作为单元格的值，以便随后可以将完整的字符串输出为 CSV 等其他文件格式。然而，如果您设置了对 Excel 文件格式无效的此类值，后续不应将工作簿保存为 Excel 文件格式，否则生成的 Excel 文件可能会出现意外错误。 |
| [ClearBuiltInDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearbuiltindocumentproperties) { get; set; } | 从文档中移除内置的元数据属性。 |
| [ClearCustomDocumentProperties](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clearcustomdocumentproperties) { get; set; } | 从文档中移除自定义元数据属性。 |
| [ColumnsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/columnsperpage) { get; set; } | 按列将工作表拆分为页面。默认值为 0，不进行分页。 |
| [ConvertOwned](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowned) { get; set; } | 实现 [`ConvertOwned`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowned) 默认值为 false |
| [ConvertOwner](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertowner) { get; set; } | 实现 [`ConvertOwner`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/convertowner) 默认值为 true |
| [ConvertRange](../../groupdocs.conversion.options.load/spreadsheetloadoptions/convertrange) { get; set; } | Convert specific range when converting to other than spreadsheet format. Example: "D1:F8"。 |
| [CultureInfo](../../groupdocs.conversion.options.load/spreadsheetloadoptions/cultureinfo) { get; set; } | 获取或设置文件加载时的系统区域性信息。 |
| [DefaultFont](../../groupdocs.conversion.options.load/spreadsheetloadoptions/defaultfont) { get; set; } | 电子表格文档的默认字体。如果缺少字体，将使用以下字体。 |
| [Depth](../../groupdocs.conversion.options.load/spreadsheetloadoptions/depth) { get; set; } | 实现 [`Depth`](../../groupdocs.conversion.contracts/idocumentscontainerloadoptions/depth) 默认值：1 |
| [FontSubstitutes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/fontsubstitutes) { get; set; } | 在转换电子表格文档时替换特定字体。 |
| [Format](../../groupdocs.conversion.options.load/tsvloadoptions/format) { get; } | 输入文档的文件类型。 |
| virtual [Format](../../groupdocs.conversion.options.load/loadoptions/format) { get; } | 输入文档的文件类型。 |
| [IgnoreFormulaCalculationErrors](../../groupdocs.conversion.options.load/spreadsheetloadoptions/ignoreformulacalculationerrors) { get; set; } | 指示是否忽略公式计算错误。错误可能是不支持的函数、外部链接等。默认值为 false。 |
| [MarginSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/marginsettings) { get; set; } | 页面边距设置 |
| [OnePagePerSheet](../../groupdocs.conversion.options.load/spreadsheetloadoptions/onepagepersheet) { get; set; } | 如果 OnePagePerSheet 为 true，工作表的内容将转换为 PDF 文档中的单页。默认值为 true。 |
| [OptimizePdfSize](../../groupdocs.conversion.options.load/spreadsheetloadoptions/optimizepdfsize) { get; set; } | 如果为 True 并且转换为 PDF，则转换将针对更好的文件大小而非打印质量进行优化。 |
| [Password](../../groupdocs.conversion.options.load/spreadsheetloadoptions/password) { get; set; } | 设置密码以解除受保护文档的保护。 |
| [PreserveDocumentStructure](../../groupdocs.conversion.options.load/spreadsheetloadoptions/preservedocumentstructure) { get; set; } | 确定在转换为 PDF 时是否应保留文档结构（默认值为 false）。 |
| [PrintComments](../../groupdocs.conversion.options.load/spreadsheetloadoptions/printcomments) { get; set; } | 表示在工作表中打印批注的方式。默认值为 PrintNoComments。 |
| [ResetFontFolders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/resetfontfolders) { get; set; } | 在加载文档之前重置字体文件夹。 |
| [RowsPerPage](../../groupdocs.conversion.options.load/spreadsheetloadoptions/rowsperpage) { get; set; } | 按行将工作表拆分为页面。默认值为 0，不进行分页。 |
| [SheetIndexes](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheetindexes) { get; set; } | 要转换的工作表索引列表。索引必须从零开始。 |
| [Sheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sheets) { get; set; } | 要转换的工作表名称。 |
| [ShowGridLines](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showgridlines) { get; set; } | 在转换 Excel 文件时显示网格线。 |
| [ShowHiddenSheets](../../groupdocs.conversion.options.load/spreadsheetloadoptions/showhiddensheets) { get; set; } | 在转换 Excel 文件时显示隐藏的工作表。 |
| [SizeSettings](../../groupdocs.conversion.options.load/spreadsheetloadoptions/sizesettings) { get; set; } | 页面尺寸设置 |
| [SkipEmptyRowsAndColumns](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipemptyrowsandcolumns) { get; set; } | 在转换时跳过空行和空列。默认值为 True。 |
| [SkipExternalResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipexternalresources) { get; set; } | 实现 [`SkipExternalResources`](../iresourceloadingoptions/skipexternalresources) |
| [SkipFooters](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipfooters) { get; set; } | 在转换电子表格文档时跳过页脚。默认值：false。 |
| [SkipHeaders](../../groupdocs.conversion.options.load/spreadsheetloadoptions/skipheaders) { get; set; } | 在转换电子表格文档时跳过标题。默认值：false。 |
| [WhitelistedResources](../../groupdocs.conversion.options.load/spreadsheetloadoptions/whitelistedresources) { get; set; } | 实现 [`WhitelistedResources`](../iresourceloadingoptions/whitelistedresources) |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../groupdocs.conversion.options.load/spreadsheetloadoptions/clone)() | 克隆当前实例。 |
| override [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(object) | 确定两个对象实例是否相等。 |
| virtual [Equals](../../groupdocs.conversion.contracts/valueobject/equals)(ValueObject) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/valueobject/gethashcode)() | 充当默认的哈希函数。 |

### 另见

* class [SpreadsheetLoadOptions](../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
