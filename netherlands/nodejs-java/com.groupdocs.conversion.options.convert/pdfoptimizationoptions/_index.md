---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Definieert PDF‑optimalisatieopties."
type: docs
weight: 29
url: /nl/nodejs-java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Definieert PDF‑optimalisatieopties.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Initialiseert een nieuw exemplaar van de klasse [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions). |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Koppel dubbele streams |
| [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Koppel dubbele streams |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Verwijder ongebruikte objecten |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Verwijder ongebruikte objecten |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Verwijder ongebruikte streams |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Verwijder ongebruikte streams |
| [getCompressImages()](#getCompressImages--) | Als CompressImages is ingesteld op true, worden alle afbeeldingen in het document opnieuw gecomprimeerd. |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | Als CompressImages is ingesteld op true, worden alle afbeeldingen in het document opnieuw gecomprimeerd. |
| [getImageQuality()](#getImageQuality--) | Waarde in procent waarbij 100% onveranderde kwaliteit en afbeeldingsgrootte betekent. |
| [setImageQuality(int value)](#setImageQuality-int-) | Waarde in procent waarbij 100% onveranderde kwaliteit en afbeeldingsgrootte betekent. |
| [getUnembedFonts()](#getUnembedFonts--) | Maak lettertypen niet ingesloten als dit op true is ingesteld |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Maak lettertypen niet ingesloten als dit op true is ingesteld |
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
| [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Stel lettertype-subsetstrategie in |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Initialiseert een nieuw exemplaar van de klasse [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions).

### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Koppel dubbele streams

**Returns:**
boolean
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Koppel dubbele streams

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Verwijder ongebruikte objecten

**Returns:**
boolean
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Verwijder ongebruikte objecten

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Verwijder ongebruikte streams

**Returns:**
boolean
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Verwijder ongebruikte streams

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


Als CompressImages is ingesteld op true, worden alle afbeeldingen in het document opnieuw gecomprimeerd. De compressie wordt bepaald door de ImageQuality-eigenschap.

**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Als CompressImages is ingesteld op true, worden alle afbeeldingen in het document opnieuw gecomprimeerd. De compressie wordt bepaald door de ImageQuality-eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Waarde in procent waarbij 100% onveranderde kwaliteit en afbeeldingsgrootte betekent. Om de afbeeldingsgrootte te verkleinen, stel deze eigenschap in op minder dan 100.

**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Waarde in procent waarbij 100% onveranderde kwaliteit en afbeeldingsgrootte betekent. Om de afbeeldingsgrootte te verkleinen, stel deze eigenschap in op minder dan 100.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Maak lettertypen niet ingesloten als dit op true is ingesteld

**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Maak lettertypen niet ingesloten als dit op true is ingesteld

**Parameters:**
| Parameter | Type | Beschrijving |
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


Stel lettertype-subsetstrategie in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

