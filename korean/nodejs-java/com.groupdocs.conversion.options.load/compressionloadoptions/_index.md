---
title: "CompressionLoadOptions"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "압축 문서 불러오기 옵션."
type: docs
weight: 13
url: /ko/nodejs-java/com.groupdocs.conversion.options.load/compressionloadoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject), [com.groupdocs.conversion.options.load.LoadOptions](../../com.groupdocs.conversion.options.load/loadoptions)

**All Implemented Interfaces:**
[com.groupdocs.conversion.contracts.IDocumentsContainerLoadOptions](../../com.groupdocs.conversion.contracts/idocumentscontainerloadoptions)
```
public class CompressionLoadOptions extends LoadOptions implements IDocumentsContainerLoadOptions
```

압축 문서 불러오기 옵션.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CompressionLoadOptions()](#CompressionLoadOptions--) |   클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [isConvertOwner()](#isConvertOwner--) | 소유자는 변환되지 않습니다 |
| [isConvertOwned()](#isConvertOwned--) |  |
| [getDepth()](#getDepth--) |  |
| [setDepth(int depth)](#setDepth-int-) |  |
| [getPassword()](#getPassword--) |  |
| [setPassword(String password)](#setPassword-java.lang.String-) | 보호된 문서를 로드하기 위한 비밀번호를 설정합니다. |
| [getEqualityComponents()](#getEqualityComponents--) |  |
### CompressionLoadOptions() {#CompressionLoadOptions--}
```
public CompressionLoadOptions()
```


  클래스의 새 인스턴스를 초기화합니다.

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

### getPassword() {#getPassword--}
```
public String getPassword()
```




**Returns:**
java.lang.String
### setPassword(String password) {#setPassword-java.lang.String-}
```
public void setPassword(String password)
```


보호된 문서를 로드하기 위한 비밀번호를 설정합니다.

**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 비밀번호 | java.lang.String | 비밀번호 |

### getEqualityComponents() {#getEqualityComponents--}
```
public List<Object> getEqualityComponents()
```




**Returns:**
java.util.List<java.lang.Object>
