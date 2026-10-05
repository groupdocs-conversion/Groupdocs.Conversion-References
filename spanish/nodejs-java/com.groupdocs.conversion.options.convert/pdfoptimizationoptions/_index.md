---
title: "PdfOptimizationOptions"
second_title: "Referencia de API de GroupDocs.Conversion para Node.js vía Java"
description: "Define las opciones de optimización Pdf."
type: docs
weight: 29
url: /es/nodejs-java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Define las opciones de optimización Pdf.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Inicializa una nueva instancia de [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) clase. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Vincular flujos duplicados |
| [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Vincular flujos duplicados |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Eliminar objetos no utilizados |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Eliminar objetos no utilizados |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Eliminar flujos no utilizados |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Eliminar flujos no utilizados |
| [getCompressImages()](#getCompressImages--) | Si CompressImages está configurado en  true , todas las imágenes del documento se recomprimen. |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | Si CompressImages está configurado en  true , todas las imágenes del documento se recomprimen. |
| [getImageQuality()](#getImageQuality--) | Valor en porcentaje donde 100% representa calidad y tamaño de imagen sin cambios. |
| [setImageQuality(int value)](#setImageQuality-int-) | Valor en porcentaje donde 100% representa calidad y tamaño de imagen sin cambios. |
| [getUnembedFonts()](#getUnembedFonts--) | No incrustar fuentes si está configurado en true |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | No incrustar fuentes si está configurado en true |
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
| [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Establecer estrategia de subconjunto de fuentes |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Inicializa una nueva instancia de [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) clase.

### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Vincular flujos duplicados

**Returns:**
boolean
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Vincular flujos duplicados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Eliminar objetos no utilizados

**Returns:**
boolean
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Eliminar objetos no utilizados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Eliminar flujos no utilizados

**Returns:**
boolean
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Eliminar flujos no utilizados

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


Si CompressImages está configurado en  true , todas las imágenes del documento se recomprimen. La compresión se define mediante la propiedad ImageQuality.

**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Si CompressImages está configurado en  true , todas las imágenes del documento se recomprimen. La compresión se define mediante la propiedad ImageQuality.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Valor en porcentaje donde 100% representa calidad y tamaño de imagen sin cambios. Para reducir el tamaño de la imagen, establezca esta propiedad en menos de 100.

**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Valor en porcentaje donde 100% representa calidad y tamaño de imagen sin cambios. Para reducir el tamaño de la imagen, establezca esta propiedad en menos de 100.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


No incrustar fuentes si está configurado en true

**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


No incrustar fuentes si está configurado en true

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getFontSubsetStrategy() {#getFontSubsetStrategy--}
```
public PdfFontSubsetStrategy getFontSubsetStrategy()
```




**Returns:**
[PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy)
### setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy) {#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-}
```
public void setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)
```


Establecer estrategia de subconjunto de fuentes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

