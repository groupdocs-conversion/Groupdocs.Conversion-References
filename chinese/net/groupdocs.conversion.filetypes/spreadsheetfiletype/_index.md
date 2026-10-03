---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion for .NET API 参考"
description: "定义电子表格文档。包括以下文件类型 Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. 了解更多关于电子表格格式的信息，请访问 https//wiki.fileformat.com/spreadsheet。"
type: docs
weight: 1240
url: /zh/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

定义电子表格文档。包括以下文件类型：[`Csv`](./csv)、[`Fods`](./fods)、[`Ods`](./ods)、[`Ots`](./ots)、[`Tsv`](./tsv)、[`Xlam`](./xlam)、[`Xls`](./xls)、[`Xlsb`](./xlsb)、[`Xlsm`](./xlsm)、[`Xlsx`](./xlsx)、[`Xlt`](./xlt)、[`Xltm`](./xltm)、[`Xltx`](./xltx)。了解更多关于电子表格格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet)。

```csharp
public sealed class SpreadsheetFileType : FileType
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | 序列化构造函数 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 文件类型描述 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 文件扩展名 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 文件族 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 文件格式 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 实现 [`Equals`](../../groupdocs.conversion.contracts/enumeration/equals) |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 充当默认的哈希函数。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 字符串表示 |

## Fields

| 名称 | 描述 |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | CSV（逗号分隔值）扩展名的文件表示包含逗号分隔值的数据记录的纯文本文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/csv)。 |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF 代表数据交换格式，用于在不同应用程序之间导入/导出电子表格数据。这些应用包括 Microsoft Excel、OpenOffice Calc、StarCalc 等。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/dif)。 |
| static readonly [FlatOpc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/flatopc) | Flat OPC Excel 是以平面 XML 文件而非 ZIP 包存储的 Office Open XML SpreadsheetML。 |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | 扩展名为 .fods 的文件是一种 OpenDocument 电子表格文档格式，以行列方式存储数据。该格式是 OASIS 发布并维护的 ODF 1.2 规范的一部分。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/fods)。 |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | 扩展名为 .numbers 的文件被归类为电子表格文件类型，因此它们类似于 .xlsx 文件；但 Numbers 文件是使用 Apple iWork Numbers 电子表格软件创建的。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/spreadsheet/numbers)。 |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | 扩展名为 ODS 的文件代表可由用户编辑的 OpenDocument 电子表格文档格式。数据以行列方式存储在 ODF 文件中。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/ods)。 |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | 扩展名为 .ots 的文件是使用 Apache OpenOffice 中的 Calc 应用软件创建的 OpenDocument 电子表格模板文件。Calc 应用软件类似于 Microsoft Office 中的 Excel。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/ots)。 |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | 文件格式 SXC（Sun XML Calc）属于名为 OpenOffice.org 的办公套件。该格式主要满足用户的电子表格需求，是基于 XML 的电子表格文件格式。SXC 格式支持公式、函数、宏、图表以及 DataPilot。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/sxc)。 |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | 制表符分隔值（TSV）文件格式表示以制表符分隔的纯文本数据。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/tsv)。 |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM 是一种宏启用的加载项文件，用于向电子表格添加新函数。加载项是运行附加代码并为电子表格提供额外功能的补充程序。了解更多关于此文件格式的信息，请点击[此处](https://docs.fileformat.com/spreadsheet/xlam/)。 |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS 代表 Excel 二进制文件格式。这类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xls)。 |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB 文件格式指定 Excel 二进制文件格式，它是一组记录和结构，用于定义 Excel 工作簿的内容。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsb)。 |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM 是一种支持宏的电子表格文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsm)。 |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX 是 Microsoft Excel 文档的知名格式，随 Microsoft Office 2007 发布而推出。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlsx)。 |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | 扩展名为 .XLT 的文件是使用 Microsoft Excel 创建的模板文件，Excel 是 Microsoft Office 套件的一部分。Microsoft Office 97-2003 支持创建和打开新的 XLT 文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xlt)。 |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM 文件扩展名表示由 Microsoft Excel 生成的宏启用模板文件。XLTM 文件在结构上类似于 XLTX，但后者不支持创建带宏的模板文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xltm)。 |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX 文件代表基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。它用于创建标准模板文件，可用于生成具有与 XLTX 文件中指定的相同设置的 XLSX 文件。了解更多关于此文件格式的信息，请点击[此处](https://wiki.fileformat.com/spreadsheet/xltx)。 |

### 另见

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.conversion.dll 生成 -->
