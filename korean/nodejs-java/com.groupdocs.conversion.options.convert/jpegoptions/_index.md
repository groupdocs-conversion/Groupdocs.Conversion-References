---
title: "JpegOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "JPEG 파일 형식으로 변환 옵션."
type: docs
weight: 20
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/jpegoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class JpegOptions extends ValueObject implements Serializable
```

JPEG 파일 형식으로 변환 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [JpegOptions()](#JpegOptions--) | 새로운 [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getQuality()](#getQuality--) | 원하는 이미지 품질. |
| [setQuality(int value)](#setQuality-int-) | 원하는 이미지 품질. |
| [getColorMode()](#getColorMode--) | Jpg 색상 모드. |
| [setColorMode(JpgColorModes value)](#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-) | Jpg 색상 모드. |
| [getCompression()](#getCompression--) | Jpg 압축 방식. |
| [setCompression(JpgCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-) | Jpg 압축 방식. |
### JpegOptions() {#JpegOptions--}
```
public JpegOptions()
```


새로운 [JpegOptions](../../com.groupdocs.conversion.options.convert/jpegoptions) 클래스 인스턴스를 초기화합니다.

### getQuality() {#getQuality--}
```
public final int getQuality()
```


원하는 이미지 품질. 값은 0에서 100 사이여야 합니다. 기본값은 100입니다.

**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public final void setQuality(int value)
```


원하는 이미지 품질. 값은 0에서 100 사이여야 합니다. 기본값은 100입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getColorMode() {#getColorMode--}
```
public final JpgColorModes getColorMode()
```


Jpg 색상 모드.

**Returns:**
[JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes)
### setColorMode(JpgColorModes value) {#setColorMode-com.groupdocs.conversion.options.convert.JpgColorModes-}
```
public final void setColorMode(JpgColorModes value)
```


Jpg 색상 모드.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [JpgColorModes](../../com.groupdocs.conversion.options.convert/jpgcolormodes) |  |

### getCompression() {#getCompression--}
```
public final JpgCompressionMethods getCompression()
```


Jpg 압축 방식.

**Returns:**
[JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods)
### setCompression(JpgCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.JpgCompressionMethods-}
```
public final void setCompression(JpgCompressionMethods value)
```


Jpg 압축 방식.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [JpgCompressionMethods](../../com.groupdocs.conversion.options.convert/jpgcompressionmethods) |  |

