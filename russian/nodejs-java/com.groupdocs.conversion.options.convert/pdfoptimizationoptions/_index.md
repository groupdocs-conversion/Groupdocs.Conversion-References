---
title: "PdfOptimizationOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Определяет параметры оптимизации Pdf."
type: docs
weight: 29
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

Определяет параметры оптимизации Pdf.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | Инициализирует новый экземпляр класса [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | Связать дублирующие потоки |
| [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | Связать дублирующие потоки |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | Удалить неиспользуемые объекты |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | Удалить неиспользуемые объекты |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | Удалить неиспользуемые потоки |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | Удалить неиспользуемые потоки |
| [getCompressImages()](#getCompressImages--) | Если параметр CompressImages установлен в true, все изображения в документе перекомпрессируются. |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | Если параметр CompressImages установлен в true, все изображения в документе перекомпрессируются. |
| [getImageQuality()](#getImageQuality--) | Значение в процентах, где 100 % означает неизменное качество и размер изображения. |
| [setImageQuality(int value)](#setImageQuality-int-) | Значение в процентах, где 100 % означает неизменное качество и размер изображения. |
| [getUnembedFonts()](#getUnembedFonts--) | Не встраивать шрифты, если параметр установлен в true |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | Не встраивать шрифты, если параметр установлен в true |
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
| [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | Установить стратегию подмножества шрифтов |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


Инициализирует новый экземпляр класса [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions).

### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


Связать дублирующие потоки

**Returns:**
boolean
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


Связать дублирующие потоки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


Удалить неиспользуемые объекты

**Returns:**
boolean
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


Удалить неиспользуемые объекты

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


Удалить неиспользуемые потоки

**Returns:**
boolean
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


Удалить неиспользуемые потоки

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


Если параметр CompressImages установлен в true, все изображения в документе перекомпрессируются. Сжатие определяется свойством ImageQuality.

**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


Если параметр CompressImages установлен в true, все изображения в документе перекомпрессируются. Сжатие определяется свойством ImageQuality.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


Значение в процентах, где 100 % означает неизменное качество и размер изображения. Чтобы уменьшить размер изображения, установите это свойство меньше 100.

**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


Значение в процентах, где 100 % означает неизменное качество и размер изображения. Чтобы уменьшить размер изображения, установите это свойство меньше 100.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


Не встраивать шрифты, если параметр установлен в true

**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


Не встраивать шрифты, если параметр установлен в true

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

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


Установить стратегию подмножества шрифтов

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

