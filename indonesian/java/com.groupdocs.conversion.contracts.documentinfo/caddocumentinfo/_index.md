---
title: "CadDocumentInfo"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Berisi metadata dokumen Cad"
type: docs
weight: 11
url: /id/java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Berisi metadata dokumen Cad

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [getWidth()](#getWidth--) | lebar |
|
|  | [getHeight()](#getHeight--) | tinggi |
|
|  | [getLayouts()](#getLayouts--) | tata letak dalam dokumen |
|
|  | [getLayers()](#getLayers--) | lapisan dalam dokumen |
|
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


lebar


**Returns:**
int - lebar

### getHeight() {#getHeight--}
```
public int getHeight()
```


tinggi


**Returns:**
int - tinggi

### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


tata letak dalam dokumen


**Returns:**
java.util.List<java.lang.String> - tata letak dalam dokumen

### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


lapisan dalam dokumen


**Returns:**
java.util.List<java.lang.String> - lapisan dalam dokumen

