---
title: "SpreadsheetDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "包含电子表格文档元数据"
type: docs
weight: 36
url: /zh/java/com.groupdocs.conversion.contracts.documentinfo/spreadsheetdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class SpreadsheetDocumentInfo extends DocumentInfo
```

包含电子表格文档元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)](#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getTitle()](#getTitle--) | 获取标题 |
|
|  | [getWorksheetsCount()](#getWorksheetsCount--) | 获取工作表数量 |
|
|  | [getAuthor()](#getAuthor--) | 获取作者 |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | 获取文档是否受密码保护 |
|
|  | [getWorksheets()](#getWorksheets--) | 工作表名称 |
|
| [setWorksheets(List<String> worksheets)](#setWorksheets-java.util.List-java.lang.String--) |  |
### SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size) {#SpreadsheetDocumentInfo-com.aspose.cells.Workbook-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public SpreadsheetDocumentInfo(Workbook spreadsheet, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| spreadsheet | com.aspose.cells.Workbook |  |
| isPasswordProtected | 布尔 |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 大小 | long |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


获取标题


**Returns:**
java.lang.String - 标题

### getWorksheetsCount() {#getWorksheetsCount--}
```
public int getWorksheetsCount()
```


获取工作表数量


**Returns:**
int - 工作表数量

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


获取作者


**Returns:**
java.lang.String - 作者

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


获取文档是否受密码保护


**Returns:**
boolean - 如果文档受密码保护则为 true

### getWorksheets() {#getWorksheets--}
```
public List<String> getWorksheets()
```


工作表名称


**Returns:**
java.util.List<java.lang.String>
### setWorksheets(List<String> worksheets) {#setWorksheets-java.util.List-java.lang.String--}
```
public void setWorksheets(List<String> worksheets)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| worksheets | java.util.List<java.lang.String> |  |

