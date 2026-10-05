---
title: "DjVuDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "DjVu 문서 메타데이터를 포함합니다"
type: docs
weight: 15
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/djvudocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts/documentinfo/documentinfo), [com.groupdocs.conversion.contracts.documentinfo.ImageDocumentInfo](../../com.groupdocs.conversion.contracts/documentinfo/imagedocumentinfo)
```
public class DjVuDocumentInfo extends ImageDocumentInfo
```

DjVu 문서 메타데이터를 포함합니다
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [DjVuDocumentInfo(DjvuImage image, FileType format, long size)](#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getVerticalResolution()](#getVerticalResolution--) | 수직 해상도를 가져옵니다 |
| [getHorizontalResolution()](#getHorizontalResolution--) | 수평 해상도 가져오기 |
| [getOpacity()](#getOpacity--) | 이미지 불투명도 가져오기 |
### DjVuDocumentInfo(DjvuImage image, FileType format, long size) {#DjVuDocumentInfo-com.aspose.imaging.fileformats.djvu.DjvuImage-com.groupdocs.conversion.filetypes.FileType-long-}
```
public DjVuDocumentInfo(DjvuImage image, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | com.aspose.imaging.fileformats.djvu.DjvuImage |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 크기 | long |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


수직 해상도를 가져옵니다

**Returns:**
double - 수직 해상도
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


수평 해상도 가져오기

**Returns:**
double - 수평 해상도
### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


이미지 불투명도 가져오기

**Returns:**
float - 이미지 불투명도
