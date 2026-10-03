---
title: "DiagramConvertOptions"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Параметры конвертации в тип файла Diagram."
type: docs
weight: 13
url: /ru/java/com.groupdocs.conversion.options.convert/diagramconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class DiagramConvertOptions extends CommonConvertOptions<DiagramFileType>
```

Параметры конвертации в тип файла Diagram.

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [DiagramConvertOptions()](#DiagramConvertOptions--) | Инициализирует новый экземпляр класса. |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [isAutoFitPageToDrawingContent()](#isAutoFitPageToDrawingContent--) | Определяет, нужно ли увеличивать страницу, чтобы вместить содержимое рисунка, или нет |
|
|  | [setAutoFitPageToDrawingContent(boolean autoFitPageToDrawingContent)](#setAutoFitPageToDrawingContent-boolean-) | Устанавливает флаг необходимости увеличения страницы |
|
### DiagramConvertOptions() {#DiagramConvertOptions--}
```
public DiagramConvertOptions()
```


Инициализирует новый экземпляр класса.


### isAutoFitPageToDrawingContent() {#isAutoFitPageToDrawingContent--}
```
public boolean isAutoFitPageToDrawingContent()
```


Определяет, нужно ли увеличивать страницу, чтобы вместить содержимое рисунка, или нет


**Returns:**
boolean — флаг необходимости увеличения страницы

### setAutoFitPageToDrawingContent(boolean autoFitPageToDrawingContent) {#setAutoFitPageToDrawingContent-boolean-}
```
public void setAutoFitPageToDrawingContent(boolean autoFitPageToDrawingContent)
```


Устанавливает флаг необходимости увеличения страницы


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | autoFitPageToDrawingContent | логический | флаг необходимости увеличения страницы |
|

