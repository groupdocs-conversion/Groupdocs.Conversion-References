---
title: "폰트"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "글꼴 설정"
type: docs
weight: 16
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/font/
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
| [Font(String fontFamilyName, float size)](#Font-java.lang.String-float-) | 새로운 Font 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | 폰트 패밀리 이름을 가져옵니다. |
| [getSize()](#getSize--) | 폰트 크기를 가져옵니다. |
| [isBold()](#isBold--) | 폰트 굵게 플래그 |
| [setBold(boolean bold)](#setBold-boolean-) | 폰트 굵게 플래그를 설정합니다. |
| [isItalic()](#isItalic--) | 폰트 이탤릭 플래그 |
| [setItalic(boolean italic)](#setItalic-boolean-) | 글꼴 이탤릭 플래그를 설정합니다 |
| [isUnderline()](#isUnderline--) | 글꼴 밑줄을 가져옵니다 |
| [setUnderline(boolean underline)](#setUnderline-boolean-) | 글꼴 밑줄을 설정합니다 |
| [getDefault()](#getDefault--) |  |
| [clone(float newSize)](#clone-float-) |  |
### Font(String fontFamilyName, float size) {#Font-java.lang.String-float-}
```
public Font(String fontFamilyName, float size)
```


새로운 Font 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontFamilyName | java.lang.String | 글꼴 이름 |
| 크기 | float | 글꼴 크기 |

### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


폰트 패밀리 이름을 가져옵니다.

**Returns:**
java.lang.String - 글꼴 패밀리 이름
### getSize() {#getSize--}
```
public float getSize()
```


폰트 크기를 가져옵니다.

**Returns:**
float - 글꼴 크기
### isBold() {#isBold--}
```
public boolean isBold()
```


폰트 굵게 플래그

**Returns:**
boolean - 볼드인 경우 true
### setBold(boolean bold) {#setBold-boolean-}
```
public void setBold(boolean bold)
```


폰트 굵게 플래그를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 볼드 | boolean | 볼드인 경우 true |

### isItalic() {#isItalic--}
```
public boolean isItalic()
```


폰트 이탤릭 플래그

**Returns:**
boolean - 이탤릭인 경우 true
### setItalic(boolean italic) {#setItalic-boolean-}
```
public void setItalic(boolean italic)
```


글꼴 이탤릭 플래그를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이탤릭 | boolean | 이탤릭인 경우 true |

### isUnderline() {#isUnderline--}
```
public boolean isUnderline()
```


글꼴 밑줄을 가져옵니다

**Returns:**
boolean - 글꼴이 밑줄인 경우 true
### setUnderline(boolean underline) {#setUnderline-boolean-}
```
public void setUnderline(boolean underline)
```


글꼴 밑줄을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 밑줄 | boolean | 글꼴 밑줄 플래그 |

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
