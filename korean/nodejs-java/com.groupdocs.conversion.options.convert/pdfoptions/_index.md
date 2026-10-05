---
title: "PdfOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "PDF 파일 형식으로 변환 옵션."
type: docs
weight: 30
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/pdfoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfOptions extends ValueObject implements Serializable
```

PDF 파일 형식으로 변환 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfOptions()](#PdfOptions--) | ctor |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPdfFormat()](#getPdfFormat--) | 변환된 문서의 pdf 형식을 설정합니다. |
| [setPdfFormat(PdfFormats value)](#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-) | 변환된 문서의 pdf 형식을 설정합니다. |
| [getRemovePdfACompliance()](#getRemovePdfACompliance--) | Pdf-A 준수를 제거합니다. |
| [setRemovePdfACompliance(boolean value)](#setRemovePdfACompliance-boolean-) | Pdf-A 준수를 제거합니다. |
| [getZoom()](#getZoom--) | 줌 레벨을 백분율로 지정합니다. |
| [setZoom(int value)](#setZoom-int-) | 줌 레벨을 백분율로 지정합니다. |
| [getLinearize()](#getLinearize--) | 웹용 PDF 문서를 선형화합니다. |
| [setLinearize(boolean value)](#setLinearize-boolean-) | 웹용 PDF 문서를 선형화합니다. |
| [getOptimizationOptions()](#getOptimizationOptions--) | PDF 최적화 옵션 |
| [setOptimizationOptions(PdfOptimizationOptions value)](#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-) | PDF 최적화 옵션 |
| [getGrayscale()](#getGrayscale--) | PDF를 RGB 색공간에서 그레이스케일로 변환합니다 |
| [setGrayscale(boolean value)](#setGrayscale-boolean-) | PDF를 RGB 색공간에서 그레이스케일로 변환합니다 |
| [getFormattingOptions()](#getFormattingOptions--) | PDF 서식 옵션 |
| [setFormattingOptions(PdfFormattingOptions value)](#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-) | PDF 서식 옵션 |
| [getDocumentInfo()](#getDocumentInfo--) | PDF 문서의 메타 정보. |
| [setDocumentInfo(PdfDocumentInfo documentInfo)](#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-) |  |
### PdfOptions() {#PdfOptions--}
```
public PdfOptions()
```


ctor

### getPdfFormat() {#getPdfFormat--}
```
public final PdfFormats getPdfFormat()
```


변환된 문서의 pdf 형식을 설정합니다.

**Returns:**
[PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats)
### setPdfFormat(PdfFormats value) {#setPdfFormat-com.groupdocs.conversion.options.convert.PdfFormats-}
```
public final void setPdfFormat(PdfFormats value)
```


변환된 문서의 pdf 형식을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PdfFormats](../../com.groupdocs.conversion.options.convert/pdfformats) |  |

### getRemovePdfACompliance() {#getRemovePdfACompliance--}
```
public final boolean getRemovePdfACompliance()
```


Pdf-A 준수를 제거합니다.

**Returns:**
boolean
### setRemovePdfACompliance(boolean value) {#setRemovePdfACompliance-boolean-}
```
public final void setRemovePdfACompliance(boolean value)
```


Pdf-A 준수를 제거합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


줌 레벨을 백분율로 지정합니다. 기본값은 100입니다.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


줌 레벨을 백분율로 지정합니다. 기본값은 100입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getLinearize() {#getLinearize--}
```
public final boolean getLinearize()
```


웹용 PDF 문서를 선형화합니다.

**Returns:**
boolean
### setLinearize(boolean value) {#setLinearize-boolean-}
```
public final void setLinearize(boolean value)
```


웹용 PDF 문서를 선형화합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getOptimizationOptions() {#getOptimizationOptions--}
```
public final PdfOptimizationOptions getOptimizationOptions()
```


PDF 최적화 옵션

**Returns:**
[PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions)
### setOptimizationOptions(PdfOptimizationOptions value) {#setOptimizationOptions-com.groupdocs.conversion.options.convert.PdfOptimizationOptions-}
```
public final void setOptimizationOptions(PdfOptimizationOptions value)
```


PDF 최적화 옵션

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PdfOptimizationOptions](../../com.groupdocs.conversion.options.convert/pdfoptimizationoptions) |  |

### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


PDF를 RGB 색공간에서 그레이스케일로 변환합니다

**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


PDF를 RGB 색공간에서 그레이스케일로 변환합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getFormattingOptions() {#getFormattingOptions--}
```
public final PdfFormattingOptions getFormattingOptions()
```


PDF 서식 옵션

**Returns:**
[PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions)
### setFormattingOptions(PdfFormattingOptions value) {#setFormattingOptions-com.groupdocs.conversion.options.convert.PdfFormattingOptions-}
```
public final void setFormattingOptions(PdfFormattingOptions value)
```


PDF 서식 옵션

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PdfFormattingOptions](../../com.groupdocs.conversion.options.convert/pdfformattingoptions) |  |

### getDocumentInfo() {#getDocumentInfo--}
```
public PdfDocumentInfo getDocumentInfo()
```


PDF 문서의 메타 정보.

**Returns:**
[PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo)
### setDocumentInfo(PdfDocumentInfo documentInfo) {#setDocumentInfo-com.groupdocs.conversion.options.convert.PdfDocumentInfo-}
```
public void setDocumentInfo(PdfDocumentInfo documentInfo)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| documentInfo | [PdfDocumentInfo](../../com.groupdocs.conversion.options.convert/pdfdocumentinfo) |  |

