---
title: "FontSubstitute"
second_title: "GroupDocs.Conversion für Java API-Referenz"
description: "Beschreibt den Ersatz für fehlende Schriftart."
type: docs
weight: 12
url: /de/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Beschreibt den Ersatz für fehlende Schriftart.

## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Instanziiere neues Schriftart-Substitutionspaar. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | Der ursprüngliche Schriftartname. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | Der Ersatzschriftartname. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Instanziiere neues Schriftart-Substitutionspaar.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | originalFont | java.lang.String | Schriftart aus dem Quelldokument. |
|
|  | substituteWith | java.lang.String | Schriftart, die verwendet wird, um originalFont zu ersetzen. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Der ursprüngliche Schriftartname.


**Returns:**
java.lang.String - der ursprüngliche Schriftartname.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


Der Ersatzschriftartname.


**Returns:**
java.lang.String - der Ersatzschriftartname.

