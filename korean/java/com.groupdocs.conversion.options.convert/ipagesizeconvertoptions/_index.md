---
title: "IPageSizeConvertOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "페이지 크기를 지원하는 변환 옵션을 나타냅니다."
type: docs
weight: 54
url: /ko/java/com.groupdocs.conversion.options.convert/ipagesizeconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageSizeConvertOptions extends IConvertOptions
```

페이지 크기를 지원하는 변환 옵션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageSize()](#getPageSize--) | 변환 후 원하는 페이지 크기를 가져옵니다 |
|
|  | [setPageSize(PageSize pageSize)](#setPageSize-com.groupdocs.conversion.options.convert.PageSize-) | 변환 후 원하는 페이지 크기를 설정합니다 |
|
|  | [getPageWidth()](#getPageWidth--) | PageSize.Custom으로 설정된 경우 지정된 페이지 너비(포인트) |
|
|  | [setPageWidth(float pageWidth)](#setPageWidth-float-) | 원하는 페이지 너비 설정 |
|
|  | [getPageHeight()](#getPageHeight--) | PageSize.Custom으로 설정된 경우 지정된 페이지 높이(포인트) |
|
|  | [setPageHeight(float pageHeight)](#setPageHeight-float-) | 원하는 페이지 높이 설정 |
|
### getPageSize() {#getPageSize--}
```
public abstract PageSize getPageSize()
```


변환 후 원하는 페이지 크기를 가져옵니다


**Returns:**
[PageSize](../../com.groupdocs.conversion.options.convert/pagesize)
### setPageSize(PageSize pageSize) {#setPageSize-com.groupdocs.conversion.options.convert.PageSize-}
```
public abstract void setPageSize(PageSize pageSize)
```


변환 후 원하는 페이지 크기를 설정합니다


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageSize | [PageSize](../../com.groupdocs.conversion.options.convert/pagesize) |  |

### getPageWidth() {#getPageWidth--}
```
public abstract float getPageWidth()
```


PageSize.Custom으로 설정된 경우 지정된 페이지 너비(포인트)


**Returns:**
float
### setPageWidth(float pageWidth) {#setPageWidth-float-}
```
public abstract void setPageWidth(float pageWidth)
```


원하는 페이지 너비 설정


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageWidth | float |  |

### getPageHeight() {#getPageHeight--}
```
public abstract float getPageHeight()
```


PageSize.Custom으로 설정된 경우 지정된 페이지 높이(포인트)


**Returns:**
float
### setPageHeight(float pageHeight) {#setPageHeight-float-}
```
public abstract void setPageHeight(float pageHeight)
```


원하는 페이지 높이 설정


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageHeight | float |  |

