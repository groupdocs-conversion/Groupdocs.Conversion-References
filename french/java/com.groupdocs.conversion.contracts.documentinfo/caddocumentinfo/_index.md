---
title: "CadDocumentInfo"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Contient les métadonnées du document Cad"
type: docs
weight: 11
url: /fr/java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Contient les métadonnées du document Cad

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getWidth()](#getWidth--) | largeur |
|
|  | [getHeight()](#getHeight--) | hauteur |
|
|  | [getLayouts()](#getLayouts--) | mises en page du document |
|
|  | [getLayers()](#getLayers--) | calques du document |
|
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| cad | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| size | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


largeur


**Returns:**
int - largeur

### getHeight() {#getHeight--}
```
public int getHeight()
```


hauteur


**Returns:**
int - hauteur

### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


mises en page du document


**Returns:**
java.util.List<java.lang.String> - mises en page du document

### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


calques du document


**Returns:**
java.util.List<java.lang.String> - calques du document

