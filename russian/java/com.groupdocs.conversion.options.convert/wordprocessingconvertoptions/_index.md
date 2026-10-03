---
title: "WordProcessingConvertOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры конвертации в тип файла WordProcessing."
type: docs
weight: 48
url: /ru/java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

Параметры конвертации в тип файла WordProcessing.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Инициализирует новый экземпляр класса [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions). |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getDpi()](#getDpi--) | Желаемое DPI страницы после конвертации. |
|
|  | [setDpi(int value)](#setDpi-int-) | Желаемое DPI страницы после конвертации. |
|
|  | [getPassword()](#getPassword--) | Установите это свойство, если хотите защитить конвертированный документ паролем. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Установите это свойство, если хотите защитить конвертированный документ паролем. |
|
|  | [getRtfOptions()](#getRtfOptions--) | Специфические параметры конвертации RTF |
|
|  | [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | Специфические параметры конвертации RTF |
|
|  | [getZoom()](#getZoom--) | Указывает уровень масштабирования в процентах. |
|
|  | [setZoom(int value)](#setZoom-int-) | Указывает уровень масштабирования в процентах. |
|
|  | [getMarginTop()](#getMarginTop--) | Желаемый верхний отступ страницы в пунктах после конвертации. |
|
|  | [setMarginTop(float value)](#setMarginTop-float-) | Желаемый верхний отступ страницы в пунктах после конвертации. |
|
|  | [getMarginBottom()](#getMarginBottom--) | Желаемый нижний отступ страницы в пунктах после конвертации. |
|
|  | [setMarginBottom(float value)](#setMarginBottom-float-) | Желаемый нижний отступ страницы в пунктах после конвертации. |
|
|  | [getMarginLeft()](#getMarginLeft--) | Желаемый левый отступ страницы в пунктах после конвертации. |
|
|  | [setMarginLeft(float value)](#setMarginLeft-float-) | Желаемый левый отступ страницы в пунктах после конвертации. |
|
|  | [getMarginRight()](#getMarginRight--) | Желаемый правый отступ страницы в пунктах после конвертации. |
|
|  | [setMarginRight(float value)](#setMarginRight-float-) | Желаемый правый отступ страницы в пунктах после конвертации. |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPdfRecognitionMode()](#getPdfRecognitionMode--) |  |
| [setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)](#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-) |  |
|  | [getMarkdownOptions()](#getMarkdownOptions--) | Получает |
|
|  | [setMarkdownOptions(MarkdownOptions markdownOptions)](#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-) | Устанавливает |
|
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


Инициализирует новый экземпляр класса [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions).


### getDpi() {#getDpi--}
```
public final int getDpi()
```


Желаемое DPI страницы после конвертации. Разрешение по умолчанию: 96 dpi.


**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


Желаемое DPI страницы после конвертации. Разрешение по умолчанию: 96 dpi.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Установите это свойство, если хотите защитить конвертированный документ паролем.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Установите это свойство, если хотите защитить конвертированный документ паролем.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


Специфические параметры конвертации RTF


**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


Специфические параметры конвертации RTF


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Указывает уровень масштабирования в процентах. По умолчанию — 100.
Масштаб по умолчанию поддерживается до Microsoft Word 2010. Начиная с Microsoft Word 2013 масштаб по умолчанию больше не устанавливается для документа, вместо этого, кажется, используется коэффициент масштабирования последнего открытого документа.


**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Указывает уровень масштабирования в процентах. По умолчанию — 100.
Масштаб по умолчанию поддерживается до Microsoft Word 2010. Начиная с Microsoft Word 2013 масштаб по умолчанию больше не устанавливается для документа, вместо этого, кажется, используется коэффициент масштабирования последнего открытого документа.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getMarginTop() {#getMarginTop--}
```
public final float getMarginTop()
```


Желаемый верхний отступ страницы в пунктах после конвертации.


**Returns:**
float
### setMarginTop(float value) {#setMarginTop-float-}
```
public final void setMarginTop(float value)
```


Желаемый верхний отступ страницы в пунктах после конвертации.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### getMarginBottom() {#getMarginBottom--}
```
public final float getMarginBottom()
```


Желаемый нижний отступ страницы в пунктах после конвертации.


**Returns:**
float
### setMarginBottom(float value) {#setMarginBottom-float-}
```
public final void setMarginBottom(float value)
```


Желаемый нижний отступ страницы в пунктах после конвертации.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


Желаемый левый отступ страницы в пунктах после конвертации.


**Returns:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


Желаемый левый отступ страницы в пунктах после конвертации.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


Желаемый правый отступ страницы в пунктах после конвертации.


**Returns:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


Желаемый правый отступ страницы в пунктах после конвертации.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | float |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


Получает ориентацию страницы после конвертации


**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


Устанавливает желаемую ориентацию страницы после конвертации


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


Получает желаемый размер страницы после конвертации


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


Устанавливает желаемый размер страницы после конвертации


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Указанная ширина страницы в пунктах, если установлено PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Устанавливает желаемую ширину страницы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Указанная высота страницы в пунктах, если установлено PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Устанавливает желаемую высоту страницы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageHeight | float |  |

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


Получает режим распознавания при конвертации из pdf


**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


Устанавливает режим распознавания при конвертации из pdf


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

### getMarkdownOptions() {#getMarkdownOptions--}
```
public MarkdownOptions getMarkdownOptions()
```


Получает


**Returns:**
[MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions)
### setMarkdownOptions(MarkdownOptions markdownOptions) {#setMarkdownOptions-com.groupdocs.conversion.options.convert.MarkdownOptions-}
```
public void setMarkdownOptions(MarkdownOptions markdownOptions)
```


Устанавливает


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| markdownOptions | [MarkdownOptions](../../com.groupdocs.conversion.options.convert/markdownoptions) |  |

