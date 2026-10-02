---
title: "PdfDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحتوي على بيانات تعريف مستند Pdf"
type: docs
weight: 28
url: /ar/java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

يحتوي على بيانات تعريف مستند Pdf

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getVersion()](#getVersion--) | يحصل على الإصدار |
|
|  | [getTitle()](#getTitle--) | يحصل على العنوان |
|
|  | [getAuthor()](#getAuthor--) | يحصل على المؤلف |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | يسترجع ما إذا كان مشفرًا |
|
|  | [isLandscape()](#isLandscape--) | يسترجع ما إذا كانت الصفحة أفقية |
|
|  | [getHeight()](#getHeight--) | يسترجع ارتفاع الصفحة |
|
|  | [getWidth()](#getWidth--) | يسترجع عرض الصفحة |
|
|  | [getTableOfContents()](#getTableOfContents--) | يسترجع جدول المحتويات |
|
|  | [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | يضبط جدول المحتويات |
|
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


يحصل على الإصدار


**Returns:**
java.lang.String - الإصدار

### getTitle() {#getTitle--}
```
public String getTitle()
```


يحصل على العنوان


**Returns:**
java.lang.String - العنوان

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


يحصل على المؤلف


**Returns:**
java.lang.String - المؤلف

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


يسترجع ما إذا كان مشفرًا


**Returns:**
boolean - صحيح إذا كان مشفرًا

### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


يسترجع ما إذا كانت الصفحة أفقية


**Returns:**
boolean - صحيح إذا كانت الصفحة أفقية

### getHeight() {#getHeight--}
```
public double getHeight()
```


يسترجع ارتفاع الصفحة


**Returns:**
double - ارتفاع الصفحة

### getWidth() {#getWidth--}
```
public double getWidth()
```


يسترجع عرض الصفحة


**Returns:**
double - عرض الصفحة

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


يسترجع جدول المحتويات


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - جدول المحتويات

### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


يضبط جدول المحتويات


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | جدول المحتويات |
|

