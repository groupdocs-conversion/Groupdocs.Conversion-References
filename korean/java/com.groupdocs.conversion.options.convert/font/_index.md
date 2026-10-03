---
title: "폰트"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "글꼴 설정"
type: docs
weight: 16
url: /ko/java/com.groupdocs.conversion.options.convert/font/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class Font extends ValueObject
```

글꼴 설정

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | 새 Font 인스턴스를 생성합니다 |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFamilyName()](#getFamilyName--) | 폰트 패밀리 이름을 가져옵니다 |
|
|  | [getSize()](#getSize--) | 폰트 크기를 가져옵니다 |
|
|  | [isBold()](#isBold--) | Font 굵게 플래그 |
|
|  | [setBold(boolean bold)](#setBold-boolean-) | Font 굵게 플래그를 설정합니다 |
|
|  | [isItalic()](#isItalic--) | Font 이탤릭 플래그 |
|
|  | [setItalic(boolean italic)](#setItalic-boolean-) | 폰트 이탤릭 플래그를 설정합니다 |
|
|  | [isUnderline()](#isUnderline--) | Font 밑줄을 가져옵니다 |
|
|  | [setUnderline(boolean underline)](#setUnderline-boolean-) | Font 밑줄을 설정합니다 |
|
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


새 Font 인스턴스를 생성합니다


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | fontFamilyName | java.lang.String | Font 이름 |
|
|  | size | float | Font 크기 |
|

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


폰트 패밀리 이름을 가져옵니다


**Returns:**
java.lang.String - Font 패밀리 이름

### getSize() {#getSize--}
```
public float getSize()
```


폰트 크기를 가져옵니다


**Returns:**
float - Font 크기

### isBold() {#isBold--}
```
public boolean isBold()
```


Font 굵게 플래그


**Returns:**
boolean - 굵게인 경우 true

### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


Font 굵게 플래그를 설정합니다


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 굵게 | 불리언 | 굵게인 경우 true |
|

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


Font 이탤릭 플래그


**Returns:**
불리언 - 이탤릭인 경우 true

### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


폰트 이탤릭 플래그를 설정합니다


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 이탤릭 | 불리언 | 이탤릭인 경우 true |
|

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


Font 밑줄을 가져옵니다


**Returns:**
불리언 - 글꼴이 밑줄인 경우 true

### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


Font 밑줄을 설정합니다


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 밑줄 | 불리언 | 글꼴 밑줄 플래그 |
|

### getDefault() {#getDefault--}
```
public static Font getDefault()
```




**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
### clone(float newSize) {#clone-float-}
```
public Font clone(float newSize)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| newSize | float |  |

**Returns:**
[Font](../../com.groupdocs.conversion.options.convert/font)
