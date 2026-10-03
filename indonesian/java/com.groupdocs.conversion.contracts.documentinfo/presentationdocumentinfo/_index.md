---
title: "PresentationDocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Berisi metadata dokumen Presentasi"
type: docs
weight: 31
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/presentationdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PresentationDocumentInfo extends DocumentInfo
```

Berisi metadata dokumen Presentasi

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)](#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getTitle()](#getTitle--) | Mendapatkan judul |
|
|  | [setTitle(String title)](#setTitle-java.lang.String-) | Mengatur judul |
|
|  | [getAuthor()](#getAuthor--) | Mendapatkan penulis |
|
|  | [setAuthor(String author)](#setAuthor-java.lang.String-) | Mengatur penulis |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Mendapatkan apakah dokumen dilindungi kata sandi |
|
### PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected) {#PresentationDocumentInfo-com.aspose.slides.Presentation-com.groupdocs.conversion.filetypes.FileType-long-boolean-}
```
public PresentationDocumentInfo(Presentation presentation, FileType format, long size, boolean isPasswordProtected)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| presentasi | com.aspose.slides.Presentation |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |
| isPasswordProtected | boolean |  |

### getTitle() {#getTitle--}
```
public String getTitle()
```


Mendapatkan judul


**Returns:**
java.lang.String - judul

### setTitle(String title) {#setTitle-java.lang.String-}
```
public void setTitle(String title)
```


Mengatur judul


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | judul | java.lang.String | judul |
|

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Mendapatkan penulis


**Returns:**
java.lang.String - penulis

### setAuthor(String author) {#setAuthor-java.lang.String-}
```
public void setAuthor(String author)
```


Mengatur penulis


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | penulis | java.lang.String | penulis |
|

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Mendapatkan apakah dokumen dilindungi kata sandi


**Returns:**
boolean - `true` jika dokumen dilindungi kata sandi

