---
title: "FontSubstitute"
second_title: "Node.js için GroupDocs.Conversion, Java üzerinden API Referansı"
description: "Eksik yazı tipi için ikameyi açıklar."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

Eksik yazı tipi için ikameyi açıklar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Yeni bir yazı tipi ikamesi çifti oluştur. |
| [getOriginalFontName()](#getOriginalFontName--) | Orijinal yazı tipi adı. |
| [getSubstituteFontName()](#getSubstituteFontName--) | İkame yazı tipi adı. |
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Yeni bir yazı tipi ikamesi çifti oluştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| originalFont | java.lang.String | Kaynak belgeden gelen yazı tipi. |
| substituteWith | java.lang.String | originalFont öğesini değiştirmek için kullanılacak yazı tipi. |

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Orijinal yazı tipi adı.

**Returns:**
java.lang.String - orijinal yazı tipi adı.
### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


İkame yazı tipi adı.

**Returns:**
java.lang.String - ikame yazı tipi adı.
