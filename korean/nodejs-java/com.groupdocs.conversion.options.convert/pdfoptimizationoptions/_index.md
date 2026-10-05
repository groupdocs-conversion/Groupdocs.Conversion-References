---
title: "PdfOptimizationOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "PDF 최적화 옵션을 정의합니다."
type: docs
weight: 29
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/pdfoptimizationoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptimizationOptions extends ValueObject implements Serializable
```

PDF 최적화 옵션을 정의합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfOptimizationOptions()](#PdfOptimizationOptions--) | 새 인스턴스를 초기화합니다 [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getLinkDuplicateStreams()](#getLinkDuplicateStreams--) | 중복 스트림 연결 |
| [setLinkDuplicateStreams(boolean value)](#setLinkDuplicateStreams-boolean-) | 중복 스트림 연결 |
| [getRemoveUnusedObjects()](#getRemoveUnusedObjects--) | 사용되지 않는 개체 제거 |
| [setRemoveUnusedObjects(boolean value)](#setRemoveUnusedObjects-boolean-) | 사용되지 않는 개체 제거 |
| [getRemoveUnusedStreams()](#getRemoveUnusedStreams--) | 사용되지 않는 스트림 제거 |
| [setRemoveUnusedStreams(boolean value)](#setRemoveUnusedStreams-boolean-) | 사용되지 않는 스트림 제거 |
| [getCompressImages()](#getCompressImages--) | CompressImages가 true로 설정된 경우, 문서의 모든 이미지가 다시 압축됩니다. |
| [setCompressImages(boolean value)](#setCompressImages-boolean-) | CompressImages가 true로 설정된 경우, 문서의 모든 이미지가 다시 압축됩니다. |
| [getImageQuality()](#getImageQuality--) | 100%가 품질 및 이미지 크기가 변하지 않는 경우인 백분율 값. |
| [setImageQuality(int value)](#setImageQuality-int-) | 100%가 품질 및 이미지 크기가 변하지 않는 경우인 백분율 값. |
| [getUnembedFonts()](#getUnembedFonts--) | true로 설정된 경우 글꼴을 포함하지 않게 합니다 |
| [setUnembedFonts(boolean value)](#setUnembedFonts-boolean-) | true로 설정된 경우 글꼴을 포함하지 않게 합니다 |
| [getFontSubsetStrategy()](#getFontSubsetStrategy--) |  |
| [setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)](#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-) | 글꼴 부분집합 전략 설정 |
### PdfOptimizationOptions() {#PdfOptimizationOptions--}
```
public PdfOptimizationOptions()
```


새 인스턴스를 초기화합니다 [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) 클래스.

### getLinkDuplicateStreams() {#getLinkDuplicateStreams--}
```
public final boolean getLinkDuplicateStreams()
```


중복 스트림 연결

**Returns:**
boolean
### setLinkDuplicateStreams(boolean value) {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```


중복 스트림 연결

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getRemoveUnusedObjects() {#getRemoveUnusedObjects--}
```
public final boolean getRemoveUnusedObjects()
```


사용되지 않는 개체 제거

**Returns:**
boolean
### setRemoveUnusedObjects(boolean value) {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```


사용되지 않는 개체 제거

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getRemoveUnusedStreams() {#getRemoveUnusedStreams--}
```
public final boolean getRemoveUnusedStreams()
```


사용되지 않는 스트림 제거

**Returns:**
boolean
### setRemoveUnusedStreams(boolean value) {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```


사용되지 않는 스트림 제거

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getCompressImages() {#getCompressImages--}
```
public final boolean getCompressImages()
```


CompressImages가 true로 설정된 경우, 문서의 모든 이미지가 다시 압축됩니다. 압축은 ImageQuality 속성에 의해 정의됩니다.

**Returns:**
boolean
### setCompressImages(boolean value) {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```


CompressImages가 true로 설정된 경우, 문서의 모든 이미지가 다시 압축됩니다. 압축은 ImageQuality 속성에 의해 정의됩니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getImageQuality() {#getImageQuality--}
```
public final int getImageQuality()
```


값은 백분율이며, 100%는 품질과 이미지 크기가 변하지 않음을 의미합니다. 이미지 크기를 줄이려면 이 속성을 100 이하로 설정하십시오.

**Returns:**
int
### setImageQuality(int value) {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```


값은 백분율이며, 100%는 품질과 이미지 크기가 변하지 않음을 의미합니다. 이미지 크기를 줄이려면 이 속성을 100 이하로 설정하십시오.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getUnembedFonts() {#getUnembedFonts--}
```
public final boolean getUnembedFonts()
```


true로 설정된 경우 글꼴을 포함하지 않게 합니다

**Returns:**
boolean
### setUnembedFonts(boolean value) {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```


true로 설정된 경우 글꼴을 포함하지 않게 합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getFontSubsetStrategy() {#getFontSubsetStrategy--}
```
public PdfFontSubsetStrategy getFontSubsetStrategy()
```




**Returns:**
[PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy)
### setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy) {#setFontSubsetStrategy-com.groupdocs.conversion.options.convert.PdfFontSubsetStrategy-}
```
public void setFontSubsetStrategy(PdfFontSubsetStrategy fontSubsetStrategy)
```


글꼴 부분집합 전략 설정

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontSubsetStrategy | [PdfFontSubsetStrategy](../../com.groupdocs.conversion.options.convert/pdffontsubsetstrategy) |  |

