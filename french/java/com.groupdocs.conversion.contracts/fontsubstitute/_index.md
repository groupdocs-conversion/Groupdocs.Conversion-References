---
title: "FontSubstitute"
second_title: "Référence API GroupDocs.Conversion pour Java"
description: "Décrit la substitution pour une police manquante."
type: docs
weight: 12
url: /fr/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Décrit la substitution pour une police manquante.

## Méthodes

| Méthode | Description |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Instancier une nouvelle paire de substitution de police. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | Le nom de police original. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | Le nom de police de substitution. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Instancier une nouvelle paire de substitution de police.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | originalFont | java.lang.String | Police du document source. |
|
|  | substituteWith | java.lang.String | Police qui sera utilisée pour remplacer originalFont. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Le nom de police original.


**Returns:**
java.lang.String - le nom de police original.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


Le nom de police de substitution.


**Returns:**
java.lang.String - le nom de police de substitution.

