---
title: "PdfFormattingOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "PDF 서식 옵션을 정의합니다."
type: docs
weight: 28
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/pdfformattingoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public final class PdfFormattingOptions extends ValueObject implements Serializable
```

PDF 서식 옵션을 정의합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PdfFormattingOptions()](#PdfFormattingOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCenterWindow()](#getCenterWindow--) | 문서 창의 위치가 화면 중앙에 배치될지 여부를 지정합니다. |
| [setCenterWindow(boolean value)](#setCenterWindow-boolean-) | 문서 창의 위치가 화면 중앙에 배치될지 여부를 지정합니다. |
| [getDirection()](#getDirection--) | 텍스트 읽기 순서를 설정합니다: L2R(왼쪽에서 오른쪽) 또는 R2L(오른쪽에서 왼쪽). |
| [setDirection(PdfDirection value)](#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-) | 텍스트 읽기 순서를 설정합니다: L2R(왼쪽에서 오른쪽) 또는 R2L(오른쪽에서 왼쪽). |
| [getDisplayDocTitle()](#getDisplayDocTitle--) | 문서 창 제목 표시줄에 문서 제목을 표시할지 여부를 지정합니다. |
| [setDisplayDocTitle(boolean value)](#setDisplayDocTitle-boolean-) | 문서 창 제목 표시줄에 문서 제목을 표시할지 여부를 지정합니다. |
| [getFitWindow()](#getFitWindow--) | 문서 창을 첫 번째 표시 페이지에 맞게 크기 조정할지 여부를 지정합니다. |
| [setFitWindow(boolean value)](#setFitWindow-boolean-) | 문서 창을 첫 번째 표시 페이지에 맞게 크기 조정할지 여부를 지정합니다. |
| [getHideMenuBar()](#getHideMenuBar--) | 문서가 활성화될 때 메뉴 모음이 숨겨질지 여부를 지정합니다. |
| [setHideMenuBar(boolean value)](#setHideMenuBar-boolean-) | 문서가 활성화될 때 메뉴 모음이 숨겨질지 여부를 지정합니다. |
| [getHideToolBar()](#getHideToolBar--) | 문서가 활성화될 때 도구 모음이 숨겨질지 여부를 지정합니다. |
| [setHideToolBar(boolean value)](#setHideToolBar-boolean-) | 문서가 활성화될 때 도구 모음이 숨겨질지 여부를 지정합니다. |
| [getHideWindowUI()](#getHideWindowUI--) | 문서가 활성화될 때 사용자 인터페이스 요소가 숨겨질지 여부를 지정합니다. |
| [setHideWindowUI(boolean value)](#setHideWindowUI-boolean-) | 문서가 활성화될 때 사용자 인터페이스 요소가 숨겨질지 여부를 지정합니다. |
| [getNonFullScreenPageMode()](#getNonFullScreenPageMode--) | 전체 화면 모드를 종료할 때 문서를 표시하는 방법을 지정하여 페이지 모드를 설정합니다. |
| [setNonFullScreenPageMode(PdfPageMode value)](#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | 전체 화면 모드를 종료할 때 문서를 표시하는 방법을 지정하여 페이지 모드를 설정합니다. |
| [getPageLayout()](#getPageLayout--) | 문서를 열 때 사용할 페이지 레이아웃을 설정합니다. |
| [setPageLayout(PdfPageLayout value)](#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-) | 문서를 열 때 사용할 페이지 레이아웃을 설정합니다. |
| [getPageMode()](#getPageMode--) | 문서를 열 때 표시되는 방식을 지정하여 페이지 모드를 설정합니다. |
| [setPageMode(PdfPageMode value)](#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-) | 문서를 열 때 표시되는 방식을 지정하여 페이지 모드를 설정합니다. |
### PdfFormattingOptions() {#PdfFormattingOptions--}
```
public PdfFormattingOptions()
```


### getCenterWindow() {#getCenterWindow--}
```
public final boolean getCenterWindow()
```


문서 창의 위치가 화면 중앙에 배치될지 여부를 지정합니다. 기본값: false.

**Returns:**
boolean
### setCenterWindow(boolean value) {#setCenterWindow-boolean-}
```
public final void setCenterWindow(boolean value)
```


문서 창의 위치가 화면 중앙에 배치될지 여부를 지정합니다. 기본값: false.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getDirection() {#getDirection--}
```
public final PdfDirection getDirection()
```


텍스트 읽기 순서를 설정합니다: L2R(왼쪽에서 오른쪽) 또는 R2L(오른쪽에서 왼쪽). 기본값: L2R.

**Returns:**
[PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection)
### setDirection(PdfDirection value) {#setDirection-com.groupdocs.conversion.options.convert.PdfDirection-}
```
public final void setDirection(PdfDirection value)
```


텍스트 읽기 순서를 설정합니다: L2R(왼쪽에서 오른쪽) 또는 R2L(오른쪽에서 왼쪽). 기본값: L2R.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PdfDirection](../../com.groupdocs.conversion.options.convert/pdfdirection) |  |

### getDisplayDocTitle() {#getDisplayDocTitle--}
```
public final boolean getDisplayDocTitle()
```


문서 창 제목 표시줄에 문서 제목을 표시할지 여부를 지정합니다. 기본값: false.

**Returns:**
boolean
### setDisplayDocTitle(boolean value) {#setDisplayDocTitle-boolean-}
```
public final void setDisplayDocTitle(boolean value)
```


문서 창 제목 표시줄에 문서 제목을 표시할지 여부를 지정합니다. 기본값: false.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getFitWindow() {#getFitWindow--}
```
public final boolean getFitWindow()
```


문서 창을 첫 번째 표시 페이지에 맞게 크기 조정할지 여부를 지정합니다. 기본값: false.

**Returns:**
boolean
### setFitWindow(boolean value) {#setFitWindow-boolean-}
```
public final void setFitWindow(boolean value)
```


문서 창을 첫 번째 표시 페이지에 맞게 크기 조정할지 여부를 지정합니다. 기본값: false.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getHideMenuBar() {#getHideMenuBar--}
```
public final boolean getHideMenuBar()
```


문서가 활성화될 때 메뉴 모음을 숨길지 여부를 지정합니다. 기본값: false.

**Returns:**
boolean
### setHideMenuBar(boolean value) {#setHideMenuBar-boolean-}
```
public final void setHideMenuBar(boolean value)
```


문서가 활성화될 때 메뉴 모음을 숨길지 여부를 지정합니다. 기본값: false.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getHideToolBar() {#getHideToolBar--}
```
public final boolean getHideToolBar()
```


문서가 활성화될 때 도구 모음을 숨길지 여부를 지정합니다. 기본값: false.

**Returns:**
boolean
### setHideToolBar(boolean value) {#setHideToolBar-boolean-}
```
public final void setHideToolBar(boolean value)
```


문서가 활성화될 때 도구 모음을 숨길지 여부를 지정합니다. 기본값: false.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getHideWindowUI() {#getHideWindowUI--}
```
public final boolean getHideWindowUI()
```


문서가 활성화될 때 사용자 인터페이스 요소를 숨길지 여부를 지정합니다. 기본값: false.

**Returns:**
boolean
### setHideWindowUI(boolean value) {#setHideWindowUI-boolean-}
```
public final void setHideWindowUI(boolean value)
```


문서가 활성화될 때 사용자 인터페이스 요소를 숨길지 여부를 지정합니다. 기본값: false.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getNonFullScreenPageMode() {#getNonFullScreenPageMode--}
```
public final PdfPageMode getNonFullScreenPageMode()
```


전체 화면 모드를 종료할 때 문서를 표시하는 방법을 지정하여 페이지 모드를 설정합니다.

**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setNonFullScreenPageMode(PdfPageMode value) {#setNonFullScreenPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setNonFullScreenPageMode(PdfPageMode value)
```


전체 화면 모드를 종료할 때 문서를 표시하는 방법을 지정하여 페이지 모드를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

### getPageLayout() {#getPageLayout--}
```
public final PdfPageLayout getPageLayout()
```


문서를 열 때 사용할 페이지 레이아웃을 설정합니다.

**Returns:**
[PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout)
### setPageLayout(PdfPageLayout value) {#setPageLayout-com.groupdocs.conversion.options.convert.PdfPageLayout-}
```
public final void setPageLayout(PdfPageLayout value)
```


문서를 열 때 사용할 페이지 레이아웃을 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PdfPageLayout](../../com.groupdocs.conversion.options.convert/pdfpagelayout) |  |

### getPageMode() {#getPageMode--}
```
public final PdfPageMode getPageMode()
```


문서를 열 때 표시되는 방식을 지정하여 페이지 모드를 설정합니다.

**Returns:**
[PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode)
### setPageMode(PdfPageMode value) {#setPageMode-com.groupdocs.conversion.options.convert.PdfPageMode-}
```
public final void setPageMode(PdfPageMode value)
```


문서를 열 때 표시되는 방식을 지정하여 페이지 모드를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [PdfPageMode](../../com.groupdocs.conversion.options.convert/pdfpagemode) |  |

