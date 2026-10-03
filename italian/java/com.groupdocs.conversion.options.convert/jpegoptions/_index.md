---
title: "JpegOptions"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Opzioni per la conversione al tipo di file Jpeg."
type: docs
weight: 20
url: /it/java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Opzioni per la conversione al tipo di file Jpeg.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [JpegOptions()](#JpegOptions--) | Inizializza una nuova istanza della classe [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getQuality()](#getQuality--) | Qualità dell'immagine desiderata. |
|
|  | [setQuality(int value)](#setQuality-int-) | Qualità dell'immagine desiderata. |
|
|  | [getColorMode()](#getColorMode--) | Modalità colore Jpg. |
|
|  | [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Modalità colore Jpg. |
|
|  | [getCompression()](#getCompression--) | Metodo di compressione Jpg. |
|
|  | [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Metodo di compressione Jpg. |
|
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Inizializza una nuova istanza della classe [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions).


### getQuality() {#getQuality--}
```
public final int getQuality()
```


Qualità immagine desiderata. Il valore deve essere compreso tra 0 e 100. Il valore predefinito è 100.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


Qualità immagine desiderata. Il valore deve essere compreso tra 0 e 100. Il valore predefinito è 100.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Modalità colore Jpg.


**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Modalità colore Jpg.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Metodo di compressione Jpg.


**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Metodo di compressione Jpg.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

