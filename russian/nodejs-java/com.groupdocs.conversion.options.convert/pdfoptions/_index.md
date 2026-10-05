---
title: "PdfOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры конвертации в тип файла Pdf."
type: docs
weight: 30
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

Параметры конвертации в тип файла Pdf.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | ctor |
## Методы

| Метод | Описание |
| --- | --- |
| [getPdfFormat()](#getPdfFormat--) | Устанавливает PDF-формат конвертируемого документа. |
| [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | Устанавливает PDF-формат конвертируемого документа. |
| [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Удаляет соответствие Pdf-A |
| [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Удаляет соответствие Pdf-A |
| [getZoom()](#getZoom--) | Указывает уровень масштабирования в процентах. |
| [setZoom(int value)](#setZoom-int-) | Указывает уровень масштабирования в процентах. |
| [getLinearize()](#getLinearize--) | Линеаризует PDF-документ для веба |
| [setLinearize(boolean value)](#setLinearize-boolean-) | Линеаризует PDF-документ для веба |
| [getOptimizationOptions()](#getOptimizationOptions--) | Параметры оптимизации PDF |
| [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | Параметры оптимизации PDF |
| [getGrayscale()](#getGrayscale--) | Конвертировать PDF из цветового пространства RGB в градации серого |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | Конвертировать PDF из цветового пространства RGB в градации серого |
| [getFormattingOptions()](#getFormattingOptions--) | Параметры форматирования PDF |
| [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | Параметры форматирования PDF |
| [getDocumentInfo()](#getDocumentInfo--) | Метаданные PDF-документа. |
| [setDocumentInfo(PdfDocumentInfo documentInfo)](#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-) |  |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


ctor

### getPdfFormat() {#getPdfFormat--}
```
public final PdfFormats getPdfFormat()
```


Устанавливает PDF-формат конвертируемого документа.

**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


Устанавливает PDF-формат конвертируемого документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Удаляет соответствие Pdf-A

**Returns:**
boolean
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Удаляет соответствие Pdf-A

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Указывает уровень масштабирования в процентах. По умолчанию 100.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Указывает уровень масштабирования в процентах. По умолчанию 100.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


Линеаризует PDF-документ для веба

**Returns:**
boolean
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


Линеаризует PDF-документ для веба

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


Параметры оптимизации PDF

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


Параметры оптимизации PDF

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


Конвертировать PDF из цветового пространства RGB в градации серого

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


Конвертировать PDF из цветового пространства RGB в градации серого

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | boolean |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


Параметры форматирования PDF

**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


Параметры форматирования PDF

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


Метаданные PDF-документа.

**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

