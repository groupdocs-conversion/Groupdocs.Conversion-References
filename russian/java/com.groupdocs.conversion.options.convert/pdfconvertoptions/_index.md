---
title: "PdfConvertOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры конвертации в тип файла Pdf."
type: docs
weight: 25
url: /ru/java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Параметры конвертации в тип файла Pdf.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [PdfConvertOptions()](#PdfConvertOptions--) | Инициализирует новый экземпляр класса [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions). |
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
|  | [getPdfOptions()](#getPdfOptions--) | Pdf-специфические параметры конвертации |
|
|  | [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Pdf-специфические параметры конвертации |
|
|  | [getRotate()](#getRotate--) | Поворот страницы |
|
|  | [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | Поворот страницы |
|
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
### PdfConvertOptions() {#PdfConvertOptions--}
```
public PdfConvertOptions()
```


Инициализирует новый экземпляр класса [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions).


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

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Pdf-специфические параметры конвертации


**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Pdf-специфические параметры конвертации


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


Поворот страницы


**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


Поворот страницы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

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

