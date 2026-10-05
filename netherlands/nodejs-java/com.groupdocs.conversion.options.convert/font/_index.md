---
title: "Lettertype"
second_title: "GroupDocs.Conversion for Node.js via Java API-referentie"
description: "Lettertype‑instellingen"
type: docs
weight: 16
url: /nl/nodejs-java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Lettertype‑instellingen
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | maakt een nieuwe Lettertype‑instantie aan |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Haalt de naam van de lettertypefamilie op |
| [getSize()](#getSize--) | Haalt lettergrootte op |
| [isBold()](#isBold--) | Vetlettertype vlag |
| [setBold(boolean bold)](#setBold-boolean-) | Stelt vetlettertype vlag in |
| [isItalic()](#isItalic--) | Cursieflettertype vlag |
| [setItalic(boolean italic)](#setItalic-boolean-) | Stelt cursieflettertype vlag in |
| [isUnderline()](#isUnderline--) | Haalt onderstreping van lettertype op |
| [setUnderline(boolean underline)](#setUnderline-boolean-) | Stelt onderstreping van lettertype in |
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


maakt een nieuwe Lettertype‑instantie aan

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fontFamilyName | java.lang.String | Lettertype naam |
| size | float | Lettergrootte |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Haalt de naam van de lettertypefamilie op

**Returns:**
java.lang.String - Lettertypefamilienaam
### getSize() {#getSize--}
```
public float getSize()
```


Haalt lettergrootte op

**Returns:**
float - Lettergrootte
### isBold() {#isBold--}
```
public boolean isBold()
```


Vetlettertype vlag

**Returns:**
boolean - true als vet
### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Stelt vetlettertype vlag in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| vet | boolean | true als vet |

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Cursieflettertype vlag

**Returns:**
boolean - true als cursief
### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Stelt cursieflettertype vlag in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cursief | boolean | true als cursief |

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Haalt onderstreping van lettertype op

**Returns:**
boolean - true als lettertype onderstreept
### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Stelt onderstreping van lettertype in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| onderstrepen | boolean | Lettertype onderstrepingsvlag |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
