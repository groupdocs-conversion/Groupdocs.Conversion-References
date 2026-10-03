---
title: "MboxLoadOptions"
second_title: "GroupDocs.Conversion for Java API 레퍼런스"
description: "Mbox 문서를 로드하기 위한 옵션."
type: docs
weight: 23
url: /ko/java/com.groupdocs.conversion.options.load/mboxloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class MboxLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

Mbox 문서를 로드하기 위한 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [MboxLoadOptions()](#MboxLoadOptions--) | 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isConvertOwner()](#isConvertOwner--) | 소유자는 변환되지 않습니다 |
|
|  | [isConvertOwned()](#isConvertOwned--) | {@inheritDoc} |
|
|  | [getDepth()](#getDepth--) | {@inheritDoc} 기본값: 3 |
|
|  | [setDepth(int depth)](#setDepth-int-) | {@inheritDoc} |
|
|  | [getEqualityComponents()](#getEqualityComponents--) | {@inheritDoc} |
|
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


클래스의 새 인스턴스를 초기화합니다.


### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


소유자는 변환되지 않습니다


**Returns:**
불리언
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


문서 컨테이너 내 소유된 문서를 변환해야 하는지 제어하는 옵션


**Returns:**
불리언
### getDepth() {#getDepth--}
```
public int getDepth()
```


변환을 수행할 깊이 수준 수를 제어하는 옵션 기본값: 3


**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| depth | int |  |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
