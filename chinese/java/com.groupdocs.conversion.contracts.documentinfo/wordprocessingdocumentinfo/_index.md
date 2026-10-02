---
title: "WordProcessingDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "包含文字处理文档元数据"
type: docs
weight: 45
url: /zh/java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

包含文字处理文档元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getWords()](#getWords--) | 获取单词计数 |
|
|  | [getLines()](#getLines--) | 获取行计数 |
|
|  | [getTitle()](#getTitle--) | 获取标题 |
|
|  | [getAuthor()](#getAuthor--) | 获取作者 |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | 获取文档是否受密码保护 |
|
|  | [getTableOfContents()](#getTableOfContents--) | 目录 |
|
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| wordprocessing | com.aspose.words.Document |  |
| isPasswordProtected | 布尔 |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 大小 | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


获取单词计数


**Returns:**
int - 单词计数

### getLines() {#getLines--}
```
public int getLines()
```


获取行计数


**Returns:**
int - 行计数

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


获取文档是否受密码保护


**Returns:**
boolean - `true` 如果文档受密码保护

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


目录


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - 目录

