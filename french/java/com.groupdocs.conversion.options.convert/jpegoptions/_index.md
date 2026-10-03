---
title: "JpegOptions"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Options pour la conversion vers le type de fichier Jpeg."
type: docs
weight: 20
url: /fr/java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Options pour la conversion vers le type de fichier Jpeg.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [JpegOptions()](#JpegOptions--) | Initialise une nouvelle instance de la classe [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions). |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getQuality()](#getQuality--) | Qualité d'image souhaitée. |
|
|  | [setQuality(int value)](#setQuality-int-) | Qualité d'image souhaitée. |
|
|  | [getColorMode()](#getColorMode--) | Mode couleur Jpg. |
|
|  | [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Mode couleur Jpg. |
|
|  | [getCompression()](#getCompression--) | Méthode de compression Jpg. |
|
|  | [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Méthode de compression Jpg. |
|
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Initialise une nouvelle instance de la classe [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions).


### getQuality() {#getQuality--}
```
public final int getQuality()
```


Qualité d'image souhaitée. La valeur doit être comprise entre 0 et 100. La valeur par défaut est 100.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


Qualité d'image souhaitée. La valeur doit être comprise entre 0 et 100. La valeur par défaut est 100.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Mode couleur Jpg.


**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Mode couleur Jpg.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Méthode de compression Jpg.


**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Méthode de compression Jpg.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

