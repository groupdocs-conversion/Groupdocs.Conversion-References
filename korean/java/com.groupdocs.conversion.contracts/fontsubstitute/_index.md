---
title: "FontSubstitute"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "누락된 글꼴에 대한 대체를 설명합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.conversion.contracts/fontsubstitute/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class FontSubstitute extends ValueObject implements Serializable
```

누락된 글꼴에 대한 대체를 설명합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | 새 폰트 대체 쌍을 인스턴스화합니다. |
|
|  | [getOriginalFontName()](#getOriginalFontName--) | 원본 폰트 이름. |
|
|  | [getSubstituteFontName()](#getSubstituteFontName--) | 대체 폰트 이름. |
|
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


새 폰트 대체 쌍을 인스턴스화합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | originalFont | java.lang.String | 소스 문서의 글꼴. |
|
|  | substituteWith | java.lang.String | originalFont을 대체하는 데 사용될 글꼴. |
|

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair

### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


원본 폰트 이름.


**Returns:**
java.lang.String - 원본 글꼴 이름.

### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


대체 폰트 이름.


**Returns:**
java.lang.String - 대체 글꼴 이름.

