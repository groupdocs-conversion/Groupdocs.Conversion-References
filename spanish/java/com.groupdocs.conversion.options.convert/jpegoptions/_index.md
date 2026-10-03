---
title: "JpegOptions"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Opciones para la conversión a tipo de archivo Jpeg."
type: docs
weight: 20
url: /es/java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Opciones para la conversión a tipo de archivo Jpeg.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [JpegOptions()](#JpegOptions--) | Inicializa una nueva instancia de la clase [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getQuality()](#getQuality--) | Calidad de imagen deseada. |
|
|  | [setQuality(int value)](#setQuality-int-) | Calidad de imagen deseada. |
|
|  | [getColorMode()](#getColorMode--) | Modo de color Jpg. |
|
|  | [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Modo de color Jpg. |
|
|  | [getCompression()](#getCompression--) | Método de compresión Jpg. |
|
|  | [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Método de compresión Jpg. |
|
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Inicializa una nueva instancia de la clase [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions).


### getQuality() {#getQuality--}
```
public final int getQuality()
```


Calidad de imagen deseada. El valor debe estar entre 0 y 100. El valor predeterminado es 100.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


Calidad de imagen deseada. El valor debe estar entre 0 y 100. El valor predeterminado es 100.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Modo de color Jpg.


**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Modo de color Jpg.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Método de compresión Jpg.


**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Método de compresión Jpg.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

