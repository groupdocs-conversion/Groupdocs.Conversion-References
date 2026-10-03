---
title: "TextFragment"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Представляет часть распознанного текста, слова, символа и т.д., извлечённого OCR‑движком."
type: docs
weight: 11
url: /ru/java/com.groupdocs.conversion.integration.ocr/textfragment/
---
**Inheritance:**
java.lang.Object
```
public class TextFragment
```

Представляет часть распознанного текста (слово, символ и т.д.), извлечённую OCR‑движком.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [TextFragment(String text, Rectangle rectangle)](#TextFragment-java.lang.String-java.awt.Rectangle-) | Инициализирует новый экземпляр распознанного текстового фрагмента. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getText()](#getText--) | Получает текстовое содержимое распознанного текстового фрагмента. |
|
|  | [getRectangle()](#getRectangle--) | Получает ограничивающий прямоугольник распознанного текстового фрагмента. |
|
### TextFragment(String text, Rectangle rectangle) {#TextFragment-java.lang.String-java.awt.Rectangle-}
```
public TextFragment(String text, Rectangle rectangle)
```


Инициализирует новый экземпляр распознанного текстового фрагмента.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | текст | java.lang.String | текстовое содержимое распознанного текстового фрагмента |
|
|  | прямоугольник | java.awt.Rectangle | ограничивающий прямоугольник распознанного текстового фрагмента |
|

### getText() {#getText--}
```
public String getText()
```


Получает текстовое содержимое распознанного текстового фрагмента.


**Returns:**
java.lang.String
### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает ограничивающий прямоугольник распознанного текстового фрагмента.


**Returns:**
[Rectangle](../../java.awt/rectangle)
