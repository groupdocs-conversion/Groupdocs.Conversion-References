---
title: "WordProcessingBookmarksOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "WordProcessing에서 북마크를 처리하기 위한 옵션"
type: docs
weight: 43
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/wordprocessingbookmarksoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)

**All Implemented Interfaces:**
java.io.Serializable
```
public class WordProcessingBookmarksOptions extends ValueObject implements Serializable
```

WordProcessing에서 북마크를 처리하기 위한 옵션
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [WordProcessingBookmarksOptions()](#WordProcessingBookmarksOptions--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBookmarksOutlineLevel()](#getBookmarksOutlineLevel--) | 문서 개요에서 Word 책갈피를 표시할 기본 레벨을 지정합니다. |
| [setBookmarksOutlineLevel(int value)](#setBookmarksOutlineLevel-int-) | 문서 개요에서 Word 책갈피를 표시할 기본 레벨을 지정합니다. |
| [getHeadingsOutlineLevels()](#getHeadingsOutlineLevels--) | 문서 개요에 포함할 머리글 수준(Heading 스타일로 서식이 지정된 단락)의 수를 지정합니다. |
| [setHeadingsOutlineLevels(int value)](#setHeadingsOutlineLevels-int-) | 문서 개요에 포함할 머리글 수준(Heading 스타일로 서식이 지정된 단락)의 수를 지정합니다. |
| [getExpandedOutlineLevels()](#getExpandedOutlineLevels--) | 파일을 볼 때 문서 개요에서 확장된 상태로 표시할 레벨 수를 지정합니다. |
| [setExpandedOutlineLevels(int value)](#setExpandedOutlineLevels-int-) | 파일을 볼 때 문서 개요에서 확장된 상태로 표시할 레벨 수를 지정합니다. |
### WordProcessingBookmarksOptions() {#WordProcessingBookmarksOptions--}
```
public WordProcessingBookmarksOptions()
```


### getBookmarksOutlineLevel() {#getBookmarksOutlineLevel--}
```
public final int getBookmarksOutlineLevel()
```


문서 개요에서 Word 책갈피를 표시할 기본 레벨을 지정합니다. 기본값은 0이며, 유효 범위는 0에서 9까지입니다.

**Returns:**
int
### setBookmarksOutlineLevel(int value) {#setBookmarksOutlineLevel-int-}
```
public final void setBookmarksOutlineLevel(int value)
```


문서 개요에서 Word 책갈피를 표시할 기본 레벨을 지정합니다. 기본값은 0이며, 유효 범위는 0에서 9까지입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeadingsOutlineLevels() {#getHeadingsOutlineLevels--}
```
public final int getHeadingsOutlineLevels()
```


문서 개요에 포함할 머리글 수준(Heading 스타일로 서식이 지정된 단락)의 수를 지정합니다. 기본값은 0이며, 유효 범위는 0에서 9까지입니다.

**Returns:**
int
### setHeadingsOutlineLevels(int value) {#setHeadingsOutlineLevels-int-}
```
public final void setHeadingsOutlineLevels(int value)
```


문서 개요에 포함할 머리글 수준(Heading 스타일로 서식이 지정된 단락)의 수를 지정합니다. 기본값은 0이며, 유효 범위는 0에서 9까지입니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getExpandedOutlineLevels() {#getExpandedOutlineLevels--}
```
public final int getExpandedOutlineLevels()
```


파일을 볼 때 문서 개요에서 확장된 상태로 표시할 레벨 수를 지정합니다. 기본값은 0이며, 유효 범위는 0에서 9까지입니다. 이 옵션은 XPS로 저장할 때 작동하지 않음을 유의하십시오.

**Returns:**
int
### setExpandedOutlineLevels(int value) {#setExpandedOutlineLevels-int-}
```
public final void setExpandedOutlineLevels(int value)
```


파일을 볼 때 문서 개요에서 확장된 상태로 표시할 레벨 수를 지정합니다. 기본값은 0이며, 유효 범위는 0에서 9까지입니다. 이 옵션은 XPS로 저장할 때 작동하지 않음을 유의하십시오.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 값 | int |  |

