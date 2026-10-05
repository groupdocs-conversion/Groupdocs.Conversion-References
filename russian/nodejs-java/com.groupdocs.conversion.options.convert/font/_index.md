---
title: "Шрифт"
second_title: "Справочник API GroupDocs.Conversion для Node.js через Java"
description: "Настройки шрифта"
type: docs
weight: 16
url: /ru/nodejs-java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Настройки шрифта
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | создаёт новый экземпляр Font |
## Методы

| Метод | Описание |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Получает имя семейства шрифта |
| [getSize()](#getSize--) | Получает размер шрифта |
| [isBold()](#isBold--) | Флаг полужирного шрифта |
| [setBold(boolean bold)](#setBold-boolean-) | Устанавливает флаг полужирного шрифта |
| [isItalic()](#isItalic--) | Флаг курсивного шрифта |
| [setItalic(boolean italic)](#setItalic-boolean-) | Устанавливает флаг курсивного шрифта |
| [isUnderline()](#isUnderline--) | Получает подчеркивание шрифта |
| [setUnderline(boolean underline)](#setUnderline-boolean-) | Устанавливает подчеркивание шрифта |
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
| fontFamilyName | java.lang.String | Название шрифта |
| размер | float | Размер шрифта |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Получает имя семейства шрифта

**Returns:**
java.lang.String - название семейства шрифта
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


Флаг полужирного шрифта

**Returns:**
boolean - true, если полужирный
### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Устанавливает флаг полужирного шрифта

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| полужирный | boolean | true, если полужирный |

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
| курсив | boolean | true, если курсив |

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Получает подчеркивание шрифта

**Returns:**
boolean - true, если шрифт подчеркнут
### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Устанавливает подчеркивание шрифта

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| подчёркивание | boolean | Флаг подчеркивания шрифта |

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
