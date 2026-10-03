---
title: "IPageRangedConvertOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Представляет параметры конвертации, поддерживающие конвертацию конкретного списка страниц"
type: docs
weight: 52
url: /ru/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

Представляет параметры конвертации, поддерживающие конвертацию конкретного списка страниц

## Методы

| Метод | Описание |
| --- | --- |
|  | [getPages()](#getPages--) | Получает список индексов страниц для конвертации. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | Устанавливает список индексов страниц для конвертации. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


Получает список индексов страниц для конвертации. Должен быть указан для конвертации конкретных страниц.


**Returns:**
java.util.List<java.lang.Integer> - Список индексов страниц для конвертации. Должен быть указан для конвертации конкретных страниц.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


Устанавливает список индексов страниц для конвертации. Должен быть указан для конвертации конкретных страниц.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | pages | java.util.List<java.lang.Integer> | Список индексов страниц для конвертации. Должен быть указан для конвертации конкретных страниц. |
|

