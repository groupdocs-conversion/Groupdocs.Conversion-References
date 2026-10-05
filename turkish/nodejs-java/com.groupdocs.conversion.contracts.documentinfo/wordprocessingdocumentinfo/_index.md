---
title: "WordProcessingDocumentInfo"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Wordprocessing belge meta verilerini içerir"
type: docs
weight: 48
url: /tr/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/wordprocessingdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class WordProcessingDocumentInfo extends DocumentInfo
```

Wordprocessing belge meta verilerini içerir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)](#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWords()](#getWords--) | Kelime sayısını alır |
| [getLines()](#getLines--) | Satır sayısını alır |
| [getTitle()](#getTitle--) | Başlığı alır |
| [getAuthor()](#getAuthor--) | Yazarı alır |
| [isPasswordProtected()](#isPasswordProtected--) | Belgenin şifre korumalı olup olmadığını alır |
| [getTableOfContents()](#getTableOfContents--) | İçindekiler tablosu |
### WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size) {#WordProcessingDocumentInfo-com.aspose.words.Document-boolean-com.groupdocs.conversion.filetypes.FileType-long-}
```
public WordProcessingDocumentInfo(Document wordprocessing, boolean isPasswordProtected, FileType format, long size)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| kelime işleme | com.aspose.words.Document |  |
| isPasswordProtected | boolean |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWords() {#getWords--}
```
public int getWords()
```


Kelime sayısını alır

**Returns:**
int - kelime sayısı
### getLines() {#getLines--}
```
public int getLines()
```


Satır sayısını alır

**Returns:**
int - satır sayısı
### getTitle() {#getTitle--}
```
public String getTitle()
```


Başlığı alır

**Returns:**
java.lang.String - başlık
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Yazarı alır

**Returns:**
java.lang.String - yazar
### isPasswordProtected() {#isPasswordProtected--}
```
public boolean isPasswordProtected()
```


Belgenin şifre korumalı olup olmadığını alır

**Returns:**
boolean - `true` eğer belge şifre korumalıysa
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


İçindekiler tablosu

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - İçindekiler tablosu
