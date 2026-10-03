---
title: "DjVuDocumentInfo"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Contiene i metadati del documento DjVu"
type: docs
weight: 15
url: /it/java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

Contiene i metadati del documento DjVu

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getVerticalResolution()](#getVerticalResolution--) | Ottiene la risoluzione verticale |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | Ottiene la risoluzione orizzontale |
|
|  | [getOpacity()](#getOpacity--) | Ottiene l'opacità dell'immagine |
|
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| immagine | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| dimensione | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Ottiene la risoluzione verticale


**Returns:**
double - risoluzione verticale

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Ottiene la risoluzione orizzontale


**Returns:**
double - risoluzione orizzontale

### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Ottiene l'opacità dell'immagine


**Returns:**
float - opacità dell'immagine

