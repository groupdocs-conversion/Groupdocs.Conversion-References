---
title: SpreadsheetFileType
second_title: GroupDocs.Conversion for .NET API Reference
description: Defines Spreadsheet documents. Includes the following file types Csv./spreadsheetfiletype/csv Fods./spreadsheetfiletype/fods Ods./spreadsheetfiletype/ods Ots./spreadsheetfiletype/ots Tsv./spreadsheetfiletype/tsv Xlam./spreadsheetfiletype/xlam Xls./spreadsheetfiletype/xls Xlsb./spreadsheetfiletype/xlsb Xlsm./spreadsheetfiletype/xlsm Xlsx./spreadsheetfiletype/xlsx Xlt./spreadsheetfiletype/xlt Xltm./spreadsheetfiletype/xltm Xltx./spreadsheetfiletype/xltx. Learn more about Spreadsheet formats herehttps//wiki.fileformat.com/spreadsheet.
type: docs
weight: 1020
url: /net/groupdocs.conversion.filetypes/spreadsheetfiletype/
---
## SpreadsheetFileType class

Defines Spreadsheet documents. Includes the following file types: [`Csv`](./csv), [`Fods`](./fods), [`Ods`](./ods), [`Ots`](./ots), [`Tsv`](./tsv), [`Xlam`](./xlam), [`Xls`](./xls), [`Xlsb`](./xlsb), [`Xlsm`](./xlsm), [`Xlsx`](./xlsx), [`Xlt`](./xlt), [`Xltm`](./xltm), [`Xltx`](./xltx). Learn more about Spreadsheet formats [here](https://wiki.fileformat.com/spreadsheet).

```csharp
public sealed class SpreadsheetFileType : FileType
```

## Constructors

| Name | Description |
| --- | --- |
| [SpreadsheetFileType](spreadsheetfiletype)() | Serialization constructor |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../groupdocs.conversion.filetypes/filetype/description) { get; } | File type description |
| [Extension](../../groupdocs.conversion.filetypes/filetype/extension) { get; } | The file extension |
| [Family](../../groupdocs.conversion.filetypes/filetype/family) { get; } | The file family |
| [FileFormat](../../groupdocs.conversion.filetypes/filetype/fileformat) { get; } | The file format |

## Methods

| Name | Description |
| --- | --- |
| [CompareTo](../../groupdocs.conversion.contracts/enumeration/compareto)(object) | Compares current object to other. |
| override [Equals](../../groupdocs.conversion.filetypes/filetype/equals)(Enumeration) | Determines whether two object instances are equal. |
| override [Equals](../../groupdocs.conversion.contracts/enumeration/equals)(object) | Determines whether two object instances are equal. |
| override [GetHashCode](../../groupdocs.conversion.contracts/enumeration/gethashcode)() | Serves as the default hash function. |
| override [ToString](../../groupdocs.conversion.filetypes/filetype/tostring)() | String representation |

## Fields

| Name | Description |
| --- | --- |
| static readonly [Csv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/csv) | Files with CSV (Comma Separated Values) extension represent plain text files that contain records of data with comma separated values. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/csv). |
| static readonly [Dif](../../groupdocs.conversion.filetypes/spreadsheetfiletype/dif) | DIF stands for Data Interchange Format that is used to import/export spreadsheets data between different applications. These include Microsoft Excel, OpenOffice Calc, StarCalc and many others. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/dif). |
| static readonly [Fods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/fods) | A file with .fods extension is a type of OpenDocument Spreadsheet document format that stores data in rows and columns. The format is specified as part of ODF 1.2 specifications published and maintained by OASIS. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/fods). |
| static readonly [Numbers](../../groupdocs.conversion.filetypes/spreadsheetfiletype/numbers) | The files with .numbers extension are classified as spreadsheet file type, that’s why they are similar to the .xlsx files; but the Numbers files are created by using Apple iWork Numbers spreadsheet software. Learn more about this file format [here](https://docs.fileformat.com/spreadsheet/numbers). |
| static readonly [Ods](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ods) | Files with ODS extension stand for OpenDocument Spreadsheet Document format that are editable by user. Data is stored inside ODF file into rows and columns. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/ods). |
| static readonly [Ots](../../groupdocs.conversion.filetypes/spreadsheetfiletype/ots) | A file with .ots extension is an OpenDocument Spreadsheet Template file that is created with the Calc application software included in Apache OpenOffice. Calc application software is the similar to Excel available in Microsoft Office. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/ots). |
| static readonly [Sxc](../../groupdocs.conversion.filetypes/spreadsheetfiletype/sxc) | The file format SXC(Sun XML Calc) belongs to an office suite called OpenOffice.org. This format generally deals with the spreadsheet needs of users as it is an XML based spreadsheet file format. SXC format supports formulas, functions, macros and charts along with DataPilot. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/sxc). |
| static readonly [Tsv](../../groupdocs.conversion.filetypes/spreadsheetfiletype/tsv) | A Tab-Separated Values (TSV) file format represents data separated with tabs in plain text format. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/tsv). |
| static readonly [Xlam](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlam) | XLAM is an Macro-Enabled Add-In file that is used to add new functions to spreadsheets. An Add-In is a supplemental program that runs additional code and provides additional functionality for spreadsheets. Learn more about this file format [here](https://docs.fileformat.com/spreadsheet/xlam/). |
| static readonly [Xls](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xls) | XLS represents Excel Binary File Format. Such files can be created by Microsoft Excel as well as other similar spreadsheet programs such as OpenOffice Calc or Apple Numbers. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xls). |
| static readonly [Xlsb](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsb) | XLSB file format specifies the Excel Binary File Format, which is a collection of records and structures that specify Excel workbook content. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlsb). |
| static readonly [Xlsm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsm) | XLSM is a type of Spreadsheet files that support macros. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlsm). |
| static readonly [Xlsx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlsx) | XLSX is well-known format for Microsoft Excel documents that was introduced by Microsoft with the release of Microsoft Office 2007. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlsx). |
| static readonly [Xlt](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xlt) | Files with .XLT extension are template files created with Microsoft Excel which is a spreadsheet application which comes as part of Microsoft Office suite. Microsoft Office 97-2003 supported creating new XLT files as well as opening these. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xlt). |
| static readonly [Xltm](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltm) | The XLTM file extension represents files that are generated by Microsoft Excel as Macro-enabled template files. XLTM files are similar to XLTX in structure other than that the later doesn't support creating template files with macros. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xltm). |
| static readonly [Xltx](../../groupdocs.conversion.filetypes/spreadsheetfiletype/xltx) | XLTX file represents Microsoft Excel Template that are based on the Office OpenXML file format specifications. It is used to create a standard template file that can be utilized to generate XLSX files that exhibit the same settings as specified in the XLTX file. Learn more about this file format [here](https://wiki.fileformat.com/spreadsheet/xltx). |

### See Also

* class [FileType](../filetype)
* namespace [GroupDocs.Conversion.FileTypes](../../groupdocs.conversion.filetypes)
* assembly [GroupDocs.Conversion](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.conversion.dll -->
