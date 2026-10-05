---
title: "CadConvertOptions"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Параметры конвертации в тип Cad."
type: docs
weight: 10
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Параметры конвертации в тип Cad.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CadConvertOptions()](#CadConvertOptions--) | Инициализирует новый экземпляр класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


Инициализирует новый экземпляр класса.

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


Получает номер страницы, с которой начинается конвертация.

**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


Устанавливает номер страницы, с которой начинается конвертация.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


Получает количество страниц для конвертации, начиная с PageNumber.

**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


Устанавливает количество страниц для конвертации, начиная с PageNumber.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pagesCount | int |  |

