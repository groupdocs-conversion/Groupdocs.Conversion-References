---
title: "WordProcessingConvertOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры конвертации в тип файла WordProcessing."
type: docs
weight: 48
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
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
| [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | Инициализирует новый экземпляр класса [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions). |
## Методы

| Метод | Описание |
| --- | --- |
| [getDpi()](#getDpi--) | Желаемое DPI страницы после конвертации. |
| [setDpi(int value)](#setDpi-int-) | Желаемое DPI страницы после конвертации. |
| [getPassword()](#getPassword--) | Установите это свойство, если вы хотите защитить преобразованный документ паролем. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Установите это свойство, если вы хотите защитить преобразованный документ паролем. |
| [getRtfOptions()](#getRtfOptions--) | Параметры конвертации, специфичные для RTF |
| [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | Параметры конвертации, специфичные для RTF |
| [getZoom()](#getZoom--) | Указывает уровень масштабирования в процентах. |
| [setZoom(int value)](#setZoom-int-) | Указывает уровень масштабирования в процентах. |
| [getMarginTop()](#getMarginTop--) | Желаемый верхний отступ страницы в пикселях после конвертации. |
| [setMarginTop(int value)](#setMarginTop-int-) | Желаемый верхний отступ страницы в пикселях после конвертации. |
| [getMarginBottom()](#getMarginBottom--) | Желаемый нижний отступ страницы в пикселях после конвертации. |
| [setMarginBottom(int value)](#setMarginBottom-int-) | Желаемый нижний отступ страницы в пикселях после конвертации. |
| [getMarginLeft()](#getMarginLeft--) | Желаемый левый отступ страницы в пикселях после конвертации. |
| [setMarginLeft(int value)](#setMarginLeft-int-) | Желаемый левый отступ страницы в пикселях после конвертации. |
| [getMarginRight()](#getMarginRight--) | Желаемый правый отступ страницы в пикселях после конвертации. |
| [setMarginRight(int value)](#setMarginRight-int-) | Желаемый правый отступ страницы в пикселях после конвертации. |
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


Установите это свойство, если вы хотите защитить преобразованный документ паролем.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Установите это свойство, если вы хотите защитить преобразованный документ паролем.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | java.lang.String |  |

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


Параметры конвертации, специфичные для RTF

**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


Параметры конвертации, специфичные для RTF

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


Указывает уровень масштабирования в процентах. По умолчанию — 100. Масштаб по умолчанию поддерживается до Microsoft Word 2010. Начиная с Microsoft Word 2013 масштаб по умолчанию больше не задаётся в документе, вместо этого, кажется, используется коэффициент масштабирования последнего открытого документа.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


Указывает уровень масштабирования в процентах. По умолчанию — 100. Масштаб по умолчанию поддерживается до Microsoft Word 2010. Начиная с Microsoft Word 2013 масштаб по умолчанию больше не задаётся в документе, вместо этого, кажется, используется коэффициент масштабирования последнего открытого документа.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getMarginTop() {#getMarginTop--}
```
public final int getMarginTop()
```


Желаемый верхний отступ страницы в пикселях после конвертации.

**Returns:**
int
### setMarginTop(int value) {#setMarginTop-int-}
```
public final void setMarginTop(int value)
```


Желаемый верхний отступ страницы в пикселях после конвертации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getMarginBottom() {#getMarginBottom--}
```
public final int getMarginBottom()
```


Желаемый нижний отступ страницы в пикселях после конвертации.

**Returns:**
int
### setMarginBottom(int value) {#setMarginBottom-int-}
```
public final void setMarginBottom(int value)
```


Желаемый нижний отступ страницы в пикселях после конвертации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getMarginLeft() {#getMarginLeft--}
```
public final int getMarginLeft()
```


Желаемый левый отступ страницы в пикселях после конвертации.

**Returns:**
int
### setMarginLeft(int value) {#setMarginLeft-int-}
```
public final void setMarginLeft(int value)
```


Желаемый левый отступ страницы в пикселях после конвертации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

### getMarginRight() {#getMarginRight--}
```
public final int getMarginRight()
```


Желаемый правый отступ страницы в пикселях после конвертации.

**Returns:**
int
### setMarginRight(int value) {#setMarginRight-int-}
```
public final void setMarginRight(int value)
```


Желаемый правый отступ страницы в пикселях после конвертации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| значение | int |  |

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


Установить желаемый размер страницы после конвертации

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Указана ширина страницы в пунктах, если  установлено в PageSize.Custom

**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


Установить желаемую ширину страницы

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Указана высота страницы в пунктах, если  установлено в PageSize.Custom

**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


Установить желаемую высоту страницы

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

