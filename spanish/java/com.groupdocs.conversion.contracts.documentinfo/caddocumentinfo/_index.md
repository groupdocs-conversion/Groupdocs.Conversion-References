---
title: "CadDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Contiene metadatos del documento de Cad"
type: docs
weight: 11
url: /es/java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Contiene metadatos del documento de Cad

## Constructores

| Constructor | Descripción |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getWidth()](#getWidth--) | ancho |
|
|  | [getHeight()](#getHeight--) | altura |
|
|  | [getLayouts()](#getLayouts--) | diseños en el documento |
|
|  | [getLayers()](#getLayers--) | capas en el documento |
|
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


ancho


**Returns:**
int - ancho

### getHeight() {#getHeight--}
```
public int getHeight()
```


altura


**Returns:**
int - altura

### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


diseños en el documento


**Returns:**
java.util.List<java.lang.String> - diseños en el documento

### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


capas en el documento


**Returns:**
java.util.List<java.lang.String> - capas en el documento

