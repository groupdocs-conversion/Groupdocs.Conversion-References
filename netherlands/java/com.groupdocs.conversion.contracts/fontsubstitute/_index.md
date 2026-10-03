---
title: "FontSubstitute"
second_title: "GroupDocs.Conversion voor Java API-referentie"
description: "Beschrijft vervanging voor ontbrekend lettertype."
type: docs
weight: 12
url: /nl/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Beschrijft vervanging voor ontbrekend lettertype.

## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Instantieer nieuw lettertype substitutie‑paar. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | De oorspronkelijke lettertype‑naam. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | De vervangende lettertype‑naam. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Instantieer nieuw lettertype substitutie‑paar.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | originalFont | java.lang.String | Lettertype van het bron‑document. |
|
|  | substituteWith | java.lang.String | Lettertype dat zal worden gebruikt om originalFont te vervangen. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


De oorspronkelijke lettertype‑naam.


**Returns:**
java.lang.String - de oorspronkelijke lettertype‑naam.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


De vervangende lettertype‑naam.


**Returns:**
java.lang.String - de vervangende lettertype‑naam.

