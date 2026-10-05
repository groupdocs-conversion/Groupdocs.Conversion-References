---
title: "PdfDocumentInfo"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Pdf belge meta verilerini içerir"
type: docs
weight: 31
url: /tr/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/pdfdocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class PdfDocumentInfo extends DocumentInfo
```

Pdf belge meta verilerini içerir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfDocumentInfo(Document pdf, FileType format, long size)](#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) | Sürümü alır |
| [getTitle()](#getTitle--) | Başlığı alır |
| [getAuthor()](#getAuthor--) | Yazarı alır |
| [isPasswordProtected()](#isPasswordProtected--) | Şifrelenmiş olup olduğunu alır |
| [isLandscape()](#isLandscape--) | Sayfanın yatay olup olduğunu alır |
| [getHeight()](#getHeight--) | Sayfa yüksekliğini alır |
| [getWidth()](#getWidth--) | Sayfa genişliğini alır |
| [getTableOfContents()](#getTableOfContents--) | İçindekiler tablosunu alır |
| [setTableOfContents(List<TableOfContentsItem> tableOfContents)](#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--) | İçindekiler tablosunu ayarlar |
### PdfDocumentInfo(Document pdf, FileType format, long size) {#PdfDocumentInfo-com.aspose.pdf.Document-com.groupdocs.conversion.filetypes.FileType-long-}
```
public PdfDocumentInfo(Document pdf, FileType format, long size)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdf | com.aspose.pdf.Document |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getVersion() {#getVersion--}
```
public String getVersion()
```


Sürümü alır

**Returns:**
java.lang.String - sürüm
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


Şifrelenmiş olup olduğunu alır

**Returns:**
boolean - şifrelenmişse doğru
### isLandscape() {#isLandscape--}
```
public boolean isLandscape()
```


Sayfanın yatay olup olduğunu alır

**Returns:**
boolean - sayfa yatay ise doğru
### getHeight() {#getHeight--}
```
public double getHeight()
```


Sayfa yüksekliğini alır

**Returns:**
double - sayfa yüksekliği
### getWidth() {#getWidth--}
```
public double getWidth()
```


Sayfa genişliğini alır

**Returns:**
double - sayfa genişliği
### getTableOfContents() {#getTableOfContents--}
```
public List<TableOfContentsItem> getTableOfContents()
```


İçindekiler tablosunu alır

**Returns:**
java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> - İçindekiler tablosu
### setTableOfContents(List<TableOfContentsItem> tableOfContents) {#setTableOfContents-java.util.List-com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem--}
```
public void setTableOfContents(List<TableOfContentsItem> tableOfContents)
```


İçindekiler tablosunu ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tableOfContents | java.util.List<com.groupdocs.conversion.contracts.documentinfo.TableOfContentsItem> | İçindekiler tablosu |

