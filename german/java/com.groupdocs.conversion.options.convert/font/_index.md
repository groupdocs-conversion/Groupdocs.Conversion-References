---
title: "Schriftart"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Schrifteinstellungen"
type: docs
weight: 16
url: /de/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Schrifteinstellungen

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | erstellt eine neue Schriftart-Instanz |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Ruft den Namen der Schriftfamilie ab |
|
|  | [getSize()](#getSize--) | Ruft die Schriftgröße ab |
|
|  | [isBold()](#isBold--) | Fett-Flag der Schriftart |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | Setzt das Fett-Flag der Schriftart |
|
|  | [isItalic()](#isItalic--) | Kursiv-Flag der Schriftart |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | Setzt das Kursiv-Flag der Schriftart |
|
|  | [isUnderline()](#isUnderline--) | Ruft die Unterstreichung der Schriftart ab |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | Setzt die Unterstreichung der Schriftart |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


erstellt eine neue Schriftart-Instanz


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Schriftartname |
|
|  | Größe | float | Schriftgröße |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Ruft den Namen der Schriftfamilie ab


**Returns:**
java.lang.String - Schriftfamilienname

### getSize() {#getSize--}
```
public float getSize()
```


Ruft die Schriftgröße ab


**Returns:**
float - Schriftgröße

### isBold() {#isBold--}
```
public boolean isBold()
```


Fett-Flag der Schriftart


**Returns:**
boolean - wahr, wenn fett

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Setzt das Fett-Flag der Schriftart


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | fett | boolean | wahr, wenn fett |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Kursiv-Flag der Schriftart


**Returns:**
boolean - wahr, wenn kursiv

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Setzt das Kursiv-Flag der Schriftart


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | kursiv | boolean | wahr, wenn kursiv |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Ruft die Unterstreichung der Schriftart ab


**Returns:**
boolean - wahr, wenn Schriftart unterstrichen ist

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Setzt die Unterstreichung der Schriftart


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | unterstrichen | boolean | Schriftunterstreichungs-Flag |
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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
