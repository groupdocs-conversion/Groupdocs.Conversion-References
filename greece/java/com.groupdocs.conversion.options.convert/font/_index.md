---
title: "Γραμματοσειρά"
second_title: "GroupDocs.Conversion για Java API Reference"
description: "Ρυθμίσεις γραμματοσειράς"
type: docs
weight: 16
url: /el/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Ρυθμίσεις γραμματοσειράς

## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | Δημιουργεί νέο αντικείμενο Font |
|
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Λαμβάνει το όνομα οικογένειας γραμματοσειράς |
|
|  | [getSize()](#getSize--) | Λαμβάνει το μέγεθος της γραμματοσειράς |
|
|  | [isBold()](#isBold--) | Σημαία έντονης γραμματοσειράς |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | Ορίζει τη σημαία έντονης γραμματοσειράς |
|
|  | [isItalic()](#isItalic--) | Σημαία πλάγιας γραμματοσειράς |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | Ορίζει τη σημαία πλάγιας γραφής της γραμματοσειράς |
|
|  | [isUnderline()](#isUnderline--) | Λαμβάνει την υπογράμμιση της γραμματοσειράς |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | Ορίζει την υπογράμμιση της γραμματοσειράς |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


Δημιουργεί νέο αντικείμενο Font


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Όνομα γραμματοσειράς |
|
|  | μέγεθος | float | Μέγεθος γραμματοσειράς |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Λαμβάνει το όνομα οικογένειας γραμματοσειράς


**Returns:**
java.lang.String - Όνομα οικογένειας γραμματοσειράς

### getSize() {#getSize--}
```
public float getSize()
```


Λαμβάνει το μέγεθος της γραμματοσειράς


**Returns:**
float - Μέγεθος γραμματοσειράς

### isBold() {#isBold--}
```
public boolean isBold()
```


Σημαία έντονης γραμματοσειράς


**Returns:**
boolean - αληθές αν είναι έντονη

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Ορίζει τη σημαία έντονης γραμματοσειράς


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | έντονη | boolean | αληθές αν είναι έντονη |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Σημαία πλάγιας γραμματοσειράς


**Returns:**
boolean - αληθές αν είναι πλάγια

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Ορίζει τη σημαία πλάγιας γραφής της γραμματοσειράς


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | πλάγια | boolean | αληθές αν είναι πλάγια |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Λαμβάνει την υπογράμμιση της γραμματοσειράς


**Returns:**
boolean - αληθές αν η γραμματοσειρά είναι υπογραμμισμένη

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Ορίζει την υπογράμμιση της γραμματοσειράς


**Parameters:**
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
|  | υπογράμμιση | boolean | Σημαία υπογράμμισης γραμματοσειράς |
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
| Parameter | Type | Περιγραφή |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
