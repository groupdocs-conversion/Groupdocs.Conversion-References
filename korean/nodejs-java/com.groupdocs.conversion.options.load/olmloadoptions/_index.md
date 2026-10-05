---
title: "OlmLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Olm 문서를 로드하기 위한 옵션."
type: docs
weight: 29
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/olmloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions), java.lang.Cloneable, java.io.Serializable
```
public final class OlmLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions, Cloneable, Serializable
```

Olm 문서를 로드하기 위한 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OlmLoadOptions()](#OlmLoadOptions--) | 새 인스턴스를 초기화합니다 [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions) 클래스. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [folder](#folder) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [memberwiseClone()](#memberwiseClone--) |  |
| [isConvertOwner()](#isConvertOwner--) | 소유자는 변환되지 않습니다 |
| [isConvertOwned()](#isConvertOwned--) | \{@inheritDoc\} |
| [getFolder()](#getFolder--) | 처리할 폴더. 기본값은 Inbox입니다. |
| [setFolder(String folder)](#setFolder-java.lang.String-) |  |
| [getDepth()](#getDepth--) | \{@inheritDoc\} 기본값: 3 |
| [setDepth(int depth)](#setDepth-int-) |  |
| [deepClone()](#deepClone--) | 현재 인스턴스를 복제합니다. |
### OlmLoadOptions() {#OlmLoadOptions--}
```
public OlmLoadOptions()
```


새 인스턴스를 초기화합니다 [OlmLoadOptions](../../com.groupdocs.conversion.options.load/olmloadoptions) 클래스.

### folder {#folder}
```
public String folder
```


### memberwiseClone() {#memberwiseClone--}
```
public Object memberwiseClone()
```




**Returns:**
java.lang.Object
### isConvertOwner() {#isConvertOwner--}
```
public boolean isConvertOwner()
```


소유자는 변환되지 않습니다

**Returns:**
boolean
### isConvertOwned() {#isConvertOwned--}
```
public boolean isConvertOwned()
```


문서 컨테이너에 있는 소유 문서를 변환해야 하는지 제어하는 옵션

**Returns:**
boolean
### getFolder() {#getFolder--}
```
public String getFolder()
```


처리할 폴더. 기본값은 Inbox입니다.

**Returns:**
java.lang.String
### setFolder(String folder) {#setFolder-java.lang.String-}
```
public void setFolder(String folder)
```




**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 폴더 | java.lang.String |  |

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
| 깊이 | int |  |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


현재 인스턴스를 복제합니다.

**Returns:**
java.lang.Object
