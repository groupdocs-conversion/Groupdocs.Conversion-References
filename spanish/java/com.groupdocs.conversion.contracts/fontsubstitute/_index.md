---
title: "FontSubstitute"
second_title: "Referencia de API de GroupDocs.Conversion for Java"
description: "Describe la sustitución para una fuente faltante."
type: docs
weight: 12
url: /es/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Describe la sustitución para una fuente faltante.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Instanciar nuevo par de sustitución de fuentes. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | El nombre de la fuente original. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | El nombre de la fuente sustituta. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Instanciar nuevo par de sustitución de fuentes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | originalFont | java.lang.String | Fuente del documento fuente. |
|
|  | substituteWith | java.lang.String | Fuente que se usará para reemplazar originalFont. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


El nombre de la fuente original.


**Returns:**
java.lang.String - el nombre de la fuente original.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


El nombre de la fuente sustituta.


**Returns:**
java.lang.String - el nombre de la fuente sustituta.

