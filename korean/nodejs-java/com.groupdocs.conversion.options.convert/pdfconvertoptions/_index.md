---
title: "PdfConvertOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "PDF 파일 형식으로 변환 옵션."
type: docs
weight: 25
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/pdfconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions

**All Implemented Interfaces:**
java.io.Serializable, [com.groupdocs.conversion.options.convert.IPageMarginConvertOptions](../../com.groupdocs.conversion.options.convert/ipagemarginconvertoptions), [com.groupdocs.conversion.options.convert.IPageSizeConvertOptions](../../com.groupdocs.conversion.options.convert/ipagesizeconvertoptions), [com.groupdocs.conversion.options.convert.IPageOrientationConvertOptions](../../com.groupdocs.conversion.options.convert/ipageorientationconvertoptions)
```
public class PdfConvertOptions extends CommonConvertOptions<PdfFileType> implements Serializable, IPageMarginConvertOptions, IPageSizeConvertOptions, IPageOrientationConvertOptions
```

PDF 파일 형식으로 변환 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfConvertOptions()](#PdfConvertOptions--) | 새로운 [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getDpi()](#getDpi--) | 변환 후 원하는 페이지 DPI. |
| [setDpi(int value)](#setDpi-int-) | 변환 후 원하는 페이지 DPI. |
| [getPassword()](#getPassword--) | 변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오. |
| [setPassword(String value)](#setPassword-java.lang.String-) | 변환된 문서를 비밀번호로 보호하려면 이 속성을 설정하십시오. |
| [getMarginTop()](#getMarginTop--) | 변환 후 원하는 페이지 상단 여백(픽셀). |
| [setMarginTop(int value)](#setMarginTop-int-) | 변환 후 원하는 페이지 상단 여백(픽셀). |
| [getMarginBottom()](#getMarginBottom--) | 변환 후 원하는 페이지 하단 여백(픽셀). |
| [setMarginBottom(int value)](#setMarginBottom-int-) | 변환 후 원하는 페이지 하단 여백(픽셀). |
| [getMarginLeft()](#getMarginLeft--) | 변환 후 원하는 페이지 왼쪽 여백(픽셀). |
| [setMarginLeft(int value)](#setMarginLeft-int-) | 변환 후 원하는 페이지 왼쪽 여백(픽셀). |
| [getMarginRight()](#getMarginRight--) | 변환 후 원하는 페이지 오른쪽 여백(픽셀). |
| [setMarginRight(int value)](#setMarginRight-int-) | 변환 후 원하는 페이지 오른쪽 여백(픽셀). |
| [getPdfOptions()](#getPdfOptions--) | Pdf 전용 변환 옵션 |
| [setPdfOptions(PdfOptions value)](#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-) | Pdf 전용 변환 옵션 |
| [getRotate()](#getRotate--) | 페이지 회전 |
| [setRotate(Rotation value)](#setRotate-com.groupdocs.conversion.options.convert.Rotation-) | 페이지 회전 |
| [getPageOrientation()](#getPageOrientation--) |  |
| [setPageOrientation(PageOrientation pageOrientation)](#setPageOrientation-com.groupdocs.conversion.options.convert.PageOrientation-) |  |
| [getPageSize()](#getPageSize--) |  |
| [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) |  |
| [getPageWidth()](#getPageWidth--) |  |
| [setPageWidth(float pageWidth)](#setPageWidth-float-) |  |
| [getPageHeight()](#getPageHeight--) |  |
| [setPageHeight(float pageHeight)](#setPageHeight-float-) |  |
### PdfConvertOptions() {#PdfConvertOptions--}
```
public PdfConvertOptions()
```


새로운 [PdfConvertOptions](../../com.groupdocs.conversion.options.convert/pdfconvertoptions) 클래스 인스턴스를 초기화합니다.

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

### getPdfOptions() {#getPdfOptions--}
```
public final PdfOptions getPdfOptions()
```


Pdf 전용 변환 옵션

**Returns:**
[PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions)
### setPdfOptions(PdfOptions value) {#setPdfOptions-com.groupdocs.conversion.options.convert.PdfOptions-}
```
public final void setPdfOptions(PdfOptions value)
```


Pdf 전용 변환 옵션

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PdfOptions](../../com.groupdocs.conversion.options.convert/pdfoptions) |  |

### getRotate() {#getRotate--}
```
public final Rotation getRotate()
```


페이지 회전

**Returns:**
[Rotation](../../com.groupdocs.conversion.options.convert/rotation)
### setRotate(Rotation value) {#setRotate-com.groupdocs.conversion.options.convert.Rotation-}
```
public final void setRotate(Rotation value)
```


페이지 회전

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [Rotation](../../com.groupdocs.conversion.options.convert/rotation) |  |

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

