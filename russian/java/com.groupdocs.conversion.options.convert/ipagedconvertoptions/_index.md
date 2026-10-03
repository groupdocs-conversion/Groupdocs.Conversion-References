---
title: "IPagedConvertOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Представляет параметры конвертации, позволяющие ограничить количество страниц, указывая начальную страницу и количество страниц"
type: docs
weight: 55
url: /ru/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

Представляет параметры конвертации, позволяющие ограничить количество страниц, указывая начальную страницу и количество страниц

## Методы

| Метод | Описание |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | Получает номер страницы, с которой начинается конвертация. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | Устанавливает номер страницы, с которой начинается конвертация. |
|
|  | [getPagesCount()](#getPagesCount--) | Получает количество страниц для конвертации, начиная с PageNumber. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | Устанавливает количество страниц для конвертации, начиная с PageNumber. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


Получает номер страницы, с которой начинается конвертация.


**Returns:**
java.lang.Integer - Номер страницы, с которой начинается конвертация.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


Устанавливает номер страницы, с которой начинается конвертация.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pageNumber | int | Номер страницы, с которой начинается конвертация. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


Получает количество страниц для конвертации, начиная с PageNumber.


**Returns:**
java.lang.Integer - Количество страниц для конвертации, начиная с PageNumber.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


Устанавливает количество страниц для конвертации, начиная с PageNumber.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pagesCount | int | Количество страниц для конвертации, начиная с PageNumber. |
|

