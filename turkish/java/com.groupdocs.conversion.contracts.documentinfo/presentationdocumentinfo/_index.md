---
title: "PresentationDocumentInfo"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Sunum belgesi üst verilerini içerir"
type: docs
weight: 31
url: /tr/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Sunum belgesi üst verilerini içerir

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  | [getTitle()](#getTitle--) | Başlığı alır |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | Başlığı ayarlar |
|
|  | [getAuthor()](#getAuthor--) | Yazarı alır |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | Yazarı ayarlar |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Belgenin şifre korumalı olup olduğunu alır |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sunum | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Başlığı alır


**Returns:**
java.lang.String - başlık

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Başlığı ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | başlık | java.lang.String | başlık |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Yazarı alır


**Returns:**
java.lang.String - yazar

### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Yazarı ayarlar


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | yazar | java.lang.String | yazar |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Belgenin şifre korumalı olup olduğunu alır


**Returns:**
boolean - belge şifre korumalı ise `true`

