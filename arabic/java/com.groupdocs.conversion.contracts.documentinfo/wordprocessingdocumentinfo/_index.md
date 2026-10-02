---
title: "WordProcessingDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحتوي على بيانات تعريف مستند معالجة النصوص"
type: docs
weight: 45
url: /ar/java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

يحتوي على بيانات تعريف مستند معالجة النصوص

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getWords()](#getWords--) | يحصل على عدد الكلمات |
|
|  | [getLines()](#getLines--) | يحصل على عدد الأسطر |
|
|  | [getTitle()](#getTitle--) | يحصل على العنوان |
|
|  | [getAuthor()](#getAuthor--) | يحصل على المؤلف |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | يحصل على ما إذا كان المستند محميًا بكلمة مرور |
|
|  | [getTableOfContents()](#getTableOfContents--) | جدول المحتويات |
|
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| معالجة الكلمات | com.aspose.words.Document |  |
| isPasswordProtected | منطقي |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


يحصل على عدد الكلمات


**Returns:**
int - عدد الكلمات

### getLines() {#getLines--}
```
public int getLines()
```


يحصل على عدد الأسطر


**Returns:**
int - عدد الأسطر

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


يحصل على ما إذا كان المستند محميًا بكلمة مرور


**Returns:**
boolean - `true` إذا كان المستند محميًا بكلمة مرور

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


جدول المحتويات


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - جدول المحتويات

