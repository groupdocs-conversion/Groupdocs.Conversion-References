---
title: "CommonConvertOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "추상적인 일반 공통 변환 옵션 클래스."
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/commonconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IWatermarkedConvertOptions](../../com.groupdocs.conversion.options.convert/iwatermarkedconvertoptions), [com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions), [com.groupdocs.conversion.options.convert.IPageRangedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagerangedconvertoptions)
```
public abstract class CommonConvertOptions<TFileType> extends ConvertOptions<TFileType> implements IWatermarkedConvertOptions, IPagedConvertOptions, IPageRangedConvertOptions
```

추상적인 일반 공통 변환 옵션 클래스.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWatermark()](#getWatermark--) |  |
| [setWatermark(WatermarkOptions watermark)](#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-) |  |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
| [getPages()](#getPages--) |  |
| [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) |  |
### getWatermark() {#getWatermark--}
```
public WatermarkOptions getWatermark()
```


워터마크 특정 옵션을 가져옵니다

**Returns:**
[WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions)
### setWatermark(WatermarkOptions watermark) {#setWatermark-com.groupdocs.conversion.options.convert.WatermarkOptions-}
```
public void setWatermark(WatermarkOptions watermark)
```


워터마크 특정 옵션을 설정합니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| watermark | [WatermarkOptions](../../com.groupdocs.conversion.options.convert/watermarkoptions) |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


변환을 시작할 페이지 번호를 가져옵니다.

**Returns:**
java.lang.Integer
### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public void setPageNumber(int pageNumber)
```


변환을 시작할 페이지 번호를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pageNumber | int |  |

### getPagesCount() {#getPagesCount--}
```
public Integer getPagesCount()
```


PageNumber부터 변환할 페이지 수를 가져옵니다.

**Returns:**
java.lang.Integer
### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public void setPagesCount(int pagesCount)
```


PageNumber부터 변환할 페이지 수를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| pagesCount | int |  |

### getPages() {#getPages--}
```
public List<Integer> getPages()
```


변환될 페이지 인덱스 목록을 가져옵니다. 특정 페이지를 변환하려면 지정해야 합니다.

**Returns:**
java.util.List<java.lang.Integer>
### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public void setPages(List<Integer> pages)
```


변환될 페이지 인덱스 목록을 설정합니다. 특정 페이지를 변환하려면 지정해야 합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 페이지 | java.util.List<java.lang.Integer> |  |

