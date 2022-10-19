---
title: SpreadsheetFileType
second_title: GroupDocs.Conversion for .NET API 参考
description: 定义电子表格文档包括以下文件类型 Csv./spreadsheetfiletype/csv  Fods./spreadsheetfiletype/fods  Ods./spreadsheetfiletype/ods  Ots./spreadsheetfiletype/ots  Tsv./spreadsheetfiletype/tsv  Xlam./spreadsheetfiletype/xlam  Xls./spreadsheetfiletype/xls  Xlsb./spreadsheetfiletype/xlsb  Xlsm./spreadsheetfiletype/xlsm  Xlsx./spreadsheetfiletype/xlsx  Xlt./spreadsheetfiletype/xlt  Xltm./spreadsheetfiletype/xltm  Xltx./spreadsheetfiletype/xltx . 了解有关电子表格格式的更多信息这里https//wiki.fileformat.com/spreadsheet.
type: docs
weight: 930
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
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | 档案族 |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | 文件格式 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | 将当前对象与其他对象进行比较。 |
| virtual [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(Enumeration) | 确定两个对象实例是否相等。 |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | 确定两个对象实例是否相等。 |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | 用作默认哈希函数。 |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | 字符串表示 |

## 字段

| 姓名 | 描述 |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | 带有 CSV（逗号分隔值）扩展名的文件表示纯文本文件，其中包含带有逗号分隔值的数据记录。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/csv) |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF 代表数据交换格式，用于在不同应用程序之间导入/导出电子表格数据。其中包括 Microsoft Excel、OpenOffice Calc、StarCalc 等。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/dif) |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | OpenDocument 平面 XML 电子表格 |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | .numbers 扩展名的文件被归类为电子表格文件类型，这就是它们类似于 .xlsx 文件的原因；但 Numbers 文件是使用 Apple iWork Numbers 电子表格软件创建的。 了解有关此文件格式的更多信息[这里](https://docs.fileformat.com/spreadsheet/numbers) |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | 带有 ODS 扩展名的文件代表用户可编辑的 OpenDocument 电子表格文档格式。数据在 ODF 文件中存储为行和列。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/ods) |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | OpenDocument 电子表格模板 |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | OpenOffice 和 StarOffice 使用的基于 XML 的格式 |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | 制表符分隔值 (TSV) 文件格式表示用纯文本格式的制表符分隔的数据。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/tsv) |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | Xlam 文档格式 |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS 表示 Excel 二进制文件格式。此类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xls) |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB 文件格式指定 Excel 二进制文件格式，它是指定 Excel 工作簿内容的记录和结构的集合。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsb) |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM 是一种支持宏的电子表格文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsm) |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX 是 Microsoft 在 Microsoft Office 2007 中引入的众所周知的 Microsoft Excel 文档格式。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlsx) |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | 扩展名为 .XLT 的文件是使用 Microsoft Excel 创建的模板文件，Microsoft Excel 是作为 Microsoft Office 套件的一部分提供的电子表格应用程序。 Microsoft Office 97-2003 支持创建新的 XLT 文件以及打开这些文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xlt) |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | XLTM 文件扩展名表示由 Microsoft Excel 生成的文件作为启用宏的模板文件。 XLTM 文件在结构上与 XLTX 相似，只是后者不支持使用宏创建模板文件。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xltm) |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX 文件表示基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。它用于创建一个标准模板文件，该文件可用于生成 XLSX 文件，这些文件具有与 XLTX 文件中指定的相同的设置。 了解有关此文件格式的更多信息[这里](https://wiki.fileformat.com/spreadsheet/xltx) |

### 也可以看看

* class [FileType](../filetype)
* 命名空间 [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* 部件 [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Conversion.dll -->
