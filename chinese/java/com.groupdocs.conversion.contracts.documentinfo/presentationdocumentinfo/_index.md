---
title: "PresentationDocumentInfo"
second_title: "GroupDocs.Conversion for Java API 参考"
description: "包含演示文稿文档元数据"
type: docs
weight: 31
url: /zh/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

包含演示文稿文档元数据

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getTitle()](#getTitle--) | 获取标题 |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | 设置标题 |
|
|  | [getAuthor()](#getAuthor--) | 获取作者 |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | 设置作者 |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | 获取文档是否受密码保护 |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 演示文稿 | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 大小 | long |  |
| isPasswordProtected | 布尔 |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


获取标题


**Returns:**
java.lang.String - 标题

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


设置标题


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | title | java.lang.String | title |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


获取作者


**Returns:**
java.lang.String - 作者

### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


设置作者


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | author | java.lang.String | author |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


获取文档是否受密码保护


**Returns:**
boolean - `true` 如果文档受密码保护

