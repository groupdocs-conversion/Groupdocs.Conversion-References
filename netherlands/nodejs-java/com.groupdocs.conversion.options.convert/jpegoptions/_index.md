---
title: "JpegOptions"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Opties voor conversie naar JPEG‑bestandtype."
type: docs
weight: 20
url: /nl/nodejs-java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Opties voor conversie naar JPEG‑bestandtype.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Initialiseert een nieuw exemplaar van de [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getQuality()](#getQuality--) | Gewenste beeldkwaliteit. |
| [setQuality(int value)](#setQuality-int-) | Gewenste beeldkwaliteit. |
| [getColorMode()](#getColorMode--) | Jpg-kleurmodus. |
| [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Jpg-kleurmodus. |
| [getCompression()](#getCompression--) | Jpg-compressiemethode. |
| [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Jpg-compressiemethode. |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initialiseert een nieuw exemplaar van de [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) klasse.

### getQuality() {#getQuality--}
```
public final int getQuality()
```


Gewenste beeldkwaliteit. De waarde moet tussen 0 en 100 liggen. De standaardwaarde is 100.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


Gewenste beeldkwaliteit. De waarde moet tussen 0 en 100 liggen. De standaardwaarde is 100.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Jpg-kleurmodus.

**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Jpg-kleurmodus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Jpg-compressiemethode.

**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Jpg-compressiemethode.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

