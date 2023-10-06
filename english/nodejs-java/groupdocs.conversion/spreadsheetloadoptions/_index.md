---
title: SpreadsheetLoadOptions
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: 
type: docs

url: /nodejs-java/groupdocs.conversion/spreadsheetloadoptions/
---

## SpreadsheetLoadOptions class

 Options for loading Spreadsheet documents.
 
| [SpreadsheetLoadOptions](spreadsheetloadoptions)() | Initializes new instance of SpreadsheetLoadOptions class. |

## Functions

| Name | Description |
| --- | --- |
| [deepClone](deepclone)() | Clones current instance. |
| [getAllColumnsInOnePagePerSheet](getallcolumnsinonepagepersheet)() | Gets AllColumnsInOnePagePerSheet property |
| [getConvertRange](getconvertrange)() | Convert specific range when converting to other than spreadsheet format. Example: "D1:F8". |
| [getCultureInfo](getcultureinfo)() | Get the system culture info at the time file is loaded |
| [getDefaultFont](getdefaultfont)() | Default font for spreadsheet document. The following font will be used if a font is missing. |
| [getFontSubstitutes](getfontsubstitutes)() | Substitute specific fonts when converting spreadsheet document. |
| [getFormat](getformat)() |  |
| [getHideComments](gethidecomments)() | Hide comments. |
| [getOnePagePerSheet](getonepagepersheet)() | If OnePagePerSheet is true the content of the sheet will be converted to one page in the PDF document. Default value is false. |
| [getOptimizePdfSize](getoptimizepdfsize)() | If True and converting to Pdf the conversion is optimized for better file size than print quality. |
| [getPassword](getpassword)() | Set password to unprotect protected document. |
| [getSheets](getsheets)() | Get sheet name to convert |
| [getShowGridLines](getshowgridlines)() | Show grid lines when converting Excel files. |
| [getShowHiddenSheets](getshowhiddensheets)() | Show hidden sheets when converting Excel files. |
| [getSkipEmptyRowsAndColumns](getskipemptyrowsandcolumns)() | Skips empty rows and columns when converting. Default is True. |
| [isCheckExcelRestriction](ischeckexcelrestriction)() | Whether check restriction of excel file when user modify cells related objects. For example, excel does not allow inputting string value longer than 32K. When you input a value longer than 32K, if this property is true, you will get an Exception. If this property is false, we will accept your input string value as the cell's value so that later you can output the complete string value for other file formats such as CSV. However, if you have set such kind of value that is invalid for excel file format, you should not save the workbook as excel file format later. Otherwise there may be unexpected error for the generated excel file. |
| [setAllColumnsInOnePagePerSheet](setallcolumnsinonepagepersheet)(boolean) | Sets AllColumnsInOnePagePerSheet property |
| [setCheckExcelRestriction](setcheckexcelrestriction)(boolean) |  |
| [setConvertRange](setconvertrange)(String) | Convert specific range when converting to other than spreadsheet format. Example: "D1:F8". |
| [setCultureInfo](setcultureinfo)(CultureInfo) | Set the system culture info at the time file is loaded |
| [setDefaultFont](setdefaultfont)(String) | Default font for spreadsheet document. The following font will be used if a font is missing. |
| [setFontSubstitutes](setfontsubstitutes)(java.util.List<com.groupdocs.conversion.contracts. FontSubstitute>) | Substitute specific fonts when converting spreadsheet document. |
| [setHideComments](sethidecomments)(boolean) | Hide comments. |
| [setOnePagePerSheet](setonepagepersheet)(boolean) | If OnePagePerSheet is true the content of the sheet will be converted to one page in the PDF document. Default value is false. |
| [setOptimizePdfSize](setoptimizepdfsize)(boolean) | If True and converting to Pdf the conversion is optimized for better file size than print quality. |
| [setPassword](setpassword)(String) | Set password to unprotect protected document. |
| [setSheets](setsheets)(java.util.List<java.lang.String>) | Set sheet name to convert |
| [setShowGridLines](setshowgridlines)(boolean) | Show grid lines when converting Excel files. |
| [setShowHiddenSheets](setshowhiddensheets)(boolean) | Show hidden sheets when converting Excel files. |
| [setSkipEmptyRowsAndColumns](setskipemptyrowsandcolumns)(boolean) | Skips empty rows and columns when converting. Default is True. |
