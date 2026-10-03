---
title: "CadDocumentInfo"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Bevat metadata van Cad-document"
type: docs
weight: 11
url: /nl/java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Bevat metadata van Cad-document

## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getWidth()](#getWidth--) | breedte |
|
|  | [getHeight()](#getHeight--) | hoogte |
|
|  | [getLayouts()](#getLayouts--) | lay-outs in het document |
|
|  | [getLayers()](#getLayers--) | lagen in het document |
|
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


breedte


**Returns:**
int - breedte

### getHeight() {#getHeight--}
```
public int getHeight()
```


hoogte


**Returns:**
int - hoogte

### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


lay-outs in het document


**Returns:**
java.util.List<java.lang.String> - lay-outs in het document

### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


lagen in het document


**Returns:**
java.util.List<java.lang.String> - lagen in het document

