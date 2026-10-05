---
title: "JpegOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры конвертации в тип файла Jpeg."
type: docs
weight: 20
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

Параметры конвертации в тип файла Jpeg.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | Инициализирует новый экземпляр класса [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getQuality()](#getQuality--) | Желаемое качество изображения. |
| [setQuality(int value)](#setQuality-int-) | Желаемое качество изображения. |
| [getColorMode()](#getColorMode--) | Режим цвета JPG. |
| [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Режим цвета JPG. |
| [getCompression()](#getCompression--) | Метод сжатия JPG. |
| [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Метод сжатия JPG. |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


Инициализирует новый экземпляр класса [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions).

### getQuality() {#getQuality--}
```
public final int getQuality()
```


Желаемое качество изображения. Значение должно быть от 0 до 100. Значение по умолчанию — 100.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


Желаемое качество изображения. Значение должно быть от 0 до 100. Значение по умолчанию — 100.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Режим цвета JPG.

**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Режим цвета JPG.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Метод сжатия JPG.

**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Метод сжатия JPG.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

