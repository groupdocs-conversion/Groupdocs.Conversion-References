---
title: "FontSubstitute"
second_title: "GroupDocs.Conversion för Node.js via Java API-referens"
description: "Beskriver ersättning för saknat teckensnitt."
type: docs
weight: 12
url: /sv/nodejs-java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Beskriver ersättning för saknat teckensnitt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Instansiera nytt teckensnittssubstitutionspar. |
| [getOriginalFontName()](#getOriginalFontName--) | Det ursprungliga teckensnittets namn. |
| [getSubstituteFontName()](#getSubstituteFontName--) | Det ersättande teckensnittets namn. |
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Instansiera nytt teckensnittssubstitutionspar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| originalFont | java.lang.String | Teckensnitt från källdokumentet. |
| substituteWith | java.lang.String | Teckensnitt som kommer att användas för att ersätta originalFont. |

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Det ursprungliga teckensnittets namn.

**Returns:**
java.lang.String - det ursprungliga teckensnittets namn.
### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


Det ersättande teckensnittets namn.

**Returns:**
java.lang.String - det ersättande teckensnittets namn.
