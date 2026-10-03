---
title: "IPageSizeConvertOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Представляет параметры конвертации, поддерживающие размер страницы"
type: docs
weight: 54
url: /ru/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

Представляет параметры конвертации, поддерживающие размер страницы

## Методы

| Метод | Описание |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | Получает желаемый размер страницы после конвертации |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | Устанавливает желаемый размер страницы после конвертации |
|
|  | [getPageWidth()](#getPageWidth--) | Указанная ширина страницы в пунктах, если установлено PageSize.Custom |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | Устанавливает желаемую ширину страницы |
|
|  | [getPageHeight()](#getPageHeight--) | Указанная высота страницы в пунктах, если установлено PageSize.Custom |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | Устанавливает желаемую высоту страницы |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


Получает желаемый размер страницы после конвертации


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


Устанавливает желаемый размер страницы после конвертации


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


Указанная ширина страницы в пунктах, если установлено PageSize.Custom


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


Устанавливает желаемую ширину страницы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


Указанная высота страницы в пунктах, если установлено PageSize.Custom


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


Устанавливает желаемую высоту страницы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageHeight | float |  |

