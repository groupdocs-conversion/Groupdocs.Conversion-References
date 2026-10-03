---
title: "WordProcessingDocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Berisi metadata dokumen Pengolah Kata"
type: docs
weight: 45
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Berisi metadata dokumen Pengolah Kata

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWords()](#getWords--) | Mendapatkan jumlah kata |
|
|  | [getLines()](#getLines--) | Mendapatkan jumlah baris |
|
|  | [getTitle()](#getTitle--) | Mendapatkan judul |
|
|  | [getAuthor()](#getAuthor--) | Mendapatkan penulis |
|
|  | [isPasswordProtected()](#isPasswordProtected--) | Mendapatkan apakah dokumen dilindungi kata sandi |
|
|  | [getTableOfContents()](#getTableOfContents--) | Daftar isi |
|
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pengolahan kata | com.aspose.words.Document |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Mendapatkan jumlah kata


**Returns:**
int - jumlah kata

### getLines() {#getLines--}
```
public int getLines()
```


Mendapatkan jumlah baris


**Returns:**
int - jumlah baris

### getTitle() {#getTitle--}
```
public String getTitle()
```


Mendapatkan judul


**Returns:**
java.lang.String - judul

### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Mendapatkan penulis


**Returns:**
java.lang.String - penulis

### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Mendapatkan apakah dokumen dilindungi kata sandi


**Returns:**
boolean - `true` jika dokumen dilindungi kata sandi

### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


Daftar isi


**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - Daftar isi

