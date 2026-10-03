---
title: "FontSubstitute"
second_title: "Java için GroupDocs.Conversion API Referansı"
description: "Eksik yazı tipi için ikameyi açıklar."
type: docs
weight: 12
url: /tr/java/com.groupdocs.conversion.contracts/fontsubstitute/
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
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | Yeni bir font ikame çifti oluşturun. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | Orijinal font adı. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | İkame font adı. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


Yeni bir font ikame çifti oluşturun.


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | originalFont | java.lang.String | Kaynak belgeden font. |
|
|  | substituteWith | java.lang.String | originalFont yerine kullanılacak font. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


Orijinal font adı.


**Returns:**
java.lang.String - orijinal font adı.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


İkame font adı.


**Returns:**
java.lang.String - ikame font adı.

