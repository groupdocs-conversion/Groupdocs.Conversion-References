---
title: "CheckExcelRestriction"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "是否在用户修改单元格相关对象时检查 Excel 文件的限制。例如，Excel 不允许输入超过 32K 的字符串值。当您输入超过 32K 的值时，如果此属性为 true，您将收到异常。如果此属性为 false，我们将接受您输入的字符串值作为单元格的值，以便稍后您可以将完整的字符串值输出为其他文件格式，如 CSV。然而，如果您设置了对 Excel 文件格式无效的此类值，之后不应将工作簿保存为 Excel 文件格式。否则生成的 Excel 文件可能会出现意外错误。"
type: docs
weight: 40
url: /zh/net/groupdocs.conversion.options.load/spreadsheetloadoptions/checkexcelrestriction/
---
## SpreadsheetLoadOptions.CheckExcelRestriction property

是否在用户修改单元格相关对象时检查 Excel 文件的限制。例如，Excel 不允许输入超过 32K 的字符串值。当您输入的值超过 32K 时，如果此属性为 true，您将收到异常；如果此属性为 false，我们将接受您输入的字符串值作为单元格的值，以便随后可以将完整的字符串输出为 CSV 等其他文件格式。然而，如果您设置了对 Excel 文件格式无效的此类值，后续不应将工作簿保存为 Excel 文件格式，否则生成的 Excel 文件可能会出现意外错误。

```csharp
public bool CheckExcelRestriction { get; set; }
```

### 另见

* class [SpreadsheetLoadOptions](../../spreadsheetloadoptions)
* namespace [GroupDocs.Conversion.Options.Load](../../../groupdocs.conversion.options.load)
* assembly [GroupDocs.Conversion](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
