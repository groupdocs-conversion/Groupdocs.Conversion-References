---
title: "Teckensnitt"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Teckensnittinställningar"
type: docs
weight: 16
url: /sv/nodejs-java/com.groupdocs.conversion.options.convert/font/
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
| [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | skapar ny teckensnittinstans |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Fet teckensnittsfamiljnamn |
| [getSize()](#getSize--) | Hämtar teckensnittsstorlek |
| [isBold()](#isBold--) | Teckensnitt fet flagga |
| [setBold(boolean bold)](#setBold-boolean-) | Ställer in teckensnitt fet flagga |
| [isItalic()](#isItalic--) | Teckensnitt kursiv flagga |
| [setItalic(boolean italic)](#setItalic-boolean-) | Ställer in teckensnitt kursiv flagga |
| [isUnderline()](#isUnderline--) | Hämtar teckensnitt understrykning |
| [setUnderline(boolean underline)](#setUnderline-boolean-) | Ställer in teckensnitt understrykning |
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


skapar ny teckensnittinstans

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Teckensnitt namn |
| size | float | Teckensnittsstorlek |

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


Hämtar teckensnittsstorlek

**Returns:**
float - Teckensnittsstorlek
### isBold() {#isBold--}
```
public boolean isBold()
```


Teckensnitt fet flagga

**Returns:**
boolean - sant om fet
### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Ställer in teckensnitt fet flagga

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fet | boolean | sant om fet |

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Teckensnitt kursiv flagga

**Returns:**
boolean - sant om kursiv
### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Ställer in teckensnitt kursiv flagga

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kursiv | boolean | sant om kursiv |

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Hämtar teckensnitt understrykning

**Returns:**
boolean - sant om teckensnitt är understruket
### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Ställer in teckensnitt understrykning

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| understrykning | boolean | Teckensnitt understrykning flagga |

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
