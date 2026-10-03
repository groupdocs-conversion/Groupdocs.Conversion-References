---
title: "JpegOptions"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Optionen für die Konvertierung zum Jpeg-Dateityp."
type: docs
weight: 20
url: /de/java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Optionen für die Konvertierung zum Jpeg-Dateityp.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [JpegOptions()](#JpegOptions--) | Initialisiert eine neue Instanz der Klasse [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions). |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getQuality()](#getQuality--) | Gewünschte Bildqualität. |
|
|  | [setQuality(int value)](#setQuality-int-) | Gewünschte Bildqualität. |
|
|  | [getColorMode()](#getColorMode--) | Jpg-Farbmodus. |
|
|  | [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Jpg-Farbmodus. |
|
|  | [getCompression()](#getCompression--) | Jpg-Komprimierungsmethode. |
|
|  | [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Jpg-Komprimierungsmethode. |
|
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initialisiert eine neue Instanz der Klasse [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions).


### getQuality() {#getQuality--}
```
public final int getQuality()
```


Gewünschte Bildqualität. Der Wert muss zwischen 0 und 100 liegen. Der Standardwert ist 100.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


Gewünschte Bildqualität. Der Wert muss zwischen 0 und 100 liegen. Der Standardwert ist 100.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Jpg-Farbmodus.


**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Jpg-Farbmodus.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Jpg-Komprimierungsmethode.


**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Jpg-Komprimierungsmethode.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

