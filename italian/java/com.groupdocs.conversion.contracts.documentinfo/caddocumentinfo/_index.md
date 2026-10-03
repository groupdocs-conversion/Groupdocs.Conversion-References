---
title: "CadDocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Contiene i metadati del documento Cad"
type: docs
weight: 11
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Contiene i metadati del documento Cad

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getWidth()](#getWidth--) | larghezza |
|
|  | [getHeight()](#getHeight--) | altezza |
|
|  | [getLayouts()](#getLayouts--) | layout nel documento |
|
|  | [getLayers()](#getLayers--) | livelli nel documento |
|
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| dimensione | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


larghezza


**Returns:**
int - larghezza

### getHeight() {#getHeight--}
```
public int getHeight()
```


altezza


**Returns:**
int - altezza

### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


layout nel documento


**Returns:**
java.util.List<java.lang.String> - layout nel documento

### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


livelli nel documento


**Returns:**
java.util.List<java.lang.String> - livelli nel documento

