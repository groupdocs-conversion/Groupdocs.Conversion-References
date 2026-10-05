---
title: "OlmFolderInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Olm 폴더 정보"
type: docs
weight: 28
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/olmfolderinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.ValueObject](../../com.groupdocs.conversion.contracts/valueobject)
```
public class OlmFolderInfo extends ValueObject
```

Olm 폴더 정보
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [OlmFolderInfo(String name, int count)](#OlmFolderInfo-java.lang.String-int-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getName()](#getName--) | 폴더 이름 |
| [getItemsCount()](#getItemsCount--) | 폴더에 있는 항목 수 |
| [toString()](#toString--) | 개인 저장소 폴더 정보의 문자열 표현 형식은 FolderName (ItemsCount)입니다 |
### OlmFolderInfo(String name, int count) {#OlmFolderInfo-java.lang.String-int-}
```
public OlmFolderInfo(String name, int count)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |
| 수 | int |  |

### getName() {#getName--}
```
public String getName()
```


폴더 이름

**Returns:**
java.lang.String
### getItemsCount() {#getItemsCount--}
```
public int getItemsCount()
```


폴더에 있는 항목 수

**Returns:**
int
### toString() {#toString--}
```
public String toString()
```


개인 저장소 폴더 정보의 문자열 표현 형식은 FolderName (ItemsCount)입니다

**Returns:**
java.lang.String
