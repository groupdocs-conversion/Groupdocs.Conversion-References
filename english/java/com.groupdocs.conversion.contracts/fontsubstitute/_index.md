---
title: FontSubstitute
second_title: GroupDocs.Conversion for Node.js via Java API Reference
description: Describes substitution for missing font.
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Describes substitution for missing font.
## Methods

| Method | Description |
| --- | --- |
| [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Instantiate new font substitution pair. |
| [getOriginalFontName()](#getOriginalFontName--) | The original font name. |
| [getSubstituteFontName()](#getSubstituteFontName--) | The substitute font name. |
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Instantiate new font substitution pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| originalFont | java.lang.String | Font from the source document. |
| substituteWith | java.lang.String | Font which will be used to replace originalFont. |

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


The original font name.

**Returns:**
java.lang.String - the original font name.
### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


The substitute font name.

**Returns:**
java.lang.String - the substitute font name.
