---
title: "Font"
second_title: "GroupDocs.Conversion för Java API-referens"
description: "Teckensnittinställningar"
type: docs
weight: 16
url: /sv/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Teckensnittinställningar

## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | skapar en ny Font-instans |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Fet teckensnittsfamiljnamn |
|
|  | [getSize()](#getSize--) | Hämtar teckenstorlek |
|
|  | [isBold()](#isBold--) | Fet flagga för Font |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | Ställer in fet flagga för Font |
|
|  | [isItalic()](#isItalic--) | Kursiv flagga för Font |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | Ställer in kursiv flagga för font |
|
|  | [isUnderline()](#isUnderline--) | Hämtar Font understrykning |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | Ställer in Font understrykning |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


skapar en ny Font-instans


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Fontnamn |
|
|  | storlek | float | Fontstorlek |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Fet teckensnittsfamiljnamn


**Returns:**
java.lang.String - Teckensnittsfamiljnamn

### getSize() {#getSize--}
```
public float getSize()
```


Hämtar teckenstorlek


**Returns:**
float - Fontstorlek

### isBold() {#isBold--}
```
public boolean isBold()
```


Fet flagga för Font


**Returns:**
boolean - sant om fet

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Ställer in fet flagga för Font


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | fet | boolean | sant om fet |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Kursiv flagga för Font


**Returns:**
boolean - sant om kursiv

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Ställer in kursiv flagga för font


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | kursiv | boolean | sant om kursiv |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Hämtar Font understrykning


**Returns:**
boolean - sant om Font är understruken

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Ställer in Font understrykning


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | understrykning | boolean | Flagga för Font understrykning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
