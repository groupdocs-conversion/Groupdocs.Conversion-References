---
title: "Police"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Paramètres de police"
type: docs
weight: 16
url: /fr/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

Paramètres de police

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | crée une nouvelle instance de Police |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | Obtient le nom de la famille de police |
|
|  | [getSize()](#getSize--) | Obtient la taille de la police |
|
|  | [isBold()](#isBold--) | Indicateur gras de la police |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | Définit l'indicateur gras de la police |
|
|  | [isItalic()](#isItalic--) | Indicateur italique de la police |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | Définit le drapeau italique de la police |
|
|  | [isUnderline()](#isUnderline--) | Obtient le soulignement de la police |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | Définit le soulignement de la police |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


crée une nouvelle instance de Police


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Nom de la police |
|
|  | size | float | Taille de la police |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Obtient le nom de la famille de police


**Returns:**
java.lang.String - Nom de la famille de police

### getSize() {#getSize--}
```
public float getSize()
```


Obtient la taille de la police


**Returns:**
float - Taille de la police

### isBold() {#isBold--}
```
public boolean isBold()
```


Indicateur gras de la police


**Returns:**
booléen - vrai si gras

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Définit l'indicateur gras de la police


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | gras | booléen | vrai si gras |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Indicateur italique de la police


**Returns:**
booléen - vrai si italique

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


Définit le drapeau italique de la police


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | italique | booléen | vrai si italique |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Obtient le soulignement de la police


**Returns:**
booléen - vrai si la police est soulignée

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Définit le soulignement de la police


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | souligné | booléen | Drapeau de soulignement de la police |
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
| Paramètre | Type | Description |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
