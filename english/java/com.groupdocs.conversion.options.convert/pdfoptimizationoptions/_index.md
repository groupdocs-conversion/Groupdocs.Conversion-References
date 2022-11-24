---
title: PdfOptimizationOptions
second_title: GroupDocs.Conversion for Java API Reference
description: Defines Pdf optimization options.
type: docs
weight: 28
url: /java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Defines Pdf optimization options.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Initializes new instance of [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Link duplicate streams |
| [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Link duplicate streams |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Remove unused objects |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Remove unused objects |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Remove unused streams |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Remove unused streams |
| [getCompressImages()](#getCompressImages--) | If CompressImages set to  true , all images in the document are recompressed. |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | If CompressImages set to  true , all images in the document are recompressed. |
| [getImageQuality()](#getImageQuality--) | Value in percent where 100% is unchanged quality and image size. |
| [setImageQuality(int value)](#setImageQuality-int-) | Value in percent where 100% is unchanged quality and image size. |
| [getUnembedFonts()](#getUnembedFonts--) | Make fonts not embedded if set to true |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Make fonts not embedded if set to true |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Initializes new instance of [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) class.

### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Link duplicate streams

**Returns:**
boolean
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Link duplicate streams

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Remove unused objects

**Returns:**
boolean
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Remove unused objects

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Remove unused streams

**Returns:**
boolean
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Remove unused streams

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


If CompressImages set to  true , all images in the document are recompressed. The compression is defined by the ImageQuality property.

**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


If CompressImages set to  true , all images in the document are recompressed. The compression is defined by the ImageQuality property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Value in percent where 100% is unchanged quality and image size. To decrease the image size set this property to less than 100

**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Value in percent where 100% is unchanged quality and image size. To decrease the image size set this property to less than 100

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Make fonts not embedded if set to true

**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Make fonts not embedded if set to true

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

