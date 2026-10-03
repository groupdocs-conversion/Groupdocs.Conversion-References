---
title: "IPagedConvertOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "시작 페이지와 페이지 수를 지정하여 페이지 제한을 수행하도록 변환을 허용하는 변환 옵션을 나타냅니다."
type: docs
weight: 55
url: /ko/java/com.groupdocs.conversion.options.convert/ipagedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPagedConvertOptions extends IConvertOptions
```

시작 페이지와 페이지 수를 지정하여 페이지 제한을 수행하도록 변환을 허용하는 변환 옵션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | 변환을 시작할 페이지 번호를 가져옵니다. |
|
|  | [setPageNumber(int pageNumber)](#setPageNumber-int-) | 변환을 시작할 페이지 번호를 설정합니다. |
|
|  | [getPagesCount()](#getPagesCount--) | PageNumber부터 변환할 페이지 수를 가져옵니다. |
|
|  | [setPagesCount(int pagesCount)](#setPagesCount-int-) | PageNumber부터 변환할 페이지 수를 설정합니다. |
|
### getPageNumber() {#getPageNumber--}
```
public abstract Integer getPageNumber()
```


변환을 시작할 페이지 번호를 가져옵니다.


**Returns:**
java.lang.Integer - 변환을 시작할 페이지 번호입니다.

### setPageNumber(int pageNumber) {#setPageNumber-int-}
```
public abstract void setPageNumber(int pageNumber)
```


변환을 시작할 페이지 번호를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pageNumber | int | 변환을 시작할 페이지 번호. |
|

### getPagesCount() {#getPagesCount--}
```
public abstract Integer getPagesCount()
```


PageNumber부터 변환할 페이지 수를 가져옵니다.


**Returns:**
java.lang.Integer - PageNumber부터 변환할 페이지 수.

### setPagesCount(int pagesCount) {#setPagesCount-int-}
```
public abstract void setPagesCount(int pagesCount)
```


PageNumber부터 변환할 페이지 수를 설정합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | pagesCount | int | PageNumber부터 변환할 페이지 수. |
|

