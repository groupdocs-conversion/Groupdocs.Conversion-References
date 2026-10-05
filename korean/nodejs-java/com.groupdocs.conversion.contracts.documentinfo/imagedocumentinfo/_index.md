---
title: "ImageDocumentInfo"
second_title: "Node.js용 GroupDocs.Conversion (Java 경유) API 레퍼런스"
description: "Image 문서 메타데이터 포함"
type: docs
weight: 23
url: /ko/nodejs-java/com.groupdocs.conversion.contracts.documentinfo/imagedocumentinfo/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.conversion.contracts.documentinfo.DocumentInfo](../../com.groupdocs.conversion.contracts.documentinfo/documentinfo)
```
public class ImageDocumentInfo extends DocumentInfo
```

Image 문서 메타데이터 포함
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ImageDocumentInfo(Image image, FileType format, long size)](#ImageDocumentInfo-com.aspose.imaging.Image-com.groupdocs.conversion.filetypes.FileType-long-) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | 픽셀당 비트 수를 가져옵니다 |
| [getHeight()](#getHeight--) | 높이를 가져옵니다 |
| [getWidth()](#getWidth--) | 너비를 가져옵니다 |
### ImageDocumentInfo(Image image, FileType format, long size) {#ImageDocumentInfo-com.aspose.imaging.Image-com.groupdocs.conversion.filetypes.FileType-long-}
```
public ImageDocumentInfo(Image image, FileType format, long size)
```


**Parameters:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| 이미지 | com.aspose.imaging.Image |  |
| format | [FileType](../../com.groupdocs.conversion.filetypes/filetype) |  |
| 크기 | long |  |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


픽셀당 비트 수를 가져옵니다

**Returns:**
int - 픽셀당 비트 수
### getHeight() {#getHeight--}
```
public int getHeight()
```


높이를 가져옵니다

**Returns:**
int - 높이
### getWidth() {#getWidth--}
```
public int getWidth()
```


너비를 가져옵니다

**Returns:**
int - 너비
