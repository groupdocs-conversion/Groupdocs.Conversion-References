---
title: "TiffOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "TIFF 파일 형식으로 변환하기 위한 옵션."
type: docs
weight: 42
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/tiffoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class TiffOptions extends ValueObject implements Serializable
```

TIFF 파일 형식으로 변환하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | ctor |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCompression()](#getCompression--) | Tiff 압축을 설정합니다. |
| [setCompression(TiffCompressionMethods value)](#setCompression-com.groupdocs.conversion.options.convert.TiffCompressionMethods-) | Tiff 압축을 설정합니다. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


ctor

### getCompression() {#getCompression--}
```
public final TiffCompressionMethods getCompression()
```


Tiff 압축을 설정합니다.

**Returns:**
[TiffCompressionMethods](../../com.groupdocs.conversion.options.convert/tiffcompressionmethods)
### setCompression(TiffCompressionMethods value) {#setCompression-com.groupdocs.conversion.options.convert.TiffCompressionMethods-}
```
public final void setCompression(TiffCompressionMethods value)
```


Tiff 압축을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [TiffCompressionMethods](../../com.groupdocs.conversion.options.convert/tiffcompressionmethods) |  |

