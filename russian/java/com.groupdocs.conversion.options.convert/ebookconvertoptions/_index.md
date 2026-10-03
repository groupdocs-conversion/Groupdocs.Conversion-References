---
title: "EBookConvertOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры конвертации в тип файла EBook."
type: docs
weight: 14
url: /ru/java/com.groupdocs.conversion.options.convert/ebookconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class EBookConvertOptions extends CommonConvertOptions<EBookFileType> implements IPageSizeConvertOptions, IPageOrientationConvertOptions
```

Параметры конвертации в тип файла EBook.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [EBookConvertOptions()](#EBookConvertOptions--) | Инициализирует новый экземпляр класса. |
|
## Методы

| Метод | Описание |
| --- | --- |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
### EBookConvertOptions() {#EBookConvertOptions--}
```
public EBookConvertOptions()
```


Инициализирует новый экземпляр класса.


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

