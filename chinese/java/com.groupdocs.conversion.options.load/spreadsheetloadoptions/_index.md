---
title: "SpreadsheetLoadOptions"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "加载电子表格文档的选项。"
type: docs
weight: 31
url: /zh/java/com.groupdocs.conversion.options.load/spreadsheetloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable, [com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class SpreadsheetLoadOptions extends LoadOptions implements Cloneable, Serializable, IDocumentsContainerLoadOptions
```

加载电子表格文档的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [SpreadsheetLoadOptions()](#SpreadsheetLoadOptions--) | 初始化 [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSheets()](#getSheets--) | 获取要转换的工作表名称 |
|
|  | [setSheets(List<String> sheets)](#setSheets-java.util.List-java.lang.String--) | 设置要转换的工作表名称 |
|
|  | [getCultureInfo()](#getCultureInfo--) | 获取文件加载时的系统区域性信息 |
|
|  | [setCultureInfo(System.Globalization.CultureInfo cultureInfo)](#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-) | 设置文件加载时的系统区域性信息 |
|
| [getFormat()](#getFormat--) |  |
|  | [getDefaultFont()](#getDefaultFont--) | 电子表格文档的默认字体。 |
|
|  | [setDefaultFont(String value)](#setDefaultFont-java.lang.String-) | 电子表格文档的默认字体。 |
|
|  | [getFontSubstitutes()](#getFontSubstitutes--) | 在转换电子表格文档时替换特定字体。 |
|
|  | [setFontSubstitutes(List<FontSubstitute> value)](#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--) | 在转换电子表格文档时替换特定字体。 |
|
|  | [getShowGridLines()](#getShowGridLines--) | 在转换 Excel 文件时显示网格线。 |
|
|  | [setShowGridLines(boolean value)](#setShowGridLines-boolean-) | 在转换 Excel 文件时显示网格线。 |
|
|  | [getShowHiddenSheets()](#getShowHiddenSheets--) | 在转换 Excel 文件时显示隐藏的工作表。 |
|
|  | [setShowHiddenSheets(boolean value)](#setShowHiddenSheets-boolean-) | 在转换 Excel 文件时显示隐藏的工作表。 |
|
|  | [getOnePagePerSheet()](#getOnePagePerSheet--) | 如果 OnePagePerSheet 为 true，工作表的内容将转换为 PDF 文档中的单页。 |
|
|  | [setOnePagePerSheet(boolean value)](#setOnePagePerSheet-boolean-) | 如果 OnePagePerSheet 为 true，工作表的内容将转换为 PDF 文档中的单页。 |
|
|  | [getAllColumnsInOnePagePerSheet()](#getAllColumnsInOnePagePerSheet--) | 获取 AllColumnsInOnePagePerSheet 属性 |
|
|  | [setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)](#setAllColumnsInOnePagePerSheet-boolean-) | 设置 AllColumnsInOnePagePerSheet 属性 |
|
|  | [getOptimizePdfSize()](#getOptimizePdfSize--) | 如果为 True 且转换为 PDF，转换将针对更小的文件大小而非打印质量进行优化。 |
|
|  | [setOptimizePdfSize(boolean value)](#setOptimizePdfSize-boolean-) | 如果为 True 且转换为 PDF，转换将针对更小的文件大小而非打印质量进行优化。 |
|
|  | [getConvertRange()](#getConvertRange--) | 在转换为非电子表格格式时转换特定范围。 |
|
|  | [setConvertRange(String value)](#setConvertRange-java.lang.String-) | 在转换为非电子表格格式时转换特定范围。 |
|
|  | [getSkipEmptyRowsAndColumns()](#getSkipEmptyRowsAndColumns--) | 转换时跳过空行和空列。 |
|
|  | [setSkipEmptyRowsAndColumns(boolean value)](#setSkipEmptyRowsAndColumns-boolean-) | 转换时跳过空行和空列。 |
|
|  | [getPassword()](#getPassword--) | 设置密码以解除受保护文档的保护。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 设置密码以解除受保护文档的保护。 |
|
|  | [getHideComments()](#getHideComments--) | 隐藏批注。 |
|
|  | [setHideComments(boolean value)](#setHideComments-boolean-) | 隐藏批注。 |
|
|  | [isCheckExcelRestriction()](#isCheckExcelRestriction--) | 是否在用户修改单元格相关对象时检查 Excel 文件的限制。 |
|
| [setCheckExcelRestriction(boolean checkExcelRestriction)](#setCheckExcelRestriction-boolean-) |  |
|  | [getSheetIndexes()](#getSheetIndexes--) | 获取要转换的工作表索引列表。 |
|
|  | [setSheetIndexes(List<Integer> sheetIndexes)](#setSheetIndexes-java.util.List-java.lang.Integer--) | 设置要转换的工作表索引列表。 |
|
|  | [isAutoFitRows()](#isAutoFitRows--) | 转换时自动适配所有行。 |
|
| [setAutoFitRows(boolean autoFitRows)](#setAutoFitRows-boolean-) |  |
|  | [getResetFontFolders()](#getResetFontFolders--) | 在加载文档之前重置字体文件夹 |
|
| [setResetFontFolders(boolean resetFontFolders)](#setResetFontFolders-boolean-) |  |
|  | [deepClone()](#deepClone--) | 克隆当前实例。 |
|
|  | [getRowsPerPage()](#getRowsPerPage--) | 按行将工作表拆分为页面。 |
|
|  | [setRowsPerPage(int rowsPerPage)](#setRowsPerPage-int-) | 按行将工作表拆分为页面。 |
|
|  | [getColumnsPerPage()](#getColumnsPerPage--) | 按列将工作表拆分为页面。 |
|
|  | [setColumnsPerPage(int columnsPerPage)](#setColumnsPerPage-int-) | 按列将工作表拆分为页面。 |
|
| [isConvertOwner()](#isConvertOwner--) |  |
| [setConvertOwner(boolean convertOwner)](#setConvertOwner-boolean-) |  |
| [isConvertOwned()](#isConvertOwned--) |  |
| [setConvertOwned(boolean convertOwned)](#setConvertOwned-boolean-) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
### SpreadsheetLoadOptions() {#SpreadsheetLoadOptions--}
```
public SpreadsheetLoadOptions()
```


初始化 [SpreadsheetLoadOptions](../../com.groupdocs.conversion.options.load/spreadsheetloadoptions) 类的新实例。


### getSheets() {#getSheets--}
```
public List<String> getSheets()
```


获取要转换的工作表名称


**Returns:**
java.util.List<java.lang.String>
### setSheets(List<String> sheets) {#setSheets-java.util.List-java.lang.String--}
```
public void setSheets(List<String> sheets)
```


设置要转换的工作表名称


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 工作表 | java.util.List<java.lang.String> |  |

### getCultureInfo() {#getCultureInfo--}
```
public System.Globalization.CultureInfo getCultureInfo()
```


获取文件加载时的系统区域性信息


**Returns:**
com.aspose.ms.System.Globalization.CultureInfo
### setCultureInfo(System.Globalization.CultureInfo cultureInfo) {#setCultureInfo-com.aspose.ms.System.Globalization.CultureInfo-}
```
public void setCultureInfo(System.Globalization.CultureInfo cultureInfo)
```


设置文件加载时的系统区域性信息


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cultureInfo | com.aspose.ms.System.Globalization.CultureInfo |  |

### getFormat() {#getFormat--}
```
public final SpreadsheetFileType getFormat()
```


输入文档文件类型


**Returns:**
[SpreadsheetFileType](../../com.groupdocs.conversion.filetypes/spreadsheetfiletype)
### getDefaultFont() {#getDefaultFont--}
```
public final String getDefaultFont()
```


电子表格文档的默认字体。如果缺少字体，将使用以下字体。


**Returns:**
java.lang.String
### setDefaultFont(String value) {#setDefaultFont-java.lang.String-}
```
public final void setDefaultFont(String value)
```


电子表格文档的默认字体。如果缺少字体，将使用以下字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFontSubstitutes() {#getFontSubstitutes--}
```
public final List<FontSubstitute> getFontSubstitutes()
```


在转换电子表格文档时替换特定字体。


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.FontSubstitute>
### setFontSubstitutes(List<FontSubstitute> value) {#setFontSubstitutes-java.util.List-com.groupdocs.conversion.contracts.FontSubstitute--}
```
public final void setFontSubstitutes(List<FontSubstitute> value)
```


在转换电子表格文档时替换特定字体。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.List<com.groupdocs.conversion.contracts.FontSubstitute> |  |

### getShowGridLines() {#getShowGridLines--}
```
public final boolean getShowGridLines()
```


在转换 Excel 文件时显示网格线。


**Returns:**
布尔
### setShowGridLines(boolean value) {#setShowGridLines-boolean-}
```
public final void setShowGridLines(boolean value)
```


在转换 Excel 文件时显示网格线。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getShowHiddenSheets() {#getShowHiddenSheets--}
```
public final boolean getShowHiddenSheets()
```


在转换 Excel 文件时显示隐藏的工作表。


**Returns:**
布尔
### setShowHiddenSheets(boolean value) {#setShowHiddenSheets-boolean-}
```
public final void setShowHiddenSheets(boolean value)
```


在转换 Excel 文件时显示隐藏的工作表。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getOnePagePerSheet() {#getOnePagePerSheet--}
```
public final boolean getOnePagePerSheet()
```


如果 OnePagePerSheet 为 true，工作表的内容将转换为 PDF 文档中的单页。默认值为 false。


**Returns:**
布尔
### setOnePagePerSheet(boolean value) {#setOnePagePerSheet-boolean-}
```
public final void setOnePagePerSheet(boolean value)
```


如果 OnePagePerSheet 为 true，工作表的内容将转换为 PDF 文档中的单页。默认值为 false。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getAllColumnsInOnePagePerSheet() {#getAllColumnsInOnePagePerSheet--}
```
public boolean getAllColumnsInOnePagePerSheet()
```


获取 AllColumnsInOnePagePerSheet 属性


**Returns:**
boolean - 如果所有列适配到一页则为 true

### setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet) {#setAllColumnsInOnePagePerSheet-boolean-}
```
public void setAllColumnsInOnePagePerSheet(boolean allColumnsInOnePagePerSheet)
```


设置 AllColumnsInOnePagePerSheet 属性


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | allColumnsInOnePagePerSheet | 布尔 | AllColumnsInOnePagePerSheet 属性 |
|

### getOptimizePdfSize() {#getOptimizePdfSize--}
```
public final boolean getOptimizePdfSize()
```


如果为 True 且转换为 PDF，转换将针对更小的文件大小而非打印质量进行优化。


**Returns:**
布尔
### setOptimizePdfSize(boolean value) {#setOptimizePdfSize-boolean-}
```
public final void setOptimizePdfSize(boolean value)
```


如果为 True 且转换为 PDF，转换将针对更小的文件大小而非打印质量进行优化。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getConvertRange() {#getConvertRange--}
```
public final String getConvertRange()
```


在转换为非电子表格格式时转换特定范围。例如："D1:F8"。


**Returns:**
java.lang.String
### setConvertRange(String value) {#setConvertRange-java.lang.String-}
```
public final void setConvertRange(String value)
```


在转换为非电子表格格式时转换特定范围。例如："D1:F8"。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSkipEmptyRowsAndColumns() {#getSkipEmptyRowsAndColumns--}
```
public final boolean getSkipEmptyRowsAndColumns()
```


在转换时跳过空行和空列。默认值为 True。


**Returns:**
布尔
### setSkipEmptyRowsAndColumns(boolean value) {#setSkipEmptyRowsAndColumns-boolean-}
```
public final void setSkipEmptyRowsAndColumns(boolean value)
```


在转换时跳过空行和空列。默认值为 True。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


设置密码以解除受保护文档的保护。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


设置密码以解除受保护文档的保护。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getHideComments() {#getHideComments--}
```
public final boolean getHideComments()
```


隐藏批注。


**Returns:**
布尔
### setHideComments(boolean value) {#setHideComments-boolean-}
```
public final void setHideComments(boolean value)
```


隐藏批注。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | 布尔 |  |

### isCheckExcelRestriction() {#isCheckExcelRestriction--}
```
public boolean isCheckExcelRestriction()
```


是否在用户修改单元格相关对象时检查 Excel 文件的限制。例如，Excel 不允许输入超过 32K 的字符串值。当您输入的值超过 32K 时，如果此属性为 true，您将收到一个 Exception。如果此属性为 false，我们将接受您的输入字符串作为单元格的值，以便稍后您可以将完整的字符串值输出为其他文件格式，如 CSV。然而，如果您设置了对 Excel 文件格式无效的此类值，之后不应将工作簿保存为 Excel 文件格式。否则生成的 Excel 文件可能会出现意外错误。


**Returns:**
布尔型 - 检查限制标志

### setCheckExcelRestriction(boolean checkExcelRestriction) {#setCheckExcelRestriction-boolean-}
```
public void setCheckExcelRestriction(boolean checkExcelRestriction)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| checkExcelRestriction | 布尔 |  |

### getSheetIndexes() {#getSheetIndexes--}
```
public List<Integer> getSheetIndexes()
```


获取要转换的工作表索引列表。


**Returns:**
java.util.List<java.lang.Integer>
### setSheetIndexes(List<Integer> sheetIndexes) {#setSheetIndexes-java.util.List-java.lang.Integer--}
```
public void setSheetIndexes(List<Integer> sheetIndexes)
```


设置要转换的工作表索引列表。索引必须从零开始。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sheetIndexes | java.util.List<java.lang.Integer> |  |

### isAutoFitRows() {#isAutoFitRows--}
```
public boolean isAutoFitRows()
```


转换时自动适配所有行。


**Returns:**
布尔
### setAutoFitRows(boolean autoFitRows) {#setAutoFitRows-boolean-}
```
public void setAutoFitRows(boolean autoFitRows)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| autoFitRows | 布尔 |  |

### getResetFontFolders() {#getResetFontFolders--}
```
public boolean getResetFontFolders()
```


在加载文档之前重置字体文件夹


**Returns:**
布尔
### setResetFontFolders(boolean resetFontFolders) {#setResetFontFolders-boolean-}
```
public void setResetFontFolders(boolean resetFontFolders)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resetFontFolders | 布尔 |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


克隆当前实例。


**Returns:**
java.lang.Object -
### getRowsPerPage() {#getRowsPerPage--}
```
public int getRowsPerPage()
```


按行将工作表拆分为页面。默认值为 0，表示不分页。


**Returns:**
int
### setRowsPerPage(int rowsPerPage) {#setRowsPerPage-int-}
```
public void setRowsPerPage(int rowsPerPage)
```


按行将工作表拆分为页面。默认值为 0，表示不分页。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowsPerPage | int |  |

### getColumnsPerPage() {#getColumnsPerPage--}
```
public int getColumnsPerPage()
```


按列将工作表拆分为页面。默认值为 0，表示不分页。


**Returns:**
int
### setColumnsPerPage(int columnsPerPage) {#setColumnsPerPage-int-}
```
public void setColumnsPerPage(int columnsPerPage)
```


按列将工作表拆分为页面。默认值为 0，表示不分页。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnsPerPage | int |  |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


获取选项以控制文档容器本身是否必须转换


**Returns:**
布尔
### setConvertOwner(boolean convertOwner) {#setConvertOwner-boolean-}
```
public void setConvertOwner(boolean convertOwner)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOwner | 布尔 |  |

### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


选项，用于控制文档容器中的所属文档是否必须转换


**Returns:**
布尔
### setConvertOwned(boolean convertOwned) {#setConvertOwned-boolean-}
```
public void setConvertOwned(boolean convertOwned)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| convertOwned | 布尔 |  |

### getDepth() {#getDepth--}
```
public int getDepth()
```


选项，用于控制转换的深度层级数


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| depth | int |  |

