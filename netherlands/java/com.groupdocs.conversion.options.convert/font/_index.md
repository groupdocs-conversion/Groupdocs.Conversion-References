---
title: "Lettertype"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Lettertype-instellingen"
type: docs
weight: 16
url: /nl/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Lettertype-instellingen

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | maakt een nieuw Lettertype-exemplaar |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Haalt de naam van de lettertypefamilie op. |
|
|  | [getSize()](#getSize--) | Haalt de lettergrootte op. |
|
|  | [isBold()](#isBold--) | Vetvlag van lettertype |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | Stelt de vetvlag van het lettertype in. |
|
|  | [isItalic()](#isItalic--) | Cursiefvlag van het lettertype |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | Stelt font cursief vlag in |
|
|  | [isUnderline()](#isUnderline--) | Haalt Font onderstreping op |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | Stelt Font onderstreping in |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


maakt een nieuw Lettertype-exemplaar


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Font naam |
|
|  | size | float | Font grootte |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Haalt de naam van de lettertypefamilie op.


**Returns:**
java.lang.String - Font familie naam

### getSize() {#getSize--}
```
public float getSize()
```


Haalt de lettergrootte op.


**Returns:**
float - Font grootte

### isBold() {#isBold--}
```
public boolean isBold()
```


Vetvlag van lettertype


**Returns:**
boolean - true als vet

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Stelt de vetvlag van het lettertype in.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | vet | boolean | true als vet |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Cursiefvlag van het lettertype


**Returns:**
boolean - true als cursief

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Stelt font cursief vlag in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | cursief | boolean | true als cursief |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Haalt Font onderstreping op


**Returns:**
boolean - true als Font onderstreept is

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Stelt Font onderstreping in


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | onderstrepen | boolean | Font onderstreept vlag |
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
