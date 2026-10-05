---
title: "CadDocumentInfo"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Innehåller metadata för CAD-dokument"
type: docs
weight: 11
url: /sv/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Innehåller metadata för CAD-dokument
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getWidth()](#getWidth--) | bredd |
| [getHeight()](#getHeight--) | höjd |
| [getLayouts()](#getLayouts--) | layouter i dokumentet |
| [getLayers()](#getLayers--) | lager i dokumentet |
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


bredd

**Returns:**
int - bredd
### getHeight() {#getHeight--}
```
public int getHeight()
```


höjd

**Returns:**
int - höjd
### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


layouter i dokumentet

**Returns:**
java.util.List<java.lang.String> - layouter i dokumentet
### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


lager i dokumentet

**Returns:**
java.util.List<java.lang.String> - lager i dokumentet
