---
title: "CadDocumentInfo"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Enthält Metadaten für CAD-Dokumente"
type: docs
weight: 11
url: /de/java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Enthält Metadaten für CAD-Dokumente

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getWidth()](#getWidth--) | Breite |
|
|  | [getHeight()](#getHeight--) | Höhe |
|
|  | [getLayouts()](#getLayouts--) | Layouts im Dokument |
|
|  | [getLayers()](#getLayers--) | Ebenen im Dokument |
|
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| CAD | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| Größe | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Breite


**Returns:**
int - Breite

### getHeight() {#getHeight--}
```
public int getHeight()
```


Höhe


**Returns:**
int - Höhe

### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


Layouts im Dokument


**Returns:**
java.util.List<java.lang.String> - Layouts im Dokument

### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


Ebenen im Dokument


**Returns:**
java.util.List<java.lang.String> - Ebenen im Dokument

