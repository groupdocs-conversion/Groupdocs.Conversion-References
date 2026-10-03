---
title: "WebConvertOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "Web 파일 형식으로 변환하기 위한 옵션."
type: docs
weight: 46
url: /ko/java/com.groupdocs.conversion.options.convert/webconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions, com.groupdocs.conversion.options.convert.CommonConvertOptions
```
public class WebConvertOptions extends CommonConvertOptions<WebFileType>
```

Web 파일 형식으로 변환하기 위한 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WebConvertOptions()](#WebConvertOptions--) | 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isUsePdf()](#isUsePdf--) |  |
| [setUsePdf(boolean usePdf)](#setUsePdf-boolean-) |  |
| [isFixedLayout()](#isFixedLayout--) |  |
| [setFixedLayout(boolean fixedLayout)](#setFixedLayout-boolean-) |  |
| [isFixedLayoutShowBorders()](#isFixedLayoutShowBorders--) |  |
| [setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)](#setFixedLayoutShowBorders-boolean-) |  |
| [getZoom()](#getZoom--) |  |
| [setZoom(int zoom)](#setZoom-int-) |  |
|  | [isEmbedFontResources()](#isEmbedFontResources--) | 주 HTML에 글꼴 리소스를 포함할지 여부를 지정합니다. |
|
|  | [setEmbedFontResources(boolean embedFontResources)](#setEmbedFontResources-boolean-) | 주 HTML에 글꼴 리소스를 포함할지 여부를 지정합니다. |
|
### WebConvertOptions() {#WebConvertOptions--}
```
public WebConvertOptions()
```


클래스의 새 인스턴스를 초기화합니다.


### isUsePdf() {#isUsePdf--}
```
public boolean isUsePdf()
```




**Returns:**
불리언
### setUsePdf(boolean usePdf) {#setUsePdf-boolean-}
```
public void setUsePdf(boolean usePdf)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| usePdf | 불리언 |  |

### isFixedLayout() {#isFixedLayout--}
```
public boolean isFixedLayout()
```




**Returns:**
불리언
### setFixedLayout(boolean fixedLayout) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean fixedLayout)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fixedLayout | 불리언 |  |

### isFixedLayoutShowBorders() {#isFixedLayoutShowBorders--}
```
public boolean isFixedLayoutShowBorders()
```




**Returns:**
불리언
### setFixedLayoutShowBorders(boolean fixedLayoutShowBorders) {#setFixedLayoutShowBorders-boolean-}
```
public void setFixedLayoutShowBorders(boolean fixedLayoutShowBorders)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fixedLayoutShowBorders | 불리언 |  |

### getZoom() {#getZoom--}
```
public int getZoom()
```




**Returns:**
int
### setZoom(int zoom) {#setZoom-int-}
```
public void setZoom(int zoom)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| zoom | int |  |

### isEmbedFontResources() {#isEmbedFontResources--}
```
public boolean isEmbedFontResources()
```


주 HTML에 글꼴 리소스를 포함할지 여부를 지정합니다. 기본값은 false입니다. 참고: FixedLayout이 true로 설정된 경우 글꼴 리소스는 항상 포함됩니다.


**Returns:**
불리언
### setEmbedFontResources(boolean embedFontResources) {#setEmbedFontResources-boolean-}
```
public void setEmbedFontResources(boolean embedFontResources)
```


주 HTML에 글꼴 리소스를 포함할지 여부를 지정합니다. 기본값은 false입니다. 참고: FixedLayout이 true로 설정된 경우 글꼴 리소스는 항상 포함됩니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| embedFontResources | 불리언 |  |

