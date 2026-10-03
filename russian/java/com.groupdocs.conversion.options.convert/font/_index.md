---
title: "Шрифт"
second_title: "Справочник API GroupDocs.Conversion for Java"
description: "Настройки шрифтов"
type: docs
weight: 16
url: /ru/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Настройки шрифтов

## Конструкторы

| Конструктор | Описание |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | создаёт новый экземпляр Font |
|
## Методы

| Метод | Описание |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Получает название семейства шрифта |
|
|  | [getSize()](#getSize--) | Получает размер шрифта |
|
|  | [isBold()](#isBold--) | Флаг жирного шрифта |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | Устанавливает флаг жирного шрифта |
|
|  | [isItalic()](#isItalic--) | Флаг курсивного шрифта |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | Устанавливает флаг курсивного шрифта |
|
|  | [isUnderline()](#isUnderline--) | Получает подчеркивание шрифта |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | Устанавливает подчеркивание шрифта |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


создаёт новый экземпляр Font


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Имя шрифта |
|
|  | size | float | Размер шрифта |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Получает название семейства шрифта


**Returns:**
java.lang.String - имя семейства шрифта

### getSize() {#getSize--}
```
public float getSize()
```


Получает размер шрифта


**Returns:**
float - размер шрифта

### isBold() {#isBold--}
```
public boolean isBold()
```


Флаг жирного шрифта


**Returns:**
boolean - true, если жирный

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Устанавливает флаг жирного шрифта


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | жирный | логический | true, если жирный |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Флаг курсивного шрифта


**Returns:**
boolean - true, если курсив

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Устанавливает флаг курсивного шрифта


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | курсив | логический | true, если курсив |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Получает подчеркивание шрифта


**Returns:**
boolean - true, если шрифт подчеркивается

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Устанавливает подчеркивание шрифта


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
|  | подчеркивание | логический | Флаг подчеркивания шрифта |
|

### getDefault() {#getDefault--}
```
public static Font getDefault()
```




**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
### clone(float newSize) {#clone-float-}
```
public Font clone(float newSize)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
