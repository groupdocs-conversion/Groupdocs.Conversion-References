---
title: "WordProcessingConvertOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "WordProcessing 파일 형식으로 변환하기 위한 옵션."
type: docs
weight: 48
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/wordprocessingconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions), [com.groupdocs.conversion.options.convert.IPdfRecognitionModeOptions](../../com.groupdocs.conversion.options.convert/ipdfrecognitionmodeoptions)
```
public class WordProcessingConvertOptions extends CommonConvertOptions<WordProcessingFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions, IPdfRecognitionModeOptions
```

WordProcessing 파일 형식으로 변환하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingConvertOptions()](#WordProcessingConvertOptions--) | 새 인스턴스를 초기화합니다 [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) 클래스. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDpi()](#getDpi--) | 변환 후 원하는 페이지 DPI. |
| [setDpi(int value)](#setDpi-int-) | 변환 후 원하는 페이지 DPI. |
| [getPassword()](#getPassword--) | 변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오. |
| [getRtfOptions()](#getRtfOptions--) | RTF 전용 변환 옵션 |
| [setRtfOptions(RtfOptions value)](#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-) | RTF 전용 변환 옵션 |
| [getZoom()](#getZoom--) | 줌 레벨을 백분율로 지정합니다. |
| [setZoom(int value)](#setZoom-int-) | 줌 레벨을 백분율로 지정합니다. |
| [getMarginTop()](#getMarginTop--) | 변환 후 원하는 페이지 상단 여백(픽셀). |
| [setMarginTop(int value)](#setMarginTop-int-) | 변환 후 원하는 페이지 상단 여백(픽셀). |
| [getMarginBottom()](#getMarginBottom--) | 변환 후 원하는 페이지 하단 여백(픽셀). |
| [setMarginBottom(int value)](#setMarginBottom-int-) | 변환 후 원하는 페이지 하단 여백(픽셀). |
| [getMarginLeft()](#getMarginLeft--) | 변환 후 원하는 페이지 왼쪽 여백(픽셀). |
| [setMarginLeft(int value)](#setMarginLeft-int-) | 변환 후 원하는 페이지 왼쪽 여백(픽셀). |
| [getMarginRight()](#getMarginRight--) | 변환 후 원하는 페이지 오른쪽 여백(픽셀). |
| [setMarginRight(int value)](#setMarginRight-int-) | 변환 후 원하는 페이지 오른쪽 여백(픽셀). |
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
| [getPdfRecognitionMode()](#getPdfRecognitionMode--) |  |
| [setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)](#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-) |  |
### WordProcessingConvertOptions() {#WordProcessingConvertOptions--}
```
public WordProcessingConvertOptions()
```


새 인스턴스를 초기화합니다 [WordProcessingConvertOptions](../../com.groupdocs.conversion.options.convert/wordprocessingconvertoptions) 클래스.

### getDpi() {#getDpi--}
```
public final int getDpi()
```


변환 후 원하는 페이지 DPI. 기본 해상도는 96 dpi입니다.

**Returns:**
int
### setDpi(int value) {#setDpi-int-}
```
public final void setDpi(int value)
```


변환 후 원하는 페이지 DPI. 기본 해상도는 96 dpi입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getRtfOptions() {#getRtfOptions--}
```
public final RtfOptions getRtfOptions()
```


RTF 전용 변환 옵션

**Returns:**
[RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions)
### setRtfOptions(RtfOptions value) {#setRtfOptions-com.groupdocs.conversion.options.convert.RtfOptions-}
```
public final void setRtfOptions(RtfOptions value)
```


RTF 전용 변환 옵션

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [RtfOptions](../../com.groupdocs.conversion.options.convert/rtfoptions) |  |

### getZoom() {#getZoom--}
```
public final int getZoom()
```


줌 레벨을 백분율로 지정합니다. 기본값은 100입니다. 기본 줌은 Microsoft Word 2010까지 지원됩니다. Microsoft Word 2013부터는 기본 줌이 문서에 설정되지 않고, 대신 마지막으로 열린 문서의 줌 비율을 사용하는 것으로 보입니다.

**Returns:**
int
### setZoom(int value) {#setZoom-int-}
```
public final void setZoom(int value)
```


줌 레벨을 백분율로 지정합니다. 기본값은 100입니다. 기본 줌은 Microsoft Word 2010까지 지원됩니다. Microsoft Word 2013부터는 기본 줌이 문서에 설정되지 않고, 대신 마지막으로 열린 문서의 줌 비율을 사용하는 것으로 보입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getMarginTop() {#getMarginTop--}
```
public final int getMarginTop()
```


변환 후 원하는 페이지 상단 여백(픽셀).

**Returns:**
int
### setMarginTop(int value) {#setMarginTop-int-}
```
public final void setMarginTop(int value)
```


변환 후 원하는 페이지 상단 여백(픽셀).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getMarginBottom() {#getMarginBottom--}
```
public final int getMarginBottom()
```


변환 후 원하는 페이지 하단 여백(픽셀).

**Returns:**
int
### setMarginBottom(int value) {#setMarginBottom-int-}
```
public final void setMarginBottom(int value)
```


변환 후 원하는 페이지 하단 여백(픽셀).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getMarginLeft() {#getMarginLeft--}
```
public final int getMarginLeft()
```


변환 후 원하는 페이지 왼쪽 여백(픽셀).

**Returns:**
int
### setMarginLeft(int value) {#setMarginLeft-int-}
```
public final void setMarginLeft(int value)
```


변환 후 원하는 페이지 왼쪽 여백(픽셀).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getMarginRight() {#getMarginRight--}
```
public final int getMarginRight()
```


변환 후 원하는 페이지 오른쪽 여백(픽셀).

**Returns:**
int
### setMarginRight(int value) {#setMarginRight-int-}
```
public final void setMarginRight(int value)
```


변환 후 원하는 페이지 오른쪽 여백(픽셀).

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getPageOrientation() {#getPageOrientation--}
```
public PageOrientation getPageOrientation()
```


변환 후 페이지 방향을 가져옵니다

**Returns:**
[PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation)
### setPageOrientation(PageOrientation pageOrientation) {#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-}
```
public void setPageOrientation(PageOrientation pageOrientation)
```


변환 후 원하는 페이지 방향을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageOrientation | [PageOrientation](../../com.groupdocs.conversion.options.convert/pageorientation) |  |

### getPageSize() {#getPageSize--}
```
public PageSize getPageSize()
```


변환 후 원하는 페이지 크기를 가져옵니다

**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public void setPageSize(PageSize pageSize)
```


변환 후 원하는 페이지 크기를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


PageSize.Custom으로 설정된 경우 지정된 페이지 너비(포인트)

**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public void setPageWidth(float pageWidth)
```


원하는 페이지 너비를 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


PageSize.Custom 로 설정된 경우 지정된 페이지 높이(포인트)

**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public void setPageHeight(float pageHeight)
```


원하는 페이지 높이 설정

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageHeight | float |  |

### getPdfRecognitionMode() {#getPdfRecognitionMode--}
```
public PdfRecognitionMode getPdfRecognitionMode()
```


PDF 변환 시 인식 모드 가져오기

**Returns:**
[PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode)
### setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode) {#setPdfRecognitionMode-com.groupdocs.conversion.options.convert.PdfRecognitionMode-}
```
public void setPdfRecognitionMode(PdfRecognitionMode pdfRecognitionMode)
```


PDF 변환 시 인식 모드 설정

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pdfRecognitionMode | [PdfRecognitionMode](../../com.groupdocs.conversion.options.convert/pdfrecognitionmode) |  |

