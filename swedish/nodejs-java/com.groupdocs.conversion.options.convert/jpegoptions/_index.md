---
title: "JpegOptions"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Alternativ för konvertering till JPEG‑filtyp."
type: docs
weight: 20
url: /sv/nodejs-java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Alternativ för konvertering till JPEG‑filtyp.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Initierar en ny instans av klassen [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getQuality()](#getQuality--) | Önskad bildkvalitet. |
| [setQuality(int value)](#setQuality-int-) | Önskad bildkvalitet. |
| [getColorMode()](#getColorMode--) | Jpg-färgläge. |
| [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Jpg-färgläge. |
| [getCompression()](#getCompression--) | Jpg-komprimeringsmetod. |
| [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Jpg-komprimeringsmetod. |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initierar en ny instans av klassen [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions).

### getQuality() {#getQuality--}
```
public final int getQuality()
```


Önskad bildkvalitet. Värdet måste vara mellan 0 och 100. Standardvärdet är 100.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


Önskad bildkvalitet. Värdet måste vara mellan 0 och 100. Standardvärdet är 100.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Jpg-färgläge.

**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Jpg-färgläge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Jpg-komprimeringsmetod.

**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Jpg-komprimeringsmetod.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

