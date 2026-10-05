---
title: "DocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "다형성 문서 정보를 검색하기 위한 기본 구현을 제공합니다"
type: docs
weight: 16
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.documentinfo.IDocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/idocumentinfo)
```
public abstract class DocumentInfo implements IDocumentInfo
```

다형성 문서 정보를 검색하기 위한 기본 구현을 제공합니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getPropertyNames()](#getPropertyNames--) | \{@inheritDoc\} |
| [getProperty(String propertyName)](#getProperty-java.lang.String-) | \{@inheritDoc\} |
| [getPagesCount()](#getPagesCount--) | \{@inheritDoc\} |
| [getFormat()](#getFormat--) | \{@inheritDoc\} |
| [getSize()](#getSize--) | \{@inheritDoc\} |
| [getCreationDate()](#getCreationDate--) | \{@inheritDoc\} |
### getPropertyNames() {#getPropertyNames--}
```
public List<String> getPropertyNames()
```


현재 문서 정보에 대해 가져올 수 있는 모든 속성 목록

**Returns:**
java.util.List<java.lang.String>
### getProperty(String propertyName) {#getProperty-java.lang.String-}
```
public String getProperty(String propertyName)
```


키로 제공된 속성에 대한 값을 가져옵니다

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| propertyName | java.lang.String |  |

**Returns:**
java.lang.String
### getPagesCount() {#getPagesCount--}
```
public int getPagesCount()
```


문서 페이지 수.

**Returns:**
int
### getFormat() {#getFormat--}
```
public String getFormat()
```


문서 형식

**Returns:**
java.lang.String
### getSize() {#getSize--}
```
public long getSize()
```


바이트 단위 문서 크기

**Returns:**
long
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


문서 생성 날짜

**Returns:**
java.util.Date
