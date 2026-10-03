---
title: "RecognizedImage"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Представляет текст, извлечённый из изображения в результате процесса распознавания."
type: docs
weight: 10
url: /ru/java/com.groupdocs.conversion.integration.ocr/recognizedimage/
---
**Inheritance:**
java.lang.Object
```
public class RecognizedImage
```

Представляет текст, извлечённый из изображения в результате процесса распознавания.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [RecognizedImage(List<TextLine> lines)](#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--) | Инициализирует новый экземпляр класса, используя набор распознанных строк. |
|
## Поля

| Поле | Описание |
| --- | --- |
|  | [EMPTY](#EMPTY) | Пустое распознанное изображение |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getLines()](#getLines--) | Получает строки текста с их фрагментами, распознанные в документе. |
|
|  | [getText()](#getText--) | Получает текстовый эквивалент структурированного текста |
|
### RecognizedImage(List<TextLine> lines) {#RecognizedImage-java.util.List-com.groupdocs.conversion.integration.ocr.TextLine--}
```
public RecognizedImage(List<TextLine> lines)
```


Инициализирует новый экземпляр класса, используя набор распознанных строк.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | строки | java.util.List<com.groupdocs.conversion.integration.ocr.TextLine> | IEnumerable (например, список или массив) распознанных строк |
|

### EMPTY {#EMPTY}
```
public static final RecognizedImage EMPTY
```


Пустое распознанное изображение


### getLines() {#getLines--}
```
public TextLine[] getLines()
```


Получает строки текста с их фрагментами, распознанные в документе.


**Returns:**
com.groupdocs.conversion.integration.ocr.TextLine[]
### getText() {#getText--}
```
public String getText()
```


Получает текстовый эквивалент структурированного текста


**Returns:**
java.lang.String
