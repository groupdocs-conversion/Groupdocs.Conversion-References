---
title: "CadDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Cad 문서 메타데이터를 포함합니다"
type: docs
weight: 11
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/caddocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class CadDocumentInfo extends DocumentInfo
```

Cad 문서 메타데이터를 포함합니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CadDocumentInfo(Image cad, FileType format, long size)](#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWidth()](#getWidth--) | 너비 |
| [getHeight()](#getHeight--) | 높이 |
| [getLayouts()](#getLayouts--) | 문서의 레이아웃 |
| [getLayers()](#getLayers--) | 문서의 레이어 |
### CadDocumentInfo(Image cad, FileType format, long size) {#CadDocumentInfo-com.aspose.cad.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public CadDocumentInfo(Image cad, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| CAD | com.aspose.cad.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 크기 | long |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


너비

**Returns:**
int - 너비
### getHeight() {#getHeight--}
```
public int getHeight()
```


높이

**Returns:**
int - 높이
### getLayouts() {#getLayouts--}
```
public List<String> getLayouts()
```


문서의 레이아웃

**Returns:**
java.util.List<java.lang.String> - 문서의 레이아웃
### getLayers() {#getLayers--}
```
public List<String> getLayers()
```


문서의 레이어

**Returns:**
java.util.List<java.lang.String> - 문서의 레이어
