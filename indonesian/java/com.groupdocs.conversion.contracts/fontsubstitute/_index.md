---
title: "FontSubstitute"
second_title: "Referensi API GroupDocs.Conversion untuk Java"
description: "Menjelaskan substitusi untuk font yang hilang."
type: docs
weight: 12
url: /id/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Menjelaskan substitusi untuk font yang hilang.

## Metode

| Metode | Deskripsi |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Instansiasi pasangan substitusi font baru. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | Nama font asli. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | Nama font pengganti. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Instansiasi pasangan substitusi font baru.


**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
|  | originalFont | java.lang.String | Font dari dokumen sumber. |
|
|  | substituteWith | java.lang.String | Font yang akan digunakan untuk menggantikan originalFont. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Nama font asli.


**Returns:**
java.lang.String - nama font asli.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


Nama font pengganti.


**Returns:**
java.lang.String - nama font pengganti.

