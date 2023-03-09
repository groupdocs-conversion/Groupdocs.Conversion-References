---
title: SpreadsheetFileType
second_title: GroupDocs.Conversion for .NET API 参考
description: 定义电子表格文档包括以下文件类型 Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . 了解有关电子表格格式的更多信息这里https//wiki.fileformat.com/spreadsheet.
type: docs
weight: 1050
url: /zh/net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

定义电子表格文档。包括以下文件类型： [`Csv`](./csv) , [`Fods`](./fods) , [`Ods`](./ods) , [`Ots`](./ots) , [`Tsv`](./tsv) , [`Xlam`](./xlam) , [`Xls`](./xls) , [`Xlsb`](./xlsb) , [`Xlsm`](./xlsm) , [`Xlsx`](./xlsx) , [`Xlt`](./xlt) , [`Xltm`](./xltm) , [`Xltx`](./xltx) . 了解有关电子表格格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | 序列化构造函数 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | 文件类型描述 |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | 文件扩展名 |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 文件 family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 文件格式 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | 判断两个对象实例是否相等。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 判断两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 作为默认哈希函数。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 字符串表示形式 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | 具有 CSV（逗号分隔值）扩展名的文件表示包含具有逗号分隔值的数据记录的纯文本文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/csv) |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF 代表数据交换格式，用于在不同应用程序之间导入/导出电子表格数据。其中包括 Microsoft Excel、OpenOffice Calc、StarCalc 等。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/dif) |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | 扩展名为 .fods 的文件是一种 OpenDocument 电子表格文档格式，它以行和列的形式存储数据。该格式被指定为 OASIS 发布和维护的 ODF 1.2 规范的一部分。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/fods) |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | 扩展名为.numbers 的文件属于电子表格文件类型，这就是它们与.xlsx 文件相似的原因；但 Numbers 文件是使用 Apple iWork Numbers 电子表格软件创建的。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/numbers) |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | 带有 ODS 扩展名的文件代表用户可编辑的 OpenDocument 电子表格文档格式。数据以行和列的形式存储在 ODF 文件中。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/ods) |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | 扩展名为 .ots 的文件是一个 OpenDocument 电子表格模板文件，它是使用 Apache OpenOffice 中包含的 Calc 应用程序软件创建的。 Calc 应用软件类似于 Microsoft Office 中提供的 Excel。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/ots) |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | 文件格式 SXC（Sun XML Calc）属于名为 OpenOffice.org 的办公套件。这种格式通常处理用户的电子表格需求，因为它是一种基于 XML 的电子表格文件格式。 SXC 格式支持公式、函数、宏和图表以及 DataPilot。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/sxc) |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | 制表符分隔值 (TSV) 文件格式表示以纯文本格式的制表符分隔的数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/tsv) |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM 是一个启用宏的加载项文件，用于向电子表格添加新功能。加载项是一种补充程序，它运行附加代码并为电子表格提供附加功能。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/xlam/) |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS 表示 Excel 二进制文件格式。此类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（例如 OpenOffice Calc 或 Apple Numbers）创建。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB 文件格式指定 Excel 二进制文件格式，它是指定 Excel 工作簿内容的记录和结构的集合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsb) |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM 是一种支持宏的电子表格文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsm) |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX 是 Microsoft 在发布 Microsoft Office 2007 时引入的众所周知的 Microsoft Excel 文档格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsx) |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | 扩展名为 .XLT 的文件是使用 Microsoft Excel 创建的模板文件，Microsoft Excel 是一种电子表格应用程序，是 Microsoft Office 套件的一部分。 Microsoft Office 97-2003 支持创建新的 XLT 文件以及打开这些文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlt) |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM 文件扩展名表示由 Microsoft Excel 作为启用宏的模板文件生成的文件。 XLTM 文件在结构上类似于 XLTX，只是后者不支持使用宏创建模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xltm) |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX 文件表示基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。它用于创建标准模板文件，该文件可用于生成 XLSX 文件，这些文件显示与 XLTX 文件中指定的设置相同的设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xltx) |

### 也可以看看

* class [FileType](../filetype)
* 命名空间 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 部件 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
