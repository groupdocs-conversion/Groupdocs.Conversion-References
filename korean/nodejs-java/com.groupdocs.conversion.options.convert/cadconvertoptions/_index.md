---
title: "CadConvertOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Cad 유형으로 변환하기 위한 옵션."
type: docs
weight: 10
url: /ko/nodejs-java/com.groupdocs.conversion.options.convert/cadconvertoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), com.groupdocs.conversion.options.convert.ConvertOptions

**All Implemented Interfaces:**
[com.groupdocs.conversion.options.convert.IPagedConvertOptions](../../com.groupdocs.conversion.options.convert/ipagedconvertoptions)
```
public class CadConvertOptions extends ConvertOptions<CadFileType> implements IPagedConvertOptions
```

Cad 유형으로 변환하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CadConvertOptions()](#CadConvertOptions--) |   클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPageNumber()](#getPageNumber--) |  |
| [setPageNumber(int pageNumber)](#setPageNumber-int-) |  |
| [getPagesCount()](#getPagesCount--) |  |
| [setPagesCount(int pagesCount)](#setPagesCount-int-) |  |
### CadConvertOptions() {#CadConvertOptions--}
```
public CadConvertOptions()
```


  클래스의 새 인스턴스를 초기화합니다.

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

