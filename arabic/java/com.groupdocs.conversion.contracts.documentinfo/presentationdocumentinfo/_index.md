---
title: "PresentationDocumentInfo"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يحتوي على بيانات تعريف مستند العرض التقديمي"
type: docs
weight: 31
url: /ar/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

يحتوي على بيانات تعريف مستند العرض التقديمي

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getTitle()](#getTitle--) | يحصل على العنوان |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | يضبط العنوان |
|
|  | [getAuthor()](#getAuthor--) | يحصل على المؤلف |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | يضبط المؤلف |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | يحصل على ما إذا كان المستند محميًا بكلمة مرور |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| عرض تقديمي | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |
| isPasswordProtected | منطقي |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


يحصل على العنوان


**Returns:**
java.lang.String - العنوان

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


يضبط العنوان


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | العنوان | java.lang.String | العنوان |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


يحصل على المؤلف


**Returns:**
java.lang.String - المؤلف

### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


يضبط المؤلف


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | المؤلف | java.lang.String | المؤلف |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


يحصل على ما إذا كان المستند محميًا بكلمة مرور


**Returns:**
boolean - `true` إذا كان المستند محميًا بكلمة مرور

