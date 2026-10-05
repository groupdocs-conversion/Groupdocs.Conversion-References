---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Definierar PDF‑optimeringsalternativ."
type: docs
weight: 29
url: /sv/nodejs-java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Definierar PDF‑optimeringsalternativ.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Initierar en ny instans av [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Länka duplicerade strömmar |
| [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Länka duplicerade strömmar |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Ta bort oanvända objekt |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Ta bort oanvända objekt |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Ta bort oanvända strömmar |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Ta bort oanvända strömmar |
| [getCompressImages()](#getCompressImages--) | Om CompressImages är satt till true, komprimeras alla bilder i dokumentet om igen. |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | Om CompressImages är satt till true, komprimeras alla bilder i dokumentet om igen. |
| [getImageQuality()](#getImageQuality--) | Värde i procent där 100 % är oförändrad kvalitet och bildstorlek. |
| [setImageQuality(int value)](#setImageQuality-int-) | Värde i procent där 100 % är oförändrad kvalitet och bildstorlek. |
| [getUnembedFonts()](#getUnembedFonts--) | Gör så att typsnitt inte bäddas in om satt till true |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Gör så att typsnitt inte bäddas in om satt till true |
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
| [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Ange strategi för typsnittssubset |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Initierar en ny instans av [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) klass.

### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Länka duplicerade strömmar

**Returns:**
boolean
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Länka duplicerade strömmar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Ta bort oanvända objekt

**Returns:**
boolean
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Ta bort oanvända objekt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Ta bort oanvända strömmar

**Returns:**
boolean
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Ta bort oanvända strömmar

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


Om CompressImages är satt till true, komprimeras alla bilder i dokumentet om igen. Komprimeringen definieras av egenskapen ImageQuality.

**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Om CompressImages är satt till true, komprimeras alla bilder i dokumentet om igen. Komprimeringen definieras av egenskapen ImageQuality.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Värde i procent där 100 % är oförändrad kvalitet och bildstorlek. För att minska bildstorleken, sätt denna egenskap till mindre än 100.

**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Värde i procent där 100 % är oförändrad kvalitet och bildstorlek. För att minska bildstorleken, sätt denna egenskap till mindre än 100.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Gör så att typsnitt inte bäddas in om satt till true

**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Gör så att typsnitt inte bäddas in om satt till true

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

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


Ange strategi för typsnittssubset

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

