---
title: "PdfOptimizationOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Definiert Pdf-Optimierungsoptionen."
type: docs
weight: 29
url: /de/java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Definiert Pdf-Optimierungsoptionen.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Initialisiert eine neue Instanz der Klasse [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Duplizierte Streams verknüpfen |
|
|  | [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Duplizierte Streams verknüpfen |
|
|  | [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Unbenutzte Objekte entfernen |
|
|  | [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Unbenutzte Objekte entfernen |
|
|  | [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Unbenutzte Streams entfernen |
|
|  | [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Unbenutzte Streams entfernen |
|
|  | [getCompressImages()](#getCompressImages--) | Wenn CompressImages auf |
true
, werden alle Bilder im Dokument neu komprimiert.
|
|  | [setCompressImages(boolean value)](#setCompressImages-boolean-) | Wenn CompressImages auf |
true
, werden alle Bilder im Dokument neu komprimiert.
|
|  | [getImageQuality()](#getImageQuality--) | Wert in Prozent, wobei 100 % unveränderte Qualität und Bildgröße bedeutet. |
|
|  | [setImageQuality(int value)](#setImageQuality-int-) | Wert in Prozent, wobei 100 % unveränderte Qualität und Bildgröße bedeutet. |
|
|  | [getUnembedFonts()](#getUnembedFonts--) | Schriftarten nicht einbetten, wenn auf true gesetzt |
|
|  | [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Schriftarten nicht einbetten, wenn auf true gesetzt |
|
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
|  | [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Schriftuntermenge-Strategie festlegen |
|
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Initialisiert eine neue Instanz der Klasse [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions).


### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Duplizierte Streams verknüpfen


**Returns:**
boolean
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Duplizierte Streams verknüpfen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Unbenutzte Objekte entfernen


**Returns:**
boolean
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Unbenutzte Objekte entfernen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Unbenutzte Streams entfernen


**Returns:**
boolean
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Unbenutzte Streams entfernen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


Wenn CompressImages auf
true
, werden alle Bilder im Dokument neu komprimiert. Die Kompression wird durch die Eigenschaft ImageQuality definiert.


**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Wenn CompressImages auf
true
, werden alle Bilder im Dokument neu komprimiert. Die Kompression wird durch die Eigenschaft ImageQuality definiert.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Wert in Prozent, wobei 100 % unveränderte Qualität und Bildgröße bedeutet. Um die Bildgröße zu verringern, setzen Sie diese Eigenschaft auf weniger als 100.


**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Wert in Prozent, wobei 100 % unveränderte Qualität und Bildgröße bedeutet. Um die Bildgröße zu verringern, setzen Sie diese Eigenschaft auf weniger als 100.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Schriftarten nicht einbetten, wenn auf true gesetzt


**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Schriftarten nicht einbetten, wenn auf true gesetzt


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

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


Schriftuntermenge-Strategie festlegen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

