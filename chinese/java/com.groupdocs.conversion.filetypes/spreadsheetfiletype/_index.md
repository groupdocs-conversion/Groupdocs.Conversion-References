---
title: "SpreadsheetFileType"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "定义电子表格文档。"
type: docs
weight: 25
url: /zh/java/com.groupdocs.conversion.filetypes/spreadsheetfiletype/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.Enumeration](../../com.groupdocs.conversion.contracts/enumeration), [com.groupdocs.conversion.filetypes.FileType](../../com.groupdocs.conversion.filetypes/filetype)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class SpreadsheetFileType extends FileType implements Serializable
```

定义电子表格文档。包括以下文件类型：
[Csv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Csv),
[Fods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Fods),
[Ods](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ods),
[Ots](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Ots),
[Tsv](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Tsv),
[Xlam](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlam),
[Xls](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xls),
[Xlsb](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsb),
[Xlsm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsm),
[Xlsx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlsx),
[Xlt](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xlt),
[Xltm](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltm),
[Xltx](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype#Xltx).
了解更多关于电子表格格式的信息，请点击[此处](../https://wiki.fileformat.com/spreadsheet)。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetFileType()](#SpreadsheetFileType--) | 序列化构造函数 |
|
## 字段

| 字段 | 描述 |
| --- | --- |
|  | [Xls](#Xls) | XLS 表示 Excel 二进制文件格式。 |
|
|  | [Xlsx](#Xlsx) | XLSX 是一种广为人知的 Microsoft Excel 文档格式，首次随 Microsoft Office 2007 发布而推出。 |
|
|  | [Xlsm](#Xlsm) | XLSM 是一种支持宏的电子表格文件类型。 |
|
|  | [Xlsb](#Xlsb) | XLSB 文件格式指定 Excel 二进制文件格式，它是一组记录和结构的集合，用于定义 Excel 工作簿的内容。 |
|
|  | [Ods](#Ods) | 扩展名为 ODS 的文件代表可由用户编辑的 OpenDocument 电子表格文档格式。 |
|
|  | [Ots](#Ots) | 扩展名为 .ots 的文件是使用 Apache OpenOffice 中的 Calc 应用程序创建的 OpenDocument 电子表格模板文件。 |
|
|  | [Xltx](#Xltx) | XLTX 文件代表基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。 |
|
|  | [Xlt](#Xlt) | 扩展名为 .XLT 的文件是使用 Microsoft Excel 创建的模板文件，Excel 是 Microsoft Office 套件中的电子表格应用程序。 |
|
|  | [Xltm](#Xltm) | XLTM 文件扩展名表示由 Microsoft Excel 生成的宏启用模板文件。 |
|
|  | [Tsv](#Tsv) | 制表符分隔值（TSV）文件格式表示以制表符分隔的纯文本数据。 |
|
|  | [Xlam](#Xlam) | XLAM 是一种宏启用的加载项文件，用于向电子表格添加新功能。 |
|
|  | [Csv](#Csv) | 扩展名为 CSV（逗号分隔值）的文件是包含逗号分隔数据记录的纯文本文件。 |
|
|  | [Fods](#Fods) | 扩展名为 .fods 的文件是一种以行列方式存储数据的 OpenDocument 电子表格文档格式。 |
|
|  | [Dif](#Dif) | DIF 代表数据交换格式，用于在不同应用程序之间导入/导出电子表格数据。 |
|
|  | [Sxc](#Sxc) | 文件格式 SXC（Sun XML Calc）属于名为 OpenOffice.org 的办公套件。 |
|
|  | [Numbers](#Numbers) | 带有 .numbers 扩展名的文件被归类为电子表格文件类型，这就是它们与 .xlsx 文件相似的原因；但 Numbers 文件是使用 Apple iWork Numbers 电子表格软件创建的。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
| [getLoadOptions()](#getLoadOptions--) |  |
| [getConvertOptions()](#getConvertOptions--) |  |
| [getExcludedSourceTypes()](#getExcludedSourceTypes--) |  |
| [getExcludedTargetTypes()](#getExcludedTargetTypes--) |  |
### SpreadsheetFileType() {#SpreadsheetFileType--}
```
public SpreadsheetFileType()
```


序列化构造函数


### Xls {#Xls}
```
public static final SpreadsheetFileType Xls
```


XLS 代表 Excel 二进制文件格式。这类文件可以由 Microsoft Excel 以及其他类似的电子表格程序（如 OpenOffice Calc 或 Apple Numbers）创建。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/xls)。


### Xlsx {#Xlsx}
```
public static final SpreadsheetFileType Xlsx
```


XLSX 是一种广为人知的 Microsoft Excel 文档格式，首次随 Microsoft Office 2007 发布而推出。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/xlsx)。


### Xlsm {#Xlsm}
```
public static final SpreadsheetFileType Xlsm
```


XLSM 是一种支持宏的电子表格文件类型。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/xlsm)。


### Xlsb {#Xlsb}
```
public static final SpreadsheetFileType Xlsb
```


XLSB 文件格式指定 Excel 二进制文件格式，它是一组记录和结构的集合，用于定义 Excel 工作簿的内容。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/xlsb)。


### Ods {#Ods}
```
public static final SpreadsheetFileType Ods
```


带有 ODS 扩展名的文件代表可由用户编辑的 OpenDocument 电子表格文档格式。数据以行列的形式存储在 ODF 文件中。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/ods)。


### Ots {#Ots}
```
public static final SpreadsheetFileType Ots
```


带有 .ots 扩展名的文件是使用 Apache OpenOffice 中包含的 Calc 应用软件创建的 OpenDocument 电子表格模板文件。Calc 应用软件类似于 Microsoft Office 中的 Excel。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/ots)。


### Xltx {#Xltx}
```
public static final SpreadsheetFileType Xltx
```


XLTX 文件代表基于 Office OpenXML 文件格式规范的 Microsoft Excel 模板。它用于创建标准模板文件，可用于生成具有 XLTX 文件中指定相同设置的 XLSX 文件。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/xltx)。


### Xlt {#Xlt}
```
public static final SpreadsheetFileType Xlt
```


带有 .XLT 扩展名的文件是使用 Microsoft Excel 创建的模板文件，Excel 是 Microsoft Office 套件的一部分。Microsoft Office 97-2003 支持创建和打开新的 XLT 文件。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/xlt)。


### Xltm {#Xltm}
```
public static final SpreadsheetFileType Xltm
```


XLTM 文件扩展名表示由 Microsoft Excel 生成的宏启用模板文件。XLTM 文件在结构上类似于 XLTX，唯一的区别是后者不支持创建带宏的模板文件。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/xltm)。


### Tsv {#Tsv}
```
public static final SpreadsheetFileType Tsv
```


制表符分隔值（TSV）文件格式表示以制表符分隔的纯文本数据。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/tsv)。


### Xlam {#Xlam}
```
public static final SpreadsheetFileType Xlam
```


XLAM 是一种宏启用的插件文件，用于向电子表格添加新功能。插件是一种补充程序，可运行额外代码并为电子表格提供额外功能。
了解更多关于此文件格式的信息 [这里](../https://docs.fileformat.com/spreadsheet/xlam/)


### Csv {#Csv}
```
public static final SpreadsheetFileType Csv
```


扩展名为 CSV（逗号分隔值）的文件是包含逗号分隔数据记录的纯文本文件。
了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/csv)。


### Fods {#Fods}
```
public static final SpreadsheetFileType Fods
```


带有 .fods 扩展名的文件是一种以行列存储数据的 OpenDocument 电子表格文档格式。该格式是 OASIS 发布和维护的 ODF 1.2 规范的一部分。了解更多关于此文件格式的信息 [这里](../https://wiki.fileformat.com/spreadsheet/fods)。


### Dif {#Dif}
```
public static final SpreadsheetFileType Dif
```


DIF 代表 Data Interchange Format，用于在不同应用程序之间导入/导出电子表格数据。这些包括 Microsoft Excel、OpenOffice Calc、StarCalc 等许多其他软件。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/spreadsheet/dif)。


### Sxc {#Sxc}
```
public static final SpreadsheetFileType Sxc
```


SXC（Sun XML Calc）文件格式属于名为 OpenOffice.org 的办公套件。该格式主要满足用户的电子表格需求，因为它是基于 XML 的电子表格文件格式。SXC 格式支持公式、函数、宏和图表以及 DataPilot。了解更多关于此文件格式的信息，请点击[此处](../https://wiki.fileformat.com/spreadsheet/sxc)。


### Numbers {#Numbers}
```
public static final SpreadsheetFileType Numbers
```


带有 .numbers 扩展名的文件被归类为电子表格文件类型，这就是它们类似于 .xlsx 文件的原因；但 Numbers 文件是使用 Apple iWork Numbers 电子表格软件创建的。了解更多关于此文件格式的信息，请点击[此处](../https://docs.fileformat.com/spreadsheet/numbers)。


### getLoadOptions() {#getLoadOptions--}
```
public LoadOptions getLoadOptions()
```


为源文件类型准备了默认加载选项


**Returns:**
[LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)
### getConvertOptions() {#getConvertOptions--}
```
public ConvertOptions getConvertOptions()
```


为文件类型准备了默认转换选项


**Returns:**
[ConvertOptions](../../com.groupdocs.conversion.options.convert/convertoptions)
### getExcludedSourceTypes() {#getExcludedSourceTypes--}
```
public static final FileType[] getExcludedSourceTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
### getExcludedTargetTypes() {#getExcludedTargetTypes--}
```
public static final FileType[] getExcludedTargetTypes()
```




**Returns:**
com.groupdocs.conversion.filetypes.FileType[]
