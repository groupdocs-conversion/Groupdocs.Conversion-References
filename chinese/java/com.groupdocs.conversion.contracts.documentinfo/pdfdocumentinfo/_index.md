---
title: "PdfDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "包含 PDF 文档元数据"
type: docs
weight: 28
url: /zh/java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

包含 PDF 文档元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getVersion()](#getVersion--) | 获取版本 |
|
|  | [getTitle()](#getTitle--) | 获取标题 |
|
|  | [getAuthor()](#getAuthor--) | 获取作者 |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | 获取是否已加密 |
|
|  | [isLandscape()](#isLandscape--) | 获取页面是否横向 |
|
|  | [getHeight()](#getHeight--) | 获取页面高度 |
|
|  | [getWidth()](#getWidth--) | 获取页面宽度 |
|
|  | [getTableOfContents()](#getTableOfContents--) | 获取目录 |
|
|  | [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | 设置目录 |
|
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 大小 | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


获取版本


**Returns:**
java.lang.String - 版本

### getTitle() {#getTitle--}
```
public String getTitle()
```


获取标题


**Returns:**
java.lang.String - 标题

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


获取是否已加密


**Returns:**
boolean - 如果已加密则为 true

### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


获取页面是否横向


**Returns:**
boolean - 如果页面横向则为 true

### getHeight() {#getHeight--}
```
public double getHeight()
```


获取页面高度


**Returns:**
double - 页面高度

### getWidth() {#getWidth--}
```
public double getWidth()
```


获取页面宽度


**Returns:**
double - 页面宽度

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


获取目录


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - 目录

### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


设置目录


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | 目录 |
|

