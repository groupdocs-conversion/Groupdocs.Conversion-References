---
title: "TextLine"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Представляет текст, извлечённый из изображения в результате процесса распознавания."
type: docs
weight: 12
url: /ru/java/com.groupdocs.conversion.integration.ocr/textline/
---
**Inheritance:**
java.lang.Object
```
public class TextLine
```

Представляет текст, извлечённый из изображения в результате процесса распознавания.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TextLine(List<TextFragment> fragments)](#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--) | Инициализирует новый экземпляр строки текста, извлечённой OCR‑движком из изображения. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFragments()](#getFragments--) | Получает массив текстовых фрагментов, таких как символы и слова, распознанных в строке. |
|
### TextLine(List<TextFragment> fragments) {#TextLine-java.util.List-com.groupdocs.conversion.integration.ocr.TextFragment--}
```
public TextLine(List<TextFragment> fragments)
```


Инициализирует новый экземпляр строки текста, извлечённой OCR‑движком из изображения.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | фрагменты | java.util.List<com.groupdocs.conversion.integration.ocr.TextFragment> | начальный набор текстовых фрагментов |
|

### getFragments() {#getFragments--}
```
public TextFragment[] getFragments()
```


Получает массив текстовых фрагментов, таких как символы и слова, распознанных в строке.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextFragment[]
