---
title: "FontSubstitute"
second_title: "Riferimento API di GroupDocs.Conversion per Java"
description: "Descrive la sostituzione per i caratteri mancanti."
type: docs
weight: 12
url: /it/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Descrive la sostituzione per i caratteri mancanti.

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Instanzia una nuova coppia di sostituzione del font. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | Il nome del font originale. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | Il nome del font sostitutivo. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Instanzia una nuova coppia di sostituzione del font.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | originalFont | java.lang.String | Font dal documento sorgente. |
|
|  | substituteWith | java.lang.String | Font che verrà usato per sostituire originalFont. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Il nome del font originale.


**Returns:**
java.lang.String - il nome del font originale.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


Il nome del font sostitutivo.


**Returns:**
java.lang.String - il nome del font sostitutivo.

