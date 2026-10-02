---
title: "FontSubstitute"
second_title: "مرجع API لـ GroupDocs.Conversion للـ Java"
description: "يصف الاستبدال للخط المفقود."
type: docs
weight: 12
url: /ar/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

يصف الاستبدال للخط المفقود.

## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | إنشاء زوج استبدال خط جديد. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | اسم الخط الأصلي. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | اسم الخط البديل. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


إنشاء زوج استبدال خط جديد.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | originalFont | java.lang.String | خط من المستند المصدر. |
|
|  | substituteWith | java.lang.String | الخط الذي سيُستخدم لاستبدال originalFont. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


اسم الخط الأصلي.


**Returns:**
java.lang.String - اسم الخط الأصلي.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


اسم الخط البديل.


**Returns:**
java.lang.String - اسم الخط البديل.

