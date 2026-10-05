---
title: "CadDocumentInfo"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Cad belge üst verilerini içerir"
type: docs
weight: 11
url: /tr/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Cad belge üst verilerini içerir
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getWidth()](#getWidth--) | genişlik |
| [getHeight()](#getHeight--) | yükseklik |
| [getLayouts()](#getLayouts--) | belgedeki düzenler |
| [getLayers()](#getLayers--) | belgedeki katmanlar |
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


genişlik

**Returns:**
int - genişlik
### getHeight() {#getHeight--}
```
public int getHeight()
```


yükseklik

**Returns:**
int - yükseklik
### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


belgedeki düzenler

**Returns:**
java.util.List<java.lang.String> - belgedeki düzenler
### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


belgedeki katmanlar

**Returns:**
java.util.List<java.lang.String> - belgedeki katmanlar
