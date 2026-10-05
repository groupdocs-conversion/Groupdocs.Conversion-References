---
title: "DjVuDocumentInfo"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Contiene metadatos de documento DjVu"
type: docs
weight: 15
url: /es/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

Contiene metadatos de documento DjVu
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [getVerticalResolution()](#getVerticalResolution--) | Obtiene la resolución vertical |
| [getHorizontalResolution()](#getHorizontalResolution--) | Obtiene la resolución horizontal |
| [getOpacity()](#getOpacity--) | Obtiene la opacidad de la imagen |
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imagen | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| tamaño | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Obtiene la resolución vertical

**Returns:**
double - resolución vertical
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Obtiene la resolución horizontal

**Returns:**
double - resolución horizontal
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Obtiene la opacidad de la imagen

**Returns:**
float - opacidad de la imagen
