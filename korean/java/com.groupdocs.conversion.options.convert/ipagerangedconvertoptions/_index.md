---
title: "IPageRangedConvertOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "특정 페이지 목록 변환을 지원하는 변환 옵션을 나타냅니다."
type: docs
weight: 52
url: /ko/java/com.groupdocs.conversion.options.convert/ipagerangedconvertoptions/
---
**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IConvertOptions](../../com.groupdocs.conversion.options.convert/iconvertoptions)
```
public interface IPageRangedConvertOptions extends IConvertOptions
```

특정 페이지 목록 변환을 지원하는 변환 옵션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPages()](#getPages--) | 변환될 페이지 인덱스 목록을 가져옵니다. |
|
|  | [setPages(List<Integer> pages)](#setPages-java.util.List-java.lang.Integer--) | 변환될 페이지 인덱스 목록을 설정합니다. |
|
### getPages() {#getPages--}
```
public abstract List<Integer> getPages()
```


변환될 페이지 인덱스 목록을 가져옵니다. 특정 페이지를 변환하려면 지정해야 합니다.


**Returns:**
java.util.List<java.lang.Integer> - 변환될 페이지 인덱스 목록입니다. 특정 페이지를 변환하려면 지정해야 합니다.

### setPages(List<Integer> pages) {#setPages-java.util.List-java.lang.Integer--}
```
public abstract void setPages(List<Integer> pages)
```


변환될 페이지 인덱스 목록을 설정합니다. 특정 페이지를 변환하려면 지정해야 합니다.


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
|  | 페이지 | java.util.List<java.lang.Integer> | 변환될 페이지 인덱스 목록입니다. 특정 페이지를 변환하려면 지정해야 합니다. |
|

