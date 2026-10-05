---
title: "PersonalStorageLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "개인 저장소 문서를 로드하기 위한 옵션."
type: docs
weight: 32
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/personalstorageloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class PersonalStorageLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

개인 저장소 문서를 로드하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PersonalStorageLoadOptions()](#PersonalStorageLoadOptions--) |   클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getFolder()](#getFolder--) | 처리할 폴더. 기본값은 Inbox입니다. |
| [setFolder(String folder)](#setFolder-java.lang.String-) | 처리할 폴더를 설정합니다. |
| [isConvertOwner()](#isConvertOwner--) | \{@inheritDoc\} 소유자는 변환되지 않습니다 |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getDepth()](#getDepth--) | \{@inheritDoc\} |
| [setDepth(int depth)](#setDepth-int-) | \{@inheritDoc\} |
### PersonalStorageLoadOptions() {#PersonalStorageLoadOptions--}
```
public PersonalStorageLoadOptions()
```


  클래스의 새 인스턴스를 초기화합니다.

### getFolder() {#getFolder--}
```
public String getFolder()
```


처리할 폴더. 기본값은 Inbox입니다.

**Returns:**
java.lang.String - 처리할 폴더
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```


처리할 폴더를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 폴더 | java.lang.String | 폴더 |

### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


문서 컨테이너 자체를 변환해야 하는지 제어하는 옵션을 가져옵니다. 소유자는 변환되지 않습니다.

**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


문서 컨테이너에 있는 소유 문서를 변환해야 하는지 제어하는 옵션

**Returns:**
boolean
### getDepth() {#getDepth--}
```
public int getDepth()
```


변환을 수행할 깊이 레벨 수를 제어하는 옵션

**Returns:**
int
### setDepth(int depth) {#setDepth-int-}
```
public void setDepth(int depth)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 깊이 | int |  |

