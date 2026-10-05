---
title: "FontSubstitute"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "누락된 글꼴에 대한 대체를 설명합니다."
type: docs
weight: 12
url: /ko/nodejs-java/com.groupdocs.conversion.contracts/fontsubstitute/
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
| [create(String originalFont, String substituteWith)](#create-java.lang.String-java.lang.String-) | 새 폰트 대체 쌍을 인스턴스화합니다. |
| [getOriginalFontName()](#getOriginalFontName--) | 원본 폰트 이름. |
| [getSubstituteFontName()](#getSubstituteFontName--) | 대체 폰트 이름. |
### create(String originalFont, String substituteWith) {#create-java.lang.String-java.lang.String-}
```
public static FontSubstitute create(String originalFont, String substituteWith)
```


새 폰트 대체 쌍을 인스턴스화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| originalFont | java.lang.String | 소스 문서의 폰트. |
| substituteWith | java.lang.String | originalFont를 교체하는 데 사용될 폰트. |

**Returns:**
[FontSubstitute](../../com.groupdocs.conversion.contracts/fontsubstitute) - substitution pair
### getOriginalFontName() {#getOriginalFontName--}
```
public String getOriginalFontName()
```


원본 폰트 이름.

**Returns:**
java.lang.String - 원본 폰트 이름.
### getSubstituteFontName() {#getSubstituteFontName--}
```
public String getSubstituteFontName()
```


대체 폰트 이름.

**Returns:**
java.lang.String - 대체 폰트 이름.
