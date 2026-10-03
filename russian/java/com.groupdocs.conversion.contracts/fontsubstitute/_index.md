---
title: "FontSubstitute"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Описывает замену отсутствующего шрифта."
type: docs
weight: 12
url: /ru/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Описывает замену отсутствующего шрифта.

## Методы

| Метод | Описание |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Создать новую пару замены шрифтов. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | Исходное название шрифта. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | Название заменяющего шрифта. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Создать новую пару замены шрифтов.


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | originalFont | java.lang.String | Шрифт из исходного документа. |
|
|  | substituteWith | java.lang.String | Шрифт, который будет использоваться для замены originalFont. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Исходное название шрифта.


**Returns:**
java.lang.String - исходное название шрифта.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


Название заменяющего шрифта.


**Returns:**
java.lang.String - название заменяющего шрифта.

