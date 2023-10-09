---
title: SpreadsheetLoadOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Options for loading Spreadsheet documents.
type: docs
weight: 31
url: /java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable
```

Options for loading Spreadsheet documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | Initializes new instance of [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getSheets()](#getSheets--) | Get sheet name to convert |
| [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | Set sheet name to convert |
| [getCultureInfo()](#getCultureInfo--) | Get the system culture info at the time file is loaded |
| [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | Set the system culture info at the time file is loaded |
| [getFormat()](#getFormat--) |  |
| [getDefaultFont()](#getDefaultFont--) | Default font for spreadsheet document. |
| [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | Default font for spreadsheet document. |
| [getFontSubstitutes()](#getFontSubstitutes--) | Substitute specific fonts when converting spreadsheet document. |
| [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | Substitute specific fonts when converting spreadsheet document. |
| [getShowGridLines()](#getShowGridLines--) | Show grid lines when converting Excel files. |
| [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | Show grid lines when converting Excel files. |
| [getShowHiddenSheets()](#getShowHiddenSheets--) | Show hidden sheets when converting Excel files. |
| [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | Show hidden sheets when converting Excel files. |
| [getOnePagePerSheet()](#getOnePagePerSheet--) | If OnePagePerSheet is true the content of the sheet will be converted to one page in the PDF document. |
| [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | If OnePagePerSheet is true the content of the sheet will be converted to one page in the PDF document. |
| [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | Gets AllColumnsInOnePagePerSheet property |
| [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | Sets AllColumnsInOnePagePerSheet property |
| [getOptimizePdfSize()](#getOptimizePdfSize--) | If True and converting to Pdf the conversion is optimized for better file size than print quality. |
| [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | If True and converting to Pdf the conversion is optimized for better file size than print quality. |
| [getConvertRange()](#getConvertRange--) | Convert specific range when converting to other than spreadsheet format. |
| [setConvertRange(String value)](#setConvertRange-java.lang.String-) | Convert specific range when converting to other than spreadsheet format. |
| [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | Skips empty rows and columns when converting. |
| [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | Skips empty rows and columns when converting. |
| [getPassword()](#getPassword--) | Set password to unprotect protected document. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Set password to unprotect protected document. |
| [getHideComments()](#getHideComments--) | Hide comments. |
| [setHideComments(boolean value)](#setHideComments-boolean-) | Hide comments. |
| [isCheckExcelRestriction()](#isCheckExcelRestriction--) | Whether check restriction of excel file when user modify cells related objects. |
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
| [getSheetIndexes()](#getSheetIndexes--) | Gets List of sheet indexes to convert. |
| [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | Sets List of sheet indexes to convert. |
| [deepClone()](#deepClone--) | Clones current instance. |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


Initializes new instance of [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) class.

### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


Get sheet name to convert

**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


Set sheet name to convert

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sheets | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


Get the system culture info at the time file is loaded

**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


Set the system culture info at the time file is loaded

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


Input document file type

**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


Default font for spreadsheet document. The following font will be used if a font is missing.

**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


Default font for spreadsheet document. The following font will be used if a font is missing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


Substitute specific fonts when converting spreadsheet document.

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


Substitute specific fonts when converting spreadsheet document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


Show grid lines when converting Excel files.

**Returns:**
boolean
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


Show grid lines when converting Excel files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


Show hidden sheets when converting Excel files.

**Returns:**
boolean
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


Show hidden sheets when converting Excel files.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


If OnePagePerSheet is true the content of the sheet will be converted to one page in the PDF document. Default value is false.

**Returns:**
boolean
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


If OnePagePerSheet is true the content of the sheet will be converted to one page in the PDF document. Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


Gets AllColumnsInOnePagePerSheet property

**Returns:**
boolean - true if fit all columns to ont page
### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


Sets AllColumnsInOnePagePerSheet property

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| allColumnsInOnePagePerSheet | boolean | AllColumnsInOnePagePerSheet property |

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


If True and converting to Pdf the conversion is optimized for better file size than print quality.

**Returns:**
boolean
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


If True and converting to Pdf the conversion is optimized for better file size than print quality.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


Convert specific range when converting to other than spreadsheet format. Example: "D1:F8".

**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


Convert specific range when converting to other than spreadsheet format. Example: "D1:F8".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


Skips empty rows and columns when converting. Default is True.

**Returns:**
boolean
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


Skips empty rows and columns when converting. Default is True.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Set password to unprotect protected document.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Set password to unprotect protected document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


Hide comments.

**Returns:**
boolean
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


Hide comments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


Whether check restriction of excel file when user modify cells related objects. For example, excel does not allow inputting string value longer than 32K. When you input a value longer than 32K, if this property is true, you will get an Exception. If this property is false, we will accept your input string value as the cell's value so that later you can output the complete string value for other file formats such as CSV. However, if you have set such kind of value that is invalid for excel file format, you should not save the workbook as excel file format later. Otherwise there may be unexpected error for the generated excel file.

**Returns:**
boolean - check restriction flag
### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| checkExcelRestriction | boolean |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


Gets List of sheet indexes to convert.

**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


Sets List of sheet indexes to convert. The indexes must be zero-based

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Clones current instance.

**Returns:**
java.lang.Object - 
